# Tech Challenge — Fase 1 | Data Analytics

## Sobre o projeto

Este projeto consiste no desenvolvimento de uma análise de dados aplicada ao setor de e-commerce, utilizando o **Brazilian E-Commerce Public Dataset by Olist**.

A proposta do desafio é transformar dados transacionais em uma narrativa analítica clara, capaz de apresentar informações relevantes sobre o desempenho comercial do e-commerce e apoiar a tomada de decisão de investidores e acionistas.

O projeto será desenvolvido em Python, utilizando Jupyter Notebook, com foco na exploração, preparação, análise e visualização dos dados.

---

## Objetivo

Desenvolver um relatório executivo baseado nos dados do e-commerce brasileiro, buscando identificar informações relevantes sobre o desempenho do negócio, padrões de comportamento, tendências e oportunidades que possam gerar insights estratégicos.

A análise será conduzida de forma orientada ao negócio, priorizando a transformação dos dados em informações compreensíveis e relevantes para a tomada de decisão.

---

## Base de dados

**Brazilian E-Commerce Public Dataset by Olist**

O conjunto de dados disponibilizado pela Olist contém informações sobre pedidos realizados em uma plataforma de comércio eletrônico brasileiro, abrangendo diferentes aspectos da operação.

As bases utilizadas no projeto estão armazenadas localmente na pasta `data/`, em arquivos CSV separados.

### Arquivos disponíveis

| Arquivo | Descrição |
|---|---|
| `olist_customers_dataset.csv` | Informações sobre os clientes |
| `olist_geolocation_dataset.csv` | Dados geográficos relacionados às localidades |
| `olist_order_items_dataset.csv` | Itens associados aos pedidos |
| `olist_order_payments_dataset.csv` | Informações sobre pagamentos |
| `olist_order_reviews_dataset.csv` | Avaliações dos pedidos |
| `olist_orders_dataset.csv` | Informações gerais sobre os pedidos |
| `olist_products_dataset.csv` | Informações sobre os produtos |
| `olist_sellers_dataset.csv` | Informações sobre os vendedores |
| `product_category_name_translation.csv` | Tradução dos nomes das categorias de produtos |

As bases possuem diferentes estruturas e relacionamentos, sendo necessário compreender suas características antes da realização das análises.

---

## Metodologia

O projeto será conduzido utilizando a metodologia **CRISP-DM (Cross-Industry Standard Process for Data Mining)**, estruturada em seis etapas.

### 1. Entendimento do negócio (Business Understanding)

Compreender o contexto do negócio, os objetivos do projeto, as necessidades analíticas e os problemas que podem ser investigados a partir dos dados disponíveis.

### 2. Entendimento dos dados (Data Understanding)

Explorar as bases de dados, identificar suas estruturas, variáveis, relacionamentos, características e limitações, avaliando sua adequação aos objetivos do projeto.

### 3. Preparação dos dados (Data Preparation)

Realizar a limpeza, tratamento, integração e transformação dos dados, preparando as informações para as análises.

### 4. Modelagem (Modeling)

Aplicar técnicas analíticas e estatísticas para identificar padrões, tendências, relações e comportamentos relevantes para o negócio.

### 5. Avaliação (Evaluation)

Avaliar os resultados obtidos, verificando sua consistência, relevância e alinhamento com os objetivos inicialmente definidos.

### 6. Implementação (Deployment)

Organizar e apresentar os resultados por meio de um relatório executivo, visualizações de dados e insights estratégicos, buscando transformar as análises em informações úteis para os stakeholders.

---

## Tecnologias e ferramentas

| Tecnologia | Utilização |
|---|---|
| Python | Linguagem de programação para análise de dados |
| Pandas | Manipulação e análise de dados tabulares |
| NumPy | Operações numéricas |
| Matplotlib | Construção de gráficos e visualizações |
| Seaborn | Visualizações estatísticas |
| Jupyter Notebook | Desenvolvimento e documentação das análises |
| Visual Studio Code | Ambiente de desenvolvimento |
| Git | Controle de versão |
| GitHub | Repositório compartilhado e colaboração |

