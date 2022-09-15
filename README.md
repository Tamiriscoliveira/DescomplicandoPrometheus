# Curso Descomplicando Prometheus 

Minha evolução no sistema de monitoramento prometheus sendo realizado com a 
monitoria do Jeferson Fernando da Linuxtips.

## Porque devemos Monitorar?

Devemos monitorar para saber o que acontece na infraestrutura, na aplicação, no serviço em tempo real. Para caso ocorra alguma falha ou anomalia
as pessoas responsáveis, sejam notificadas com o máximo de informação para avaliar e fazer o troubleshooting para resolução adequada.


## Introdução

Prometheus é um sistema de captura e armazenamento de métricas, com a facilidade da integração com outros sistemas.
Ele foi inspirado no sistema de monitoramento do cluster kubernetes da google o BORG.

Ele surgiu em 2012 e foi escrito na linguagem GO, pelos engenheiros da SoundCloud.

Uma dos principais ponto do prometheus é que ele vai até o alvo para coletar as métricas,e depois ele guarda no banco de dados timeseries. 
Mas também é possivel que ele receba essas informações atráves do PUSH GATEWAY.

Banco de Dados Temporais

Um banco de dados de séries temporais(Time series database) é um sistema usado para armazenar séries temporais através de 
pares de tempo e valor associados.  Em alguns campos, as séries temporais podem ser chamadas de perfis, curvas, traços ou ainda, tendências. 

## Prometheus Monitoring Architecture

![Prometheus](https://user-images.githubusercontent.com/13388615/190471394-c5fbb82a-bcc8-486f-a2e9-9c72993874d9.png)



