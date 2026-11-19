# GLOBAL SOLUTION — CITIZEN ASSIST AI

## Energia Inteligente: Economia e Sustentabilidade nas Residências

**Global Solution 02 — 2026**

## 1. Identificação do projeto

**Disciplina:** Soluções em Energias Renováveis e Sustentáveis  
**Curso:** Ciência da Computação  
**Turma:** 1CCA — Diurno  
**Projeto:** Global Solution 02

### Integrantes

| Integrante | RM |
|---|---|
| Giulliana Maistro Brasolin | 569381 |
| Lara Dos Santos Cândido Alves | 573827 |
| Mikaella Mirela Dos Santos Lucindo | 573775 |

## 2. Apresentação do projeto

O Citizen Assist AI é um projeto voltado à análise do consumo de energia elétrica em residências e à identificação de alternativas que contribuam para a redução dos gastos e para a sustentabilidade.

A proposta consiste em utilizar análise de dados e programação em Python para avaliar o consumo energético de uma residência hipotética, identificar os equipamentos que mais consomem energia e comparar alternativas de economia e geração de energia renovável.

A partir dos resultados obtidos, foi desenvolvido um protótipo de assistente interativo que apresenta informações e orientações sobre consumo residencial, eficiência energética e energia solar fotovoltaica.

## 3. Problema e público-alvo

O projeto aborda a dificuldade que muitos moradores encontram para compreender o consumo de energia elétrica de suas residências, identificar os equipamentos responsáveis pelos maiores gastos e avaliar alternativas que possam reduzir os custos da conta de luz.

O público-alvo são moradores de residências no município de São Paulo, SP, que desejam compreender melhor seu consumo energético, economizar energia e conhecer alternativas de fornecimento mais sustentáveis.

Para desenvolver as análises, foi definido um cenário residencial hipotético com as seguintes características:

| Característica | Definição |
|---|---|
| Localização | São Paulo - SP |
| Tipo de imóvel | Casa residencial |
| Número de moradores | 4 pessoas |
| Quartos | 2 |
| Banheiros | 1 |
| Fornecimento de energia | Rede elétrica convencional |

A residência foi criada exclusivamente para a realização das simulações. Portanto, os resultados não representam medições de uma residência real nem uma média oficial de consumo familiar.

## 4. Funcionalidades desenvolvidas

O projeto contempla duas frentes principais: a análise computacional do consumo energético e o desenvolvimento de um assistente interativo.

### 4.1. Análise energética

Foram desenvolvidos cálculos e simulações para:

- Estimar o consumo mensal e anual de energia elétrica da residência.
- Identificar os equipamentos com maior participação no consumo.
- Comparar o consumo de lâmpadas convencionais e lâmpadas LED.
- Calcular a economia energética e financeira proporcionada pela substituição das lâmpadas.
- Dimensionar um sistema de geração solar fotovoltaica.
- Estimar a geração mensal de energia solar.
- Comparar investimentos, economias e prazos estimados de retorno financeiro.
- Avaliar os impactos ambientais das alternativas analisadas.

### 4.2. Assistente Citizen Assist AI

Foi desenvolvido um protótipo interativo em Python, baseado em funções e estruturas condicionais, que apresenta orientações ao usuário por meio de um menu de opções.

As funcionalidades disponíveis são:

| Opção | Funcionalidade |
|---|---|
| 1 | Diagnóstico de consumo |
| 2 | Orientação sobre redução do tempo de banho |
| 3 | Informações sobre lâmpadas LED |
| 4 | Informações sobre energia solar fotovoltaica |
| 5 | Comparação das alternativas |
| 6 | Consulta às fontes e limitações |
| 7 | Orientações para dúvidas |
| 0 | Encerramento do atendimento |

O assistente utiliza os resultados calculados nas etapas anteriores para apresentar informações e recomendações relacionadas ao cenário residencial analisado.

O protótipo não utiliza inteligência artificial generativa. Sua lógica de orientação é baseada em regras previamente definidas e respostas programadas em Python.

