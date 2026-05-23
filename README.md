# Claude Impact Lab — Rio de Janeiro

Bem-vindos ao **Claude Impact Lab** — um hackathon de um dia em parceria com a Prefeitura do Rio de Janeiro, focado em construir soluções com IA para desafios reais nas áreas de **saúde pública** e **segurança pública**.

Este não é um hackathon comum. Os problemas vêm diretamente do governo municipal, e os melhores projetos têm chance real de serem adotados para melhorar a vida no Rio. Você não está construindo uma demo para um painel — está construindo algo que pode ser implementado.

# 🗓️ Agenda

| Horário   | Momento                                 |
| --------- | --------------------------------------- |
| 8h30      | Boas-vindas e briefing dos problemas    |
| 9h30      | Início do hackathon e apoio de mentores |
| 12h00     | Almoço servido (não precisa parar)      |
| **16h15** | **Hora limite de entrega dos projetos** |
| 16h30     | Palestras no auditório                  |
| 17h30     | Apresentação dos times finalistas       |
| 18h30     | Premiação e encerramento                |

# 🎯 Os desafios

Você vai construir uma solução para **um** dos dois problemas abaixo, de acordo com o que foi selecionado para o seu time.

## Problema 1 — Saúde pública: Inteligência no Território

Os mais de 6.200 Agentes Comunitários de Saúde (ACS) do Rio conduzem visitas domiciliares ativas a 4,5 milhões de moradores em territórios vulneráveis. Hoje, o planejamento diário das visitas depende da memória de cada agente, de anotações em papel e do conhecimento informal do território — enquanto dados clínicos e sociais relevantes (cadastros de pacientes, consultas agendadas, atendimentos de urgência, histórico de visitas) permanecem dispersos nos sistemas da atenção primária e não chegam à mão de quem está em campo.

Os times devem transformar esses dados em inteligência acionável que responda, a cada manhã: **quem visitar, em que ordem e por quê**.

**Link para o problema completo:** <https://github.com/prefeitura-rio/claude-impact-lab-saude>

## Problema 2 — Segurança pública: CompStat Rio

O CompStat Rio é o modelo de gestão da segurança pública da Prefeitura, inspirado no CompStat do NYPD. Opera sobre 22 áreas prioritárias — definidas pela mancha criminal de furto e roubo — combinando o policiamento da **Força Municipal** (Divisão de Elite da Guarda Municipal) com a resolução de **20 fatores urbanos** que favorecem o crime (iluminação deficiente, vegetação encobrindo postes, calçadas obstruídas, mobiliário abandonado) pelos órgãos municipais responsáveis. Hoje, os relatórios semanais que orientam essas decisões são montados à mão, cruzando cinco fontes em silos: ocorrências georreferenciadas, Disque Denúncia, RELINTs, fatores urbanos e polígonos da Força Municipal.

Os times devem construir uma plataforma que cruze essas fontes e responda, para cada área: **onde e como patrulhar, e quais fatores urbanos resolver primeiro**.

**Link para o problema completo:** <https://github.com/CompStat-Rio/claude_impact_lab_compstat_rio>

# 📋 Regras

1. **O projeto começa no evento.** O primeiro commit deve ser feito após as 09:30 do dia 24/05. Projetos com evidências de desenvolvimento anterior serão desclassificados. Bibliotecas, frameworks e APIs preexistentes podem ser usados; a lógica do projeto tem que ser construída no dia.
2. **Uma submissão por equipe.** Cada equipe submete um único projeto pelo GitHub. Submissões progressivas são aceitas; vale a versão mais recente até o prazo.
3. **Prazo final: 16:15.** Submissões após esse horário serão desconsiderados.
4. **Repositório público no GitHub.** Os jurados precisam revisar o código. Você pode torná-lo privado após o encerramento.

> **Use os dados da cidade com responsabilidade.** Use APIs públicas, dados abertos e os dados fornecidos pelas secretarias neste repositório. Não faça scraping nem uso indevido dos sistemas da cidade. Os dados e recursos referenciados estão sujeitos aos termos de uso e licenciamento de suas respectivas fontes — cabe aos participantes revisá-los e cumpri-los.

## Conteúdo obrigatório do README

- **Nome da equipe**
- **Membros da equipe**
- **Tema:** saúde ou segurança
- **Resumo:** breve explicação da solução desenvolvida
- **Arquitetura / abordagem:** como o Claude foi usado para construir e como ele atua dentro da aplicação
- **Links:** URL da aplicação, se publicada
- **Vídeo demo:** demonstração de 60s. Opcional se a aplicação estiver publicamente acessível; **obrigatório** caso contrário.

# 🎤 Finalistas e apresentações

Serão selecionados até **3 times finalistas por problema** (saúde e segurança), totalizando até 6 apresentações. Cada time finalista terá **6 minutos** para apresentar sua solução aos jurados, no auditório, a partir das 17h30.

