# 🏎️ Porsche Sales Intelligence

Dashboard interativa desenvolvida em HTML para análise de vendas de veículos Porsche, com foco na organização e sanitização dos dados, visualização de indicadores e identificação de padrões comerciais.

O projeto combina o uso de Inteligência Artificial no tratamento da base de dados com visualizações interativas para transformar registros de vendas em informações relevantes para a tomada de decisão.

## 🎯 Objetivo do projeto

Desenvolver uma dashboard que permita explorar o desempenho comercial dos modelos Porsche, identificar preferências de consumo por cidade e analisar a distribuição das vendas de acordo com o ano do modelo e o método de pagamento.

## 🧠 Uso de Inteligência Artificial

Durante o desenvolvimento, foi utilizado um agente de Inteligência Artificial para auxiliar na sanitização e padronização da base de dados.

O objetivo foi melhorar a consistência das informações e preparar os dados para análises mais confiáveis, reduzindo possíveis problemas decorrentes de inconsistências nos registros.

### Etapas de tratamento da base

- **Inspeção dos dados:** análise da estrutura da base, identificação das colunas disponíveis e compreensão dos campos relevantes para o negócio.
- **Padronização de categorias:** normalização dos nomes de modelos, cidades e métodos de pagamento, quando necessário.
- **Tratamento de inconsistências:** identificação de possíveis variações de escrita, formatos divergentes e valores que poderiam prejudicar a análise.
- **Verificação dos anos de modelo:** organização do campo `Model Year` para permitir comparações entre os anos.
- **Preparação para análise:** estruturação dos campos utilizados nos filtros, KPIs e gráficos da dashboard.

O agente de IA foi utilizado como apoio ao processo de preparação dos dados, com foco na qualidade, consistência e usabilidade da base.

> **Observação:** as etapas representam o escopo do tratamento realizado no projeto. A aplicação efetiva de cada transformação deve ser validada de acordo com o arquivo final utilizado na dashboard.

## 💬 Prompt utilizado

O desenvolvimento da interface foi orientado por um prompt com requisitos de negócio, filtros interativos e identidade visual.

```text
Utilizando o recurso de Canvas, desenvolva uma
dashboard interativa em HTML para análise de
vendas de veículos Porsche.

Filtros:
- Modelo da Porsche
- Model Year
- City
- Pay Method

Perguntas de negócio:
- Quais são os principais modelos de carros
  vendidos por cidade?
- Qual ano de modelo apresentou o maior
  volume de vendas em determinado período?
- Quais modelos são populares em cada cidade,
  considerando os dados disponíveis?

Design e experiência do usuário:
- Utilizar como referência visual o site oficial
  da Porsche Brasil.
- Criar uma interface elegante, refinada e
  minimalista.
- Priorizar legibilidade, hierarquia visual
  e facilidade de navegação.
- Apresentar KPIs, gráficos e insights que
  facilitem a interpretação dos dados.
- Garantir que os filtros atualizem as
  visualizações de acordo com a seleção.
```

## 📊 Principais análises de negócio

### 1. Modelos mais vendidos por cidade

Identificar quais modelos Porsche apresentam maior volume de vendas em cada cidade, permitindo comparar preferências regionais e reconhecer os modelos de maior destaque em cada localidade.

**Perguntas respondidas:**
- Qual modelo lidera as vendas em cada cidade?
- Quais modelos apresentam maior presença em diferentes mercados?
- Existem diferenças nas preferências entre cidades?

### 2. Desempenho por ano do modelo

Analisar a distribuição das vendas por `Model Year` para identificar os anos de modelo com maior volume de registros.

**Perguntas respondidas:**
- Qual ano de modelo apresenta mais vendas?
- Como o volume de vendas se distribui entre os anos?
- Quais anos se destacam quando os filtros são aplicados?

### 3. Popularidade dos modelos por cidade

Explorar a concentração das vendas por modelo e cidade para identificar padrões de preferência e oportunidades de aprofundamento comercial.

