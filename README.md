# Prometheus e Grafana
Esse é um tutorial como deixar a sua aplicação sendo observabilizada com o Prometheus e adicionando os gráficos no Grafana.

## Requisitos:
- Docker Desktop
- MVN 
- Java

## Como subir aplicação Prometheus e Grafana
- Faça o clone deste repositório
- Acesse a pasta
- Execute o docker
- Com o projeto aberto, vá até a pasta app e execute `mvn clean package e verifique se o build foi executado com sucesso
- Volte a pasta anterior e execute `docker-compose up -d` aguarde um pouco e verifique acessando a url se aplicação está funcionando.
- 