# Dashboard de Eficiência Operacional e Manutenção (Power BI)

Criei este projeto no Power BI Desktop para acompanhar a operação de manutenção corretiva e preventiva, olhando desde o volume de ordens de serviço até onde estão os maiores gargalos de tempo e custo.

## O que tem no painel

O relatório está dividido em duas páginas principais:

- **Visão Geral:** traz o panorama da operação com o total de ordens de serviço (1.800 OS), divisão entre corretiva (37,06%) e preventiva (62,94%), custo total, MTTR médio (4,9 h) e aderência geral ao SLA (79,5%), além da evolução por sistema e ao longo dos meses.
- **Gargalos e SLA:** foca em identificar onde a operação perde tempo ou gasta mais, comparando o MTTR e o percentual de SLA por sistema de ativo (Civil/Predial, Refrigeração, HVAC, Hidráulica e Elétrica) e o custo total por unidade cliente.

## Filtros disponíveis

Nas duas abas dá para cruzar os dados por:
- Período (`Date`)
- Segmento do cliente (`segmento_cliente`)
- Unidade do cliente (`unidade_cliente`)

## Telas do projeto
![Visão Geral](Vis%C3%A3o%20Geral.png)

![Gargalos e SLA](Gargalos%20e%20SLA.png)

## Arquivo

O arquivo `.pbix` completo está aqui no repositório para quem quiser abrir no Power BI Desktop e testar os filtros e medidas DAX.
