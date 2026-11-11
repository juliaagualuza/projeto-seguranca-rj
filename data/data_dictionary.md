# Dicionário de Dados

## Projeto
Análise Temporal e Espacial da Criminalidade no Estado do Rio de Janeiro (2014–2026).

## Fonte
Instituto de Segurança Pública do Estado do Rio de Janeiro (ISP-RJ).

## Estrutura da base

A base apresenta registros mensais de indicadores de criminalidade por município e região do Estado do Rio de Janeiro.

| Variável | Descrição |
|---|---|
| `fmun_cod` | Código do município |
| `fmun` | Nome do município |
| `ano` | Ano de referência |
| `mes` | Mês de referência |
| `mes_ano` | Identificação do mês e ano |
| `regiao` | Região do Estado |
| `registro_ocorrencias` | Total de registros de ocorrências |
| `fase` | Fase de consolidação dos dados |

## Indicadores criminais

As demais colunas representam indicadores de ocorrências e atividades policiais, incluindo:

- **Homicídios e violência:** `hom_doloso`, `hom_culposo`, `letalidade_violenta`, `cvli`, `feminicidio`, `tentat_hom`.
- **Lesões e crimes sexuais:** `lesao_corp_morte`, `lesao_corp_dolosa`, `lesao_corp_culposa`, `estupro`.
- **Roubos:** `roubo_rua`, `roubo_veiculo`, `roubo_carga`, `roubo_comercio`, `roubo_residencia`, `total_roubos` e demais variáveis iniciadas por `roubo_`.
- **Furtos:** `furto_veiculos`, `furto_transeunte`, `furto_celular`, `total_furtos` e demais variáveis iniciadas por `furto_`.
- **Outros indicadores:** sequestro, extorsão, estelionato, apreensão de drogas, tráfico de drogas, recuperação de veículos, ameaças e pessoas desaparecidas.
- **Atividades policiais:** `apf`, `aaapai`, `cmp` e `cmba`.
- **Outros registros:** encontro de cadáver, encontro de ossada e policiais mortos em serviço.

## Observação

Os indicadores são apresentados conforme a nomenclatura original disponibilizada pelo ISP-RJ. Para interpretações detalhadas, devem ser consultadas as definições oficiais de cada indicador.

## Formato dos dados

- Unidade de observação: município por mês.
- Período analisado: 2014 a 2026.
- Municípios: 92.
- Registros: 14.076 linhas e 62 colunas.
- Formato original: Excel (.xlsx).
