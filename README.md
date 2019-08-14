# NSRP CHALLENGE

Docker compose responsável pela execução da solução de cadastro de campanha e sócio torcedor juntamente com as dependências necessárias.

#### Imagens utilizadas

* Mysql 8.0 - Serviço de campanha
* Mysql 8.0 - Serviço de sócio torcedor
* ActiveMQ
* nsrp-challenge-campanha
* nsrp-challenge-socio-torcedor

#### Execução da solução

A execução poderá ser feita através do comando `docker-compose up -d` no diretório onde se encontra o arquivo docker-compose.yaml

#### Acesso aos serviços
| Serviço | Porta |
|---|---|
| Mysql Serviço de campanha |3306|
| Mysql Serviço de sócio torcedor | 3307|
| ActiveMQ                      | 61616|
| nsrp-challenge-campanha       | 8080|
| nsrp-challenge-socio-torcedor | 8081|
