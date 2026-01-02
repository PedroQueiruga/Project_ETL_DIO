📊 Pipeline ETL: Curso Santander 2025
Este projeto demonstra um pipeline de ETL (Extract, Transform, Load) desenvolvido durante a Santander Dev Week. O objetivo original era consumir uma API de um banco fictício, transformar os dados usando Inteligência Artificial e carregar os dados de volta. Devido à indisponibilidade da API original, o projeto foi adaptado para utilizar arquivos locais, mantendo toda a lógica de processamento de dados.

🚀 O Projeto
O fluxo consiste em:

Extract (Extração): Leitura de dados de clientes a partir de um arquivo CSV (SDW2025.csv).

Transform (Transformação): Processamento dos dados para estruturar informações de conta e cartão, além da integração com a API da OpenAI para gerar mensagens de marketing personalizadas.

Load (Carga): Exportação dos dados processados para um arquivo JSON estruturado, simulando o fechamento do ciclo de dados.

🛠️ Tecnologias Utilizadas
Python 

Pandas: Para manipulação e análise de dados.

OpenAI API: Para a geração de conteúdo via Inteligência Artificial (Generative AI).

JSON/CSV: Como fontes e destinos de dados.

🤖 Integração com IA (OpenAI)
Para utilizar a funcionalidade de geração de mensagens personalizadas, é necessário possuir uma chave de API da OpenAI.
