# Turorial-Microservices

1. Conceitos Fundamentais de Microservices
   - O que são microservices e como se diferenciam da arquitetura monolítica.
     Microservices (ou microserviços) são uma abordagem arquitetural para o desenvolvimento de software em que um sistema é dividido em pequenos serviços independentes. Cada microserviço é responsável por uma funcionalidade específica do sistema e pode ser desenvolvido, implantado e escalado de forma independente.
     
   - Benefícios e desafios dessa abordagem. ,
   - Princípios de design:
     * Independência dos serviços.
     * Comunicação assíncrona ou síncrona.
     * Autonomia e independência de dados.
   - Domain-Driven Design (DDD)
     * Domain-Driven Design (DDD)
     * Domain-Driven Design (DDD)
       
2. Linguagem e Fundamentos do Java
   - Revisão de conceitos básicos de Java.
   - Trabalhar com APIs REST usando JAX-RS ou Spring MVC.
   - Manipulação de JSON usando bibliotecas como Jackson ou Gson.

3. Frameworks Populares para Microservices
   - Spring Boot:
     * Criação de APIs RESTful.
     * Configuração de propriedades e profiles.
   - Spring Cloud:
     * Componentes como Eureka (Service Discovery), Zuul/Gateway, Config Server.
     * Circuit Breaker (Hystrix/Resilience4j).
   - Micronaut:
     * Framework alternativo, leve e otimizado para microservices.
    
4. Comunicação entre Microservices
   - Protocolos e formatos de comunicação:
     * REST (HTTP/HTTPS).
     * JSON e XML.
   - JSON e XML.
     * GRPC.
     * Apache Kafka (mensageria).
     * RabbitMQ ou ActiveMQ.
    
5. Gestão de Configuração
   - Configuração centralizada com Spring Cloud Config.
   - Gerenciamento de secrets e variáveis de ambiente (como usar Vault ou AWS Secrets Manager).

6. Banco de Dados e Persistência
   - Banco de Dados e Persistência:
     * Cada microservice gerencia seu próprio banco de dados.
   - Trabalhar com JPA/Hibernate ou Spring Data.
   - Alternativas como NoSQL (MongoDB, Cassandra).

7. Monitoramento e Resiliência
   - Monitoramento e Logging:
     * Uso de ferramentas como ELK Stack (Elasticsearch, Logstash, Kibana).
     * Distributed Tracing com Zipkin ou Jaeger.
   - Tolerância a falhas:
     * Implementação de Circuit Breaker (Resilience4j).
     * Retry e Timeout policies.

8. Contêineres e Orquestração
   - Docker:
     * Criação de contêineres para microservices.
     * Docker Compose para ambientes multi-contêiner.
   - Kubernetes:
     * Deploy e gerenciamento de microservices.
     * Conceitos como pods, services, ingress.
    
9. Testes de Microservices
    - Testes unitários e de integração com JUnit e MockMVC.
    - Testes de contrato com Spring Cloud Contract.
    - Testes end-to-end para verificar a integração entre serviços.
  
10. Segurança em Microservices
    - Autenticação e autorização com OAuth2 e JWT.
    - Integração com Spring Security.
    - Práticas de segurança para proteger APIs.
   
11. Versionamento e CI/CD
    - Versionamento de APIs (URI ou cabeçalhos).
    - Configuração de pipelines de CI/CD com Jenkins, GitHub Actions ou GitLab CI.


