# Dashboard de Chamados — Suporte Técnico

Dashboard interativo desenvolvido com Streamlit para visualização de chamados de suporte técnico a partir de uma planilha Excel.

**Construído para:** substituir uma planilha estática por visualizações dinâmicas que facilitam a priorização do atendimento.

## Funcionalidades

- Upload direto de planilha Excel (.xlsx) pelo navegador
- Gráfico de barras horizontal por área (com cores customizadas por categoria)
- Gráfico de pizza com distribuição percentual
- Interface web local via Streamlit

## Tecnologias

- Python 3
- Streamlit (interface web)
- Pandas (manipulação de dados)
- Matplotlib (gráficos)
- openpyxl (leitura de Excel)

## Como rodar localmente

1. Clone o repositório
2. Instale as dependências:

```bash
pip install -r requirements.txt
```

3. Execute:

```bash
streamlit run copy_dashboard_chamados.py
```

4. Acesse no navegador: https://dashboard-chamados-ffbm3zkednyutkshdsibc3.streamlit.app/
5. Baixe a planilha_exemplo_chamados.xlsx para testar o dashboard

## Estrutura esperada da planilha

A planilha precisa ter ao menos uma coluna chamada `definicao_area` com as categorias dos chamados (ex: PROPOSTA, CLIENTES, DASHBOARD, etc.)

## Contexto

Desenvolvido para um colega de trabalho que organizava chamados de suporte em planilha. O dashboard transformou dados brutos em visualizações claras para priorizar atendimentos. O projeto não evoluiu pois o uso da planilha foi descontinuado.
