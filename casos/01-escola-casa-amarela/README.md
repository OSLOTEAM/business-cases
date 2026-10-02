# Escola Casa Amarela

**OSLO. · Business case · Processo seletivo**

*É a escola ou é o mercado? Um case de diagnóstico com dados públicos, os números de uma escola e uma recomendação para quem precisa decidir.*

[Baixar o enunciado em PDF](enunciado.pdf)

---

## Antes de começar

Este case é um problema real, com uma cliente fictícia. Não existe resposta pronta para copiar: existe uma pergunta, um contexto e dados que você vai precisar encontrar.

A **OSLO.** é um estúdio de tecnologia e inteligência de Curitiba. Integramos dados, construímos sistemas e aplicamos inteligência artificial em operações reais de empresas. Boa parte do nosso trabalho começa como este case: alguém tem um problema, uma intuição sobre a causa e uma decisão para tomar. Nosso papel é transformar isso em perguntas que dados conseguem responder e devolver uma recomendação que a pessoa entenda e consiga executar.

Queremos ver como você pensa: como estrutura um problema mal definido, onde procura informação, como trata dados imperfeitos, quanto confia nos próprios números e como comunica uma recomendação para alguém que não é da área.

Não precisa saber nada de educação. Precisa ter curiosidade, método e honestidade sobre o que conseguiu e o que não conseguiu medir.

- **7 dias** corridos, a partir do recebimento do case por e-mail.
- **10 slides** no máximo no deck principal, mais apêndice livre.
- **1 base**: planilha ou código que reproduza todos os números do deck.

### Regras

1. **O trabalho é individual.** Você pode conversar com quem quiser sobre o tema, mas a análise e o deck são seus.
2. **Os dados existem e são públicos.** Há bases oficiais e gratuitas sobre nascimentos, população, escolas e matrículas, professores e renda das famílias, muitas no nível de cada escola e de cada município. Encontrá-las, entendê-las e tratá-las faz parte do case. Não usamos dados pagos nem privados.
3. **Toda afirmação numérica precisa de fonte.** Cite a base, o ano e o link. Número sem fonte conta como número inventado.
4. **Pode usar inteligência artificial.** A OSLO. trabalha com IA todos os dias. Diga em uma página onde e como usou e como conferiu o que ela produziu.
5. **Prefira estar certo a estar completo.** Uma análise menor e bem feita vale mais do que todas as perguntas respondidas pela metade.

## A cliente: Escola Casa Amarela

*Uma escola de educação infantil de bairro em Curitiba, há 17 anos no mesmo endereço, que viu o número de alunos cair 29% em cinco anos e não sabe se o problema é dela ou do mundo.*

> Escola, pessoas e números da escola são fictícios. Qualquer semelhança com uma escola real é coincidência.

A Casa Amarela fica no Cristo Rei, bairro residencial de classe média próximo ao centro de Curitiba. Atende crianças de 4 meses a 5 anos, do berçário ao pré II, e não oferece ensino fundamental. É uma escola privada sem convênio com o poder público: toda a receita vem das mensalidades.

A fundadora e diretora, Marta, abriu a escola em 2008. Até 2019 havia fila de espera em quase todas as turmas. Desde então, a escola perde alunos todo ano, com exceção da recuperação de 2022. Em 2025 o caixa ficou negativo pela primeira vez, e Marta precisou usar reservas para pagar o 13º.

Ela procurou a OSLO. depois de receber, no mesmo mês, uma proposta de compra de um grupo educacional e um convite da prefeitura para conversar sobre vagas conveniadas de creche.

### O e-mail da Marta

> "Preciso entender se eu fiz alguma coisa errada ou se o mundo mudou. Todo mundo me diz que 'nascem menos crianças', mas eu vejo escola nova abrindo perto daqui e vejo as famílias levando os filhos embora quando fazem 4 anos. Uma amiga diretora diz que eu deveria fazer um parque maior e oferecer integral para todo mundo. Outra diz que eu deveria aceitar a proposta e vender enquanto vale alguma coisa. A prefeitura quer comprar vagas, mas não sei se o valor paga a conta.
>
> Também nunca foi tão difícil contratar professora: perdi cinco este ano e levei dois meses para repor uma. E a cada ano chegam mais crianças com laudo ou em investigação. Eu quero saber o que está acontecendo, o que vai acontecer até 2030 e o que eu faço agora. Quero números, não opinião."

### O que a Marta acredita hoje

