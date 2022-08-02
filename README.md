# Obervabilidade no Spring Boot utilizando o Actuator, Prometheus e Grafana

Poc que usa o Spring Boot Actuator para expor métricas que serão consumidas e armazenadas pelo Prometheus e posteriormente exibidas pelo Grafana.

## Leitura complementar

- https://medium.com/@valdenirsantana/obervabilidade-no-spring-boot-utilizando-o-actuator-prometheus-e-grafana-156eca15cf80

## Instalação e execução

### Pré requisitos

- Para rodar este projeto você precisa:
  - Docker
  - Java 17
  - Maven 


### Execução

1. Execute o comando `docker-compose up` na pasta raiz do projeto para subir o prometheus e o grafana
2. Execute a aplicação java através da sua ide, ou do comando `mvn spring-boot:run`
