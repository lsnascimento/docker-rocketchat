# Rocketchat

1. Para a utilização do Rocketchat é necessário a instalação do docker e o docker compose, caso já possua esses softwares instalados, favor desconsidere.
2. Baixe o arquivo `docker-compose.yml` ou copie o seu conteúdo.
3. Após isso, execute o comando `docker-compose up --build -d`
4. Caso ocorra alguma mensagem de erro do Rocketchat ao tentar procurar o MongoDB, execute cada service individualmente.
   1. Exemplo: `docker-compose up -d mongo` e assim por diante.