**Perguntas respondidas:**
- Quais modelos se destacam em cada cidade?
- Quais modelos aparecem com frequência em diferentes localidades?
- Como o ranking de modelos muda conforme a cidade selecionada?

### 4. Análise dos métodos de pagamento

Avaliar a distribuição dos registros de vendas de acordo com `Pay Method`, identificando os métodos mais utilizados na base.

**Perguntas respondidas:**
- Qual método de pagamento possui maior volume de registros?
- Como os métodos se distribuem entre as vendas?
- Existem diferenças na distribuição conforme o modelo ou a cidade?

## 📌 KPIs da dashboard

Os indicadores permitem acompanhar os principais aspectos do conjunto de dados.

| Indicador | Objetivo |
|---|---|
| Total de vendas | Quantificar os registros de vendas considerados na análise |
| Receita total | Consolidar os valores monetários registrados na base |
| Modelo líder | Identificar o modelo com maior volume de vendas |
| Ano de modelo líder | Encontrar o `Model Year` com maior frequência |
| Modelo líder por cidade | Comparar os modelos mais vendidos em cada localidade |

Os valores dos indicadores variam conforme os filtros selecionados.

## 🎛️ Filtros interativos

A dashboard conta com quatro filtros principais:

- **Modelo da Porsche:** permite analisar modelos específicos.
- **Model Year:** restringe a análise ao ano de modelo selecionado.
- **City:** permite explorar os resultados por cidade.
- **Pay Method:** possibilita comparar os métodos de pagamento.

A combinação dos filtros permite criar diferentes recortes analíticos e aprofundar a investigação dos dados.

## 🎨 Interface e experiência do usuário

A interface foi inspirada na identidade visual do site oficial da Porsche Brasil, priorizando uma apresentação sofisticada e minimalista.

Principais características:

- Design elegante com referências à identidade visual da marca.
- Hierarquia visual para destacar os indicadores mais relevantes.
- Gráficos orientados à comparação e identificação de padrões.
- Filtros para exploração dinâmica dos dados.
- Organização dos componentes com foco em legibilidade e experiência do usuário.

Referência visual: [Porsche Brasil](https://www.porsche.com/brazil/pt/)

## 🛠️ Tecnologias e recursos utilizados

- **HTML:** estrutura da dashboard.
- **CSS:** estilização e organização visual dos componentes.
- **JavaScript:** interatividade, filtros e atualização das visualizações.
- **Inteligência Artificial:** apoio à sanitização dos dados e desenvolvimento da interface.
- **GitHub:** versionamento e documentação do projeto.
- **GitHub Pages:** publicação da dashboard, quando habilitado.

## 📁 Estrutura do projeto

```text
porsche-sales-intelligence/
├── index.html
├── README.md
└── dados/
    └── base_tratada.xlsx
```

A pasta `dados/` é opcional e deve ser incluída somente se a base puder ser compartilhada. Os nomes dos arquivos devem corresponder aos arquivos efetivamente existentes no repositório.

## 🚀 Como executar

1. Clone ou baixe este repositório.
2. Abra o arquivo `index.html` em um navegador.
3. Utilize os filtros para explorar os dados e visualizar os indicadores.

Caso o projeto esteja publicado no GitHub Pages, acesse a versão online pelo link disponibilizado no repositório.

## 📈 Aprendizados e competências desenvolvidas

Este projeto permitiu explorar conceitos e práticas relacionados a:

- Preparação e qualidade de dados.
- Sanitização e padronização de informações com auxílio de IA.
- Análise exploratória de dados.
- Definição de KPIs e perguntas de negócio.
- Visualização de dados e construção de dashboards.
- Desenvolvimento de interfaces com HTML, CSS e JavaScript.
- Transformação de dados em informações úteis para a tomada de decisão.

## 📂 Fonte de dados

A análise utiliza uma base de dados de vendas de veículos Porsche para fins educacionais e de desenvolvimento de portfólio.

Os resultados dependem dos registros disponíveis na base e não representam necessariamente o desempenho comercial real da Porsche.

---

*Projeto desenvolvido para fins de estudo, prática de análise de dados e construção de portfólio profissional.*
