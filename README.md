# Análise dos números de Lionel Messi

Este repositório contém um projeto de análise dos números de Lionel Messi durante sua carreira no Barcelona, PSG, Inter Miami e na seleção argentina, entre 2004 e 2024. O objetivo deste projeto é explorar o desempenho de Messi ao longo dos anos, identificando padrões, tendências e insights através de visualizações no Power BI. Aproveito também para adaptar as documentações a notebooks também para poder praticar um pouco da linguagem Python.

## Versão mais atualizada do dashboard

https://app.powerbi.com/view?r=eyJrIjoiNDdmOTkzOWUtYzhlMS00MDQ3LWE3MzMtODU2MTk0Y2FlMzcxIiwidCI6ImU4Y2YyNjM5LTFmOTgtNGJiNC1iZDg5LWFiZDE0OTI4OTM3ZiJ9

## Objetivo do projeto

- Analisar o desempenho de Messi em diferentes clubes e na seleção.
- Visualizar a distribuição dos gols por temporada, competição, adversário e local.
- Explorar a evolução dos gols ao longo do tempo e como eles se comparam em diferentes contextos (clubes vs. seleção).
- Aprender e praticar habilidades no Power BI, incluindo criação de dashboards, uso de DAX e análise de dados.
- Também mostrar poder de síntese e adaptação de insights para a linguagem Python

## Estrutura do projeto

- /datamessi/: Conjunto de dados contendo informações detalhadas sobre os gols de Messi, incluindo data, adversário, competição, e clube/seleção.
- /reports/: Relatórios em formato .pbix, que podem ser abertos e explorados no Power BI Desktop.
- /images/: Imagens e capturas de tela dos dashboards e visualizações criadas.
- README.md: Este arquivo que você está lendo agora.

## Dados Utilizados

Os dados para este projeto foram coletados do Kaggle, através da página https://www.kaggle.com/datasets/azminetoushikwasi/-lionel-messi-all-club-goals, contendo:

- Gols por temporada e competição
- Informações sobre adversários e localizações dos jogos
- Jogador que deu a assistência, minuto que saiu o gol e resultado do jogo

Só que nesse dataset havia apenas os gols por clubes (FC Barcelona e Paris Saint-Germain), então inseri também os gols de Lionel Messi pela seleção argentina principal e pelo Inter Miami até outubro de 2024.

Para complementar, dados foram buscados tambem no FBRef.com.

## Relatórios e Dashboards Criados

- Evolução dos Gols ao Longo do Tempo: Gráfico que mostra a progressão dos gols de Messi em cada temporada.
- Análise por Clube e Seleção: Comparação dos gols marcados pelo Barcelona, PSG e pela seleção argentina.
- Distribuição por Competição: Visualização que analisa em quais competições Messi teve o melhor desempenho.

## Ferramentas e Tecnologias

- **Power BI Desktop:** Ferramenta principal para análise e criação de relatórios.
- **Excel/CSV:** Para armazenar e organizar os dados antes de importá-los para o Power BI.
- **Jupyter Notebook:** Para a adaptação dos insights ao Python

## Contribuições

Este é um projeto de aprendizado, mas sugestões e melhorias são bem-vindas! Sinta-se à vontade para contribuir através de issues ou pull requests.
