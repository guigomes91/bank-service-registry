# Service registry dos microserviços Gomes Bank

## Utiliza o Spring Boot e Spring Cloud Netflix Eureka.

Acesso a interface: http://localhost:8761/

Serviços descobertos
![image](https://github.com/guigomes91/bank-service-registry/assets/44264050/83e67559-a5a1-413a-8fcb-e1a9af962263)

Obter informações sobre todos os serviços registrados:

Endpoint: /eureka/apps
Método: GET
Descrição: Retorna informações sobre todos os aplicativos (serviços) registrados no servidor Eureka, incluindo instâncias de cada aplicativo.
Obter informações sobre um serviço específico:

Endpoint: /eureka/apps/{serviceName}
Método: GET
Descrição: Retorna informações sobre um aplicativo (serviço) específico, incluindo todas as instâncias registradas desse serviço.
Obter informações sobre instâncias de um serviço específico:

Endpoint: /eureka/apps/{serviceName}/{instanceId}
Método: GET
Descrição: Retorna informações detalhadas sobre uma instância específica de um serviço registrado no servidor Eureka.
Obter informações sobre o status do servidor Eureka:

Endpoint: /eureka/status
Método: GET
Descrição: Retorna informações sobre o status do servidor Eureka, incluindo estatísticas de registro, atualizações recentes e outros detalhes relevantes.