1. **"O problema é a concorrência no bairro."** Ela acha que escolas novas tiraram os alunos dela.
2. **"Preciso de mais estrutura."** Parque maior, mais área verde e integral para todas as turmas.
3. **"Em Curitiba todo mundo está perdendo aluno."** Mas ela não sabe se perde mais ou menos que as outras.
4. **"Escola pequena não tem futuro; o setor está sendo comprado pelos grupos."** Por isso a proposta de compra a preocupa.

Algumas dessas crenças podem estar certas, outras não. Parte do seu trabalho é dizer quais, com evidência.

## Os números da Casa Amarela

*Tudo o que a escola tem registrado. Os dados de mercado, de população e de renda você precisa buscar.*

**Alunos matriculados por turma, em março de cada ano**

| Turma | Idade | Vagas | 2020 | 2021 | 2022 | 2023 | 2024 | 2025 |
|---|:-:|--:|--:|--:|--:|--:|--:|--:|
| Berçário | 0–1 | 12 | 10 | 6 | 11 | 10 | 9 | 9 |
| Maternal I | 1–2 | 16 | 14 | 10 | 15 | 15 | 14 | 15 |
| Maternal II | 2–3 | 20 | 19 | 15 | 18 | 19 | 18 | 18 |
| Maternal III | 3–4 | 22 | 21 | 17 | 19 | 18 | 18 | 17 |
| Pré I | 4–5 | 25 | 23 | 19 | 18 | 16 | 13 | 11 |
| Pré II | 5–6 | 25 | 22 | 18 | 16 | 13 | 10 | 7 |
| **Total** | | **120** | **109** | **85** | **97** | **91** | **82** | **77** |

*Berçário a Maternal III = creche (0 a 3 anos); Pré I e II = pré-escola (4 e 5 anos). Em 2025, 31 dos 77 alunos estão em período integral.*

**Mensalidades em 2025**

| Plano | Valor mensal | Alunos |
|---|--:|--:|
| Meio período (4h30) | R$ 1.690 | 46 |
| Integral (10h) | R$ 2.640 | 31 |

*Inadimplência e descontos somam cerca de 8% da receita bruta. Reajuste anual pela inflação; não houve aumento real desde 2019.*

**Por que as famílias saíram (2023–2025)**

| Motivo declarado | Famílias |
|---|--:|
| Foi para escola que tem ensino fundamental | 20 |
| Mudou de cidade (a maioria para a região metropolitana) | 11 |
| Conseguiu vaga em escola pública | 9 |
| Motivo financeiro | 6 |
| Outros | 6 |
| **Total** | **52** |

*Conversa de saída com as famílias que não rematricularam. Não inclui as crianças que concluíram o Pré II.*

**Custos mensais médios em 2025**

| Item | R$ por mês |
|---|--:|
| Folha, encargos e pró-labore (22 pessoas) | 108.000 |
| Aluguel do imóvel | 19.000 |
| Alimentação (varia com o número de alunos) | 15.000 |
| Energia, manutenção, material, sistemas | 13.000 |
| **Total** | **155.000** |

**Equipe e rotina**

| Item | |
|---|--:|
| Professoras | 8 |
| Auxiliares de sala | 8 |
| Coordenação, secretaria, cozinha, limpeza | 5 |
| Direção (Marta) | 1 |
| Saídas de professoras e auxiliares em 2025 | 5 |
| Tempo médio para repor uma professora | ~2 meses |
| Crianças com laudo ou em investigação (2020 → 2025) | 1 → 4 |

## As opções na mesa

Marta não precisa escolher uma só, mas tem caixa para no máximo uma iniciativa que exija investimento em 2026.

- **A. Conveniar vagas de creche com a prefeitura.** A prefeitura quer comprar vagas de creche, de preferência em período integral. O valor por criança ainda não foi informado.
- **B. Abrir o 1º ano do ensino fundamental em 2027.** Exige reforma estimada em R$ 380 mil, duas salas novas e autorização da Secretaria de Educação.
- **C. Abrir uma segunda unidade na região metropolitana.** Marta tem um imóvel de família disponível para locação num município vizinho, mas não sabe se há demanda nem quanto as famílias de lá podem pagar.
- **D. Aceitar a proposta de compra do grupo educacional.** O grupo diz que "o setor está se consolidando rápido" e que escolas independentes vão desaparecer.
- **E. Ajustar a operação.** Fechar ou juntar turmas, renegociar o aluguel, rever preços e planos.

### Algumas dicas antes de começar

1. **Comece pela pergunta, não pela base.** Escreva as hipóteses antes de baixar qualquer arquivo.
2. **Desconfie de quebras.** Bases públicas mudam de formato, de nome de campo e de definição ao longo dos anos. Um salto de um ano para o outro pode ser método, não realidade.
3. **"Privada" pode ser mais de uma coisa.** Leia as definições antes de comparar.
4. **Correlação não é causa.** Se escolas com uma característica fecham menos, pergunte o que mais elas têm em comum.
5. **A Marta não é analista.** Se ela não entender o slide em 30 segundos, o slide não funcionou.

## Cinco perguntas e três bônus

*As perguntas seguem a ordem em que um bom diagnóstico costuma ser construído, mas você pode reorganizar. Responda as cinco obrigatórias antes de ir para os bônus.*

**1. Diagnóstico — É a escola ou é o mercado?**
Quanto da queda de alunos da Casa Amarela é explicado por fatores que afetam todas as escolas e quanto é próprio dela? Olhe para o Brasil, o Paraná, Curitiba e o bairro, e compare creche e pré-escola separadamente.

**2. Mercado — Como está e para onde vai o mercado de educação infantil?**
Quem atende as crianças hoje (rede pública, escolas privadas com e sem convênio) e quem está crescendo? O que deve acontecer até 2030? Construa ao menos dois cenários e diga de quais premissas eles dependem.

**3. Risco — Por que algumas escolas fecham e outras não?**
Quais características de uma escola privada de educação infantil estão associadas a maior ou menor chance de fechar ou deixar de atender a etapa? Qual é o risco da Casa Amarela, e como cada opção na mesa muda esse risco? Confirme ou derrube as crenças da Marta.

**4. Demanda — Onde estão as famílias e quem pode pagar?**
Para onde a demanda está se movendo dentro de Curitiba e na região metropolitana? Que relação existe entre a renda das famílias, o trabalho das mães e a procura por escola privada?

**5. Recomendação — O que a Marta deve fazer?**
Avalie as opções A a E com números: resultado mensal atual, ponto de equilíbrio, quanto vale uma vaga conveniada perto do custo de uma vaga, investimento e risco. Recomende um plano para 2026–2028, com o que fazer primeiro e em que condições mudar de rota.

### Bônus

- **a) Professores.** A dificuldade de contratar é da Casa Amarela ou é estrutural? O que os dados sobre formação de professores dizem para os próximos anos?
- **b) Inclusão.** A chegada de mais crianças com deficiência ou transtornos do desenvolvimento é uma percepção da escola ou uma tendência? Como a escola de mensalidade se compara à rede pública?
- **c) Consolidação.** O grupo diz que o setor está se consolidando. Isso é verdade? Como você mediria?

## O que enviar e como

Envie por e-mail para **contato@oslostudio.com.br**, dentro do prazo, com quatro itens. Não abra pull request nem publique sua solução.

1. **Deck principal (PDF, até 10 slides).** Escrito para a Marta: cada título é uma conclusão, cada gráfico tem fonte. O apêndice pode ter quantos slides quiser.
2. **Base reproduzível.** Planilha, notebook ou scripts que gerem todos os números do deck a partir dos dados originais, com um texto curto explicando como rodar. Se a base for grande, envie o link para baixar.
3. **Lista de fontes.** Cada base usada, com o ano, o link e o que você filtrou ou ajustou.
4. **Uma página de bastidores.** Como você usou IA, o que não conseguiu medir, as premissas que mais preocupam você e o que faria com mais uma semana.

### Como avaliamos

- **Estruturação:** você transforma a dor da cliente em perguntas testáveis e prioriza as que mudam a decisão.
- **Dados:** você acha as bases certas, entende o que cada campo mede e trata quebras e inconsistências.
- **Rigor:** definições explícitas, comparações justas, cuidado com causa e correlação.
- **Diagnóstico e recomendação:** você usa os números da própria escola e chega a um plano com impacto quantificado.
- **Comunicação:** a cliente entende e decide.
- **Reprodutibilidade:** outra pessoa refaz seus números a partir da sua base.

### Depois da entrega

Avaliamos todos os cases com a mesma rubrica, com dois avaliadores. As pessoas selecionadas são chamadas para uma conversa de 45 minutos: 20 minutos para apresentar à Marta (alguém da OSLO. faz o papel dela), 15 minutos de perguntas sobre o trabalho e 10 minutos para uma pergunta nova, sem aviso prévio, para pensarmos juntos.

Na conversa vamos pedir que você abra suas fontes e refaça um número. Não decore o deck: entenda o que fez.

**Dúvidas** sobre o enunciado podem ser enviadas por e-mail até o terceiro dia; respondemos a todos os candidatos com a mesma informação. Não respondemos onde encontrar os dados.

---

Intelligence, refined. · [oslostudio.com.br](https://oslostudio.com.br)