## 5. Dados utilizados e premissas

Para a construção do cenário, foram utilizados dados de referência de fontes institucionais e técnicas, além de estimativas estabelecidas pelo grupo.

A principal fonte de dados municipais foi a Secretaria de Meio Ambiente, Infraestrutura e Logística do Estado de São Paulo (SEMIL), por meio do Anuário de Energéticos por Municípios do Estado de São Paulo 2025, ano-base 2024.

Segundo o levantamento, o município de São Paulo apresentou:

- Consumidores residenciais: 5.100.843.
- Consumo residencial anual: 12.700.203.908 kWh.
- Consumo médio mensal por unidade consumidora: aproximadamente 207,5 kWh.

Esse valor foi utilizado como referência de comparação para a residência hipotética.

Também foram adotadas as seguintes premissas:

- Potências dos equipamentos e tempos de utilização estimados pelo grupo.
- Período de referência de 30 dias para os cálculos mensais.
- Fator de funcionamento de 0,35 para o compressor da geladeira.
- Lâmpadas convencionais de 60 W e lâmpadas LED de 9 W, consideradas de iluminação equivalente.
- Tarifa de referência de R$ 0,63624/kWh, correspondente à tarifa Enel SP B1 no período de 04/07/2024 a 03/07/2025.
- Produtividade solar de 113,5 kWh/kWp/mês para São Paulo.

As premissas foram utilizadas para construir um cenário comparativo. Os resultados dependem dos valores adotados e podem variar em situações reais.

## 6. Cálculos e comparação das alternativas

Foram analisadas duas alternativas principais: a substituição de lâmpadas convencionais por modelos LED e a instalação de um sistema de geração solar fotovoltaica conectado à rede elétrica (on-grid).

Também foi considerada a redução do tempo de banho como uma alternativa comportamental de economia.

### 6.1. Substituição por lâmpadas LED

A análise considerou oito lâmpadas convencionais de 60 W, utilizadas durante cinco horas por dia, substituídas por lâmpadas LED de 9 W.

| Indicador | Resultado |
|---|---:|
| Consumo convencional | 72,0 kWh/mês |
| Consumo com LED | 10,8 kWh/mês |
| Economia mensal | 61,2 kWh |
| Redução do consumo das lâmpadas | 85% |
| Novo consumo residencial | 318,6 kWh/mês |
| Economia financeira mensal | R$ 38,94 |
| Economia financeira anual | R$ 467,25 |

Foram considerados dois cenários de investimento:

- Preço de referência de compra pública: R$ 25,84 para as oito lâmpadas.
- Preço estimado de varejo: R$ 96,00 para as oito lâmpadas.

A substituição por LED apresenta baixo investimento inicial e redução imediata do consumo energético.

### 6.2. Dimensionamento do sistema solar fotovoltaico

O dimensionamento foi realizado considerando o consumo residencial após a substituição das lâmpadas por LED, de 318,6 kWh/mês.

Com produtividade solar estimada de 113,5 kWh/kWp/mês, a potência calculada foi de aproximadamente 2,81 kWp.

Para a simulação, foi escolhido um sistema de 3,0 kWp, composto por seis módulos fotovoltaicos de 500 Wp.

| Indicador | Resultado |
|---|---:|
| Consumo de referência | 318,6 kWh/mês |
| Potência calculada | 2,81 kWp |
| Potência instalada simulada | 3,0 kWp |
| Quantidade de módulos | 6 |
| Potência por módulo | 500 Wp |
| Geração mensal estimada | 340,5 kWh |
| Investimento estimado | R$ 7.290,00 |

A geração mensal estimada supera o consumo de referência da residência. Entretanto, a economia financeira efetiva depende das regras de compensação de energia, do custo de disponibilidade e das condições de instalação.

### 6.3. Comparação financeira das alternativas

A comparação considera os investimentos, a economia mensal, o prazo estimado de retorno financeiro e a redução de emissões de CO₂.

