# Urban Data Analysis

## Descricao

Projeto de analise de dados urbanos, mobilidade e planejamento territorial usando dados publicos e indicadores sinteticos.

## Problema que Resolve

Cidades produzem muitos dados sobre territorio, populacao, infraestrutura e mobilidade, mas esses dados nem sempre sao transformados em informacao acessivel para planejamento, participacao social e formulacao de politicas publicas.

## Para Quem Gera Valor

- Gestores publicos
- Conselhos municipais e instancias participativas
- Organizacoes de impacto social
- Institutos de inovacao urbana
- Pesquisadores e analistas de dados

## Solucao Proposta

Criar uma estrutura de analise com indicadores de mobilidade, acesso a equipamentos publicos, densidade, vulnerabilidade e deslocamento. O projeto pode evoluir para dashboards, mapas e estudos territoriais.

## Tecnologias e Metodos

- Python
- Pandas
- GeoPandas
- SQL
- GIS
- Power BI
- Indicadores territoriais
- Analise exploratoria de dados

## Estrutura do Projeto

```text
data/       indicadores sinteticos por bairro ou regiao
notebooks/  analise exploratoria e visualizacoes iniciais
docs/       metodologia e fontes de dados possiveis
maps/       camadas geograficas futuras
```

## Como Executar

```sh
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook notebooks/urban-data-demo.ipynb
```

## Resultados e Aprendizados

- Leitura comparativa de indicadores urbanos
- Base para mapas e dashboards territoriais
- Identificacao de regioes prioritarias
- Apoio a politicas publicas e projetos de impacto urbano

## Resultado Demonstrativo

Com os dados sinteticos em `data/indicadores_urbanos_exemplo.csv`, o notebook calcula um score de atencao territorial.

| Bairro | Prioridade | Score de atencao |
| --- | --- | ---: |
| Rio Verde | muito alta | 100,10 |
| Nova Esperanca | alta | 87,20 |
| Vila Industrial | alta | 59,00 |
| Parque Norte | media | 34,60 |
| Centro | media | 17,40 |

## Autor

Rodrigo Willemann  
Email: rodrigo.willemann@gmail.com