Use o tempo para mostrar a dor que o projeto resolve, demonstrar o protótipo ao vivo e ser honesto sobre o que está pronto hoje e o que viria em seguida. **Não será possível estourar o tempo:** ao chegar nos 6 minutos, a apresentação é encerrada.

# 🏆 Critérios de Julgamento

## Resumo

| #   | Critério       | Peso | Pergunta central                                                        |
| --- | -------------- | ---- | ----------------------------------------------------------------------- |
| 1   | _Impacto Real_ | 40   | A prefeitura usaria isso hoje para gerar impacto real?                  |
| 2   | _Produto_      | 20   | Qual a qualidade do design, da usabilidade e da experiência de uso?     |
| 3   | _Engenharia_   | 20   | Qual a qualidade técnica da solução e sua escalabilidade para produção? |
| 4   | _Ideia_        | 10   | Esquecendo o produto, quão inovadora e perspicaz é a ideia?             |
| 5   | _Apresentação_ | 10   | O quão bem o protótipo e a história foram apresentados?                 |

_Total:_ 100 pontos. Cada critério é pontuado de 1 a 5 e ajustado pelo peso correspondente.

---

## Rubrica 1–5

### 1. Impacto Real (peso 40)

A prefeitura usaria isso hoje gerando impacto real?

| Nota | Descritor                                                          |
| ---- | ------------------------------------------------------------------ |
| 5    | Pronto para usar como está; geraria impacto relevante imediato.    |
| 4    | Usaria em produção, fazendo melhorias; impacto claro e mensurável. |
| 3    | Usaria em piloto pequeno; impacto incremental.                     |
| 2    | Usaria com muito esforço e adaptação; impacto duvidoso.            |
| 1    | Não usaria; não está pronto ou não gera impacto.                   |

---

### 2. Produto (peso 20)

Qual a qualidade do produto: sua usabilidade, experiência de uso, design, etc.?

| Nota | Descritor                                                             |
| ---- | --------------------------------------------------------------------- |
| 5    | Produto polido; servidor não-técnico opera de primeira, sem treino.   |
| 4    | Bem desenhado, fluido e intuitivo; encaixa no fluxo de trabalho.      |
| 3    | Utilizável com curva curta; design aceitável, sem brilho.             |
| 2    | Funcional mas com atritos sérios; design duro, só usa quem é forçado. |
| 1    | Confuso, mal desenhado; exige treinamento e jargão técnico.           |

---

### 3. Engenharia (peso 20)

Qual a qualidade técnica da solução e sua escalabilidade para produção?

| Nota | Descritor                                                                 |
| ---- | ------------------------------------------------------------------------- |
| 5    | Pronto para produção; escalável, auditável, generalizável a outros casos. |
| 4    | Robusto, auditável, lida com dado ruidoso; caminho claro pra produção.    |
| 3    | End-to-end funcionando; reprodutível; precisa de retrabalho pra escalar.  |
| 2    | Funciona no caso feliz; frágil com dado sujo; longe de produção.          |
| 1    | Não funciona fora do cenário ensaiado; alucina; quebra com dado real.     |

---

### 4. Ideia (peso 10)

Esquecendo o que foi entregue, quão inovadora e eficaz é a ideia que tentaram?

| Nota | Descritor                                                 |
| ---- | --------------------------------------------------------- |
| 5    | Genuinamente nova; faz repensar o problema; insight raro. |
| 4    | Criativa, com ângulo original que destrava o problema.    |
| 3    | Sólida mas previsível; raciocínio defensável.             |
| 2    | Pequena variação do que já foi tentado.                   |
| 1    | Trivial; já existe; sem ângulo novo.                      |

---

### 5. Apresentação (peso 10)

O quão bem o protótipo e a história foram apresentados?

| Nota | Descritor                                                                          |
| ---- | ---------------------------------------------------------------------------------- |
| 5    | Pitch impecável; demo ao vivo impressiona; honesto sobre hoje vs. próximos passos. |
| 4    | Narrativa envolvente; demo ao vivo convincente; conexão com a dor real.            |
| 3    | Clara mas sem brilho; demo ao vivo funcionou no básico.                            |
| 2    | Narrativa fraca; demo gravada escondendo problemas.                                |
| 1    | Sem narrativa; demo falhou ou não houve; estourou o tempo.                         |

---

## Cálculo da nota final

Nota final = (Impacto Real × 8) + (Produto × 4) + (Engenharia × 4) + (Ideia × 2) + (Apresentação × 2)

Cada critério é pontuado de 1 a 5. Máximo possível: 100 pontos.

| Critério     | Multiplicador | Nota máx. |
| ------------ | ------------- | --------- |
| Impacto Real | × 8           | 40        |
| Produto      | × 4           | 20        |
| Engenharia   | × 4           | 20        |
| Ideia        | × 2           | 10        |
| Apresentação | × 2           | 10        |
| _Total_      |               | _100_     |