| Alternativa | Investimento | Economia mensal |
|---|---:|---:|
| Redução de 10 minutos no banho | R$ 0,00 | 27,5 kWh |
| LED — preço público | R$ 25,84 | 61,2 kWh |
| LED — preço de varejo | R$ 96,00 | 61,2 kWh |
| Solar 3 kWp — sem custo de disponibilidade | R$ 7.290,00 | 318,6 kWh |
| Solar 3 kWp — com custo de disponibilidade | R$ 7.290,00 | 268,6 kWh |

Para o sistema solar, foram obtidos os seguintes prazos estimados de retorno:

- Aproximadamente 36 meses, considerando a compensação integral.
- Aproximadamente 42,7 meses, considerando o custo de disponibilidade.

Os resultados demonstram que a substituição por LED exige menor investimento inicial, enquanto a energia solar apresenta maior potencial de geração renovável, mas exige um investimento significativamente maior.

As alternativas podem ser combinadas, permitindo reduzir o consumo da residência e complementar a economia com a geração de energia solar.

## 7. Tecnologias e ferramentas utilizadas

O desenvolvimento foi realizado utilizando as seguintes tecnologias:

| Tecnologia | Aplicação |
|---|---|
| Python | Desenvolvimento dos cálculos, simulações e lógica do assistente |
| Pandas | Organização, manipulação e análise dos dados |
| Matplotlib | Construção de gráficos e visualização dos resultados |
| Google Colab | Ambiente de desenvolvimento e execução do notebook |
| GitHub | Armazenamento e compartilhamento do projeto |

## 8. Como executar ou testar a solução

O projeto foi desenvolvido em um notebook Python (`.ipynb`), utilizando o ambiente Google Colab.

**Acesso ao notebook:**