---

## Estrutura do projeto

```text
Tech Challenge - Fase 1/
│
├── .venv/ 
│   └── Ambiente virtual Python local
│
├── data/
│   ├── olist_customers_dataset.csv
│   ├── olist_geolocation_dataset.csv
│   ├── olist_order_items_dataset.csv
│   ├── olist_order_payments_dataset.csv
│   ├── olist_order_reviews_dataset.csv
│   ├── olist_orders_dataset.csv
│   ├── olist_products_dataset.csv
│   ├── olist_sellers_dataset.csv
│   └── product_category_name_translation.csv
│
├── analise_ecommerce.ipynb
├── .gitignore
├── README.md
└── requirements.txt
```

---

## Configuração do ambiente

O projeto utiliza um ambiente virtual Python (`.venv`) para isolar as bibliotecas e dependências utilizadas na análise.

Essa abordagem permite que cada integrante do grupo configure seu próprio ambiente local, mantendo as mesmas versões das bibliotecas utilizadas no projeto.

### Pré-requisitos

- Python 3.10 ou compatível com as dependências do projeto;
- Visual Studio Code;
- Extensão Python;
- Extensão Jupyter;
- Git.

### Instalação

**1. Clone o repositório**

```bash
git clone URL_DO_REPOSITORIO
```

**2. Acesse a pasta do projeto**

```bash
cd "Tech Challenge - Fase 1"
```

**3. Crie o ambiente virtual**

```bash
python -m venv .venv
```

**4. Ative o ambiente virtual**

Windows PowerShell:

```powershell
.venv\Scripts\Activate.ps1
```

Linux/macOS:

```bash
source .venv/bin/activate
```

**5. Instale as dependências**

```bash
python -m pip install --upgrade pip
```

```bash
pip install -r requirements.txt
```

**6. Configure o kernel no VS Code**

Abra o arquivo `analise_ecommerce.ipynb`, clique em **Select Kernel** e selecione o ambiente Python localizado na pasta `.venv`.

Após a configuração, o notebook estará pronto para execução.

---

## Colaboração e versionamento

O desenvolvimento do projeto será realizado de forma colaborativa, utilizando Git e GitHub para compartilhamento de arquivos e controle de alterações.

Cada integrante deverá configurar seu próprio ambiente virtual local, utilizando as dependências definidas no arquivo `requirements.txt`.

Recomendações:

- Manter o repositório local atualizado;
- Utilizar o ambiente virtual `.venv` do projeto;
- Evitar versionar o ambiente virtual e arquivos temporários;
- Registrar as alterações com commits claros e objetivos;
- Atualizar o `requirements.txt` quando novas dependências forem adicionadas;
- Evitar sobrescrever alterações realizadas por outros integrantes sem revisar os commits.

---

## Resultados esperados

Ao final do projeto, espera-se:

- Compreender o desempenho do negócio a partir dos dados disponíveis;
- Identificar padrões, tendências e oportunidades;
- Explorar indicadores relevantes para o setor de e-commerce;
- Desenvolver análises orientadas a problemas de negócio;
- Construir visualizações que facilitem a interpretação dos dados;
- Apresentar insights e recomendações estratégicas;
- Elaborar um relatório executivo direcionado a investidores e acionistas.

---

## Fonte dos dados

**Brazilian E-Commerce Public Dataset by Olist**

Dataset público disponibilizado pela Olist para estudos e análises sobre o comércio eletrônico brasileiro.

Os resultados deverão considerar as características, o período de abrangência e as limitações dos dados utilizados.

---

## Autores

Projeto desenvolvido em grupo como parte do Tech Challenge da pós-graduação em Data Analytics.

Grupo - 7
Participantes:
- Arthur Lanzoni Macedo - RM 379016
- Ariane Neres de Melo - RM 379466
- Vinicius Nobrega Costa - RM 379720