# Marktech - Atendimento ao cliente
Case buscando explorar as habilidades de análise de dados focado na dinâmica de uma central de atendimento.

## Contexto
O Sexto Andar está reinventando o processo de compra e venda de imóveis usando tecnologia e dados para transformar processos burocráticos em experiências simples e agradáveis. Eles usam o modelo iBuyer para comprar, renovar e vender imóveis. Em 2020, planejam expandir para várias cidades no Brasil, adaptando a equipe de atendimento ao cliente para cada nova cidade. O grande desafio é como expandir e fornecer bom suporte ao cliente sem aumentar significativamente os custos. Este estudo de caso fornecerá um exemplo dos desafios enfrentados em suas operações diárias.

### Desafio

- Quais insights você pode tirar dos dados do conjunto de dados? (4 semanas em fevereiro)
- Como você vê a saúde operacional da nossa equipe de atendimento ao cliente?
- Levando em consideração os curtos e longos prazos, quais ações você pode tomar para melhorar a eficiência, produtividade e qualidade da
nossa equipe de atendimento ao cliente com base nos conjuntos de dados fornecidos?
- Que tipo de dados você gostaria de ter acesso para criar mais insights?
- Quais partes interessadas internas e externas você envolveria no processo e por quê? Como você se aproximaria delas?
- Como você definiria o sucesso do seu plano de ação? Aqui gostaríamos de saber sobre KPIs e métricas.
- Como você garantiria que estamos escalando e fornecendo bom suporte ao mesmo tempo sem aumentar significativamente nossos custos?

## Ferramentas Utilizadas

- Excel
- Power BI
- Power Point
  - Think-cell [lincense 60 trial](https://www.think-cell.com/en/product/firmlearning?utm_campaign=firmlearning-22-1483-1&utm_source=firmlearning&utm_medium=youtube&utm_content=&utm_id=firmlearning-22-1483)

## Dados Analisados

Os dados recebidos para esse estudo e as intruções se encontram na pasta [in](/in/), caso você tennha interesse em realizar esse estudo. Os arquivos com os meus resultados se encontram na pasta raiz, para a consulta.

### PowerBI
![ETL](bau/Operacao_ajuste.PNG)
Na base de dados sobre os chamados do canal escrito (databse_writting), realizamos operações de substituições e ajustes no campo tags, buscando extrair o máximo de informação do tagueamento do chamado. O Powerbi não foi tulizado para geração de dashboards, alguns visuais foram utilziados de forma exploratória.

## Resultados

![Painel de Campanha](bau/6Door_CE_video.gif)

- Suporte escrito: precisamos entender melhor as solicitações via api e
traçarmos planos de melhoria ao suporte via email
- Suporte chamada: precisamos focar na possiblidade de ajuste de 37% das
chamadas realizadas e aprofundamento no tempo médio de chamada
- Em média, o canal de voz tem 4x mais demanda que o escrito. Podemos
analisar se o time atual atende a quantidade de demanda por canal

Material de consulta [Apresentação Executiva Final](out/Case_6doors.pdf).