[Citizen Assist AI — Notebook no GitHub](https://github.com/Miiixy/GS-02-CITIZEN-ASSIST-AI/blob/main/Citizen_Assist_AI_Energia_Sustentavel.ipynb)

Para executar:

1. Acesse o notebook pelo link disponibilizado acima.
2. Abra o arquivo no Google Colab ou faça seu download.
3. Caso necessário, selecione o ambiente de execução Python 3.
4. Execute as células na ordem apresentada, utilizando a opção "Executar tudo".
5. Aguarde a execução dos cálculos e a apresentação das tabelas e gráficos.
6. Ao chegar à etapa do assistente, utilize o menu interativo para consultar as opções disponíveis.

As bibliotecas Pandas e Matplotlib são utilizadas nas análises. Caso não estejam disponíveis no ambiente, devem ser instaladas antes da execução.

## 9. Testes e validação com usuários

Foram realizados testes funcionais para verificar o comportamento do protótipo diante de diferentes entradas e opções selecionadas.

Os testes contemplaram consultas às funcionalidades, verificação das respostas esperadas e identificação de entradas inválidas.

**Resultados dos testes funcionais:**

| Indicador | Resultado |
|---|---:|
| Testes executados | 8 |
| Testes aprovados | 8 |
| Testes reprovados | 0 |

Também foram realizados testes de usabilidade com três participantes, identificados como P1, P2 e P3.

As situações avaliadas envolveram a consulta ao consumo e à economia com LED, a consulta à alternativa de energia solar e a comparação entre as alternativas.

Todos os participantes conseguiram utilizar o menu e compreenderam as respostas apresentadas.

Durante a avaliação, foram identificadas duas sugestões de melhoria:

- Disponibilizar uma orientação para usuários que desejassem enviar dúvidas.
- Utilizar uma linguagem mais simples para explicar os conceitos técnicos.

Com base nas sugestões, foram realizados os seguintes ajustes:

- Inclusão da opção 7, com orientações para dúvidas e indicação de canais de atendimento.
- Inclusão de explicações sobre os conceitos de kWh, kWp e payback nas respostas do assistente.

O terceiro participante não identificou dificuldades nem sugeriu alterações adicionais.

Devido ao número reduzido de participantes, os resultados indicam apenas uma avaliação inicial de usabilidade e não podem ser generalizados para todos os usuários.

## 10. Limitações da solução

O Citizen Assist AI é um protótipo introdutório baseado em regras condicionais e dados previamente calculados.

Entre suas principais limitações estão:

- Não realiza medições de consumo em tempo real.
- Não acessa contas de energia dos usuários.
- Não possui integração com distribuidoras de energia ou sistemas fotovoltaicos.
- Não utiliza dados personalizados de uma residência real.
- Não recebe mensagens livres dos usuários.
- Não substitui uma avaliação técnica especializada.

Além disso, os cálculos financeiros e energéticos possuem limitações. A simulação não considera integralmente tributos, bandeiras tarifárias, cobrança do Fio B prevista na Lei nº 14.300/2022, manutenção do sistema solar, substituição do inversor, degradação dos módulos e reajustes futuros da tarifa.

Portanto, os valores apresentados devem ser interpretados como estimativas para fins de análise e comparação, e não como garantias de economia ou retorno financeiro.

## 11. Referências

**SEMIL — Secretaria de Meio Ambiente, Infraestrutura e Logística do Estado de São Paulo.** Anuário de Energéticos por Municípios do Estado de São Paulo 2025 (ano-base 2024). 2. ed. São Paulo: SEMIL, 2025.

[Consultar publicação](https://smastr16.blob.core.windows.net/home/2026/03/Anuario-de-Energeticos-por-Municipios-do-Estado-de-Sao-Paulo-2025-ano-base-2024-1.pdf)

**ANEEL — Agência Nacional de Energia Elétrica.** Resolução Homologatória nº 3.339, de 2 de julho de 2024. Enel SP.

[Consultar resolução](https://www2.aneel.gov.br/cedoc/reh20243339.pdf)

**MME — Ministério de Minas e Energia.** Informativo Tarifário do Setor Elétrico, ano 2024.

[Consultar publicação](https://www.gov.br/mme/pt-br/assuntos/secretarias/secretaria-nacional-energia-eletrica/informativo-tarifario-do-setor-eletrico/informativo-tarifario-do-setor-eletrico-ano-2024.pdf)

**CALCULAKWH.** O que é kWp e como funciona o dimensionamento solar.

[Consultar material](https://calculakwh.com.br/artigos/kwp-o-que-e/)

**SOLARMAPPED / PVGIS.** Solar Potential in São Paulo.

[Consultar dados](https://solarmapped.com/brazil/sao-paulo)

**COMISSÃO EUROPEIA — Joint Research Centre (JRC).** PVGIS 5 User Manual.

[Consultar documentação](https://joint-research-centre.ec.europa.eu/photovoltaic-geographical-information-system-pvgis/using-pvgis-5/pvgis-5-user-manual_en)

**SOLFÁCIL / EIXOS.** Custo da energia solar residencial caiu 5% no terceiro trimestre de 2024.

[Consultar publicação](https://eixos.com.br/solar/custo-da-energia-solar-residencial-caiu-5-no-terceiro-trimestre-de-2024)

**BRASIL.** Lei nº 14.300, de 6 de janeiro de 2022. Marco Legal da Microgeração e Minigeração Distribuída.

[Consultar legislação](https://www.planalto.gov.br/ccivil_03/_ato2019-2022/2022/lei/l14300.htm)

**MCTI — Ministério da Ciência, Tecnologia e Inovação.** Fatores de Emissão de Gases de Efeito Estufa.

[Consultar dados](https://www.gov.br/mcti/pt-br/acompanhe-o-mcti/sirene/dados-e-ferramentas/fatores-de-emissao)

**SÃO PAULO — Compras Públicas.** Preço de referência de lâmpada LED de 9 W: R$ 3,23 por unidade, conforme premissas e registros de compras públicas utilizados pelo grupo.

Os preços de varejo das lâmpadas LED e demais valores estimados foram adotados como premissas do grupo, sem fonte documental específica.

## Vídeo

Link:

---

**GLOBAL SOLUTION 02 — 2026**

**Citizen Assist AI — Energia Inteligente: Economia e Sustentabilidade nas Residências.**
