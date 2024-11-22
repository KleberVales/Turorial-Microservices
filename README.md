# Turorial-Microservices

1. Conceitos Fundamentais de Microservices
   - O que são microservices e como se diferenciam da arquitetura monolítica.
     
     Microservices (ou microserviços) são uma abordagem arquitetural para o desenvolvimento de software em que um sistema é dividido em pequenos serviços independentes. Cada microserviço é responsável por uma funcionalidade específica do sistema e pode ser desenvolvido, implantado e escalado de forma independente.

     Por outro lado, a arquitetura monolítica é um modelo em que todas as funcionalidades de um sistema estão integradas em um único código ou aplicação. Isso significa que o sistema é implantado como uma unidade única.

   - Vantagens dos microservices:
     * Flexibilidade no desenvolvimento: As equipes podem trabalhar em paralelo em serviços diferentes.
     * Escalabilidade otimizada: Apenas os serviços mais utilizados precisam ser escalados.
     * Maior resiliência: Problemas em um serviço não comprometem o sistema inteiro.
     * Facilidade de adoção de novas tecnologias: Cada serviço pode ser construído com diferentes ferramentas.
    
   - Desvantagens dos microservices:
     * Maior complexidade: Requer sistemas avançados de comunicação, orquestração e monitoramento.
     * Custo operacional: Pode gerar mais custos em infraestrutura, já que cada microserviço pode ter seus próprios requisitos.
     * Gerenciamento de dados: Manter consistência entre os serviços pode ser desafiador.

   - Princípios de design:
     * Independência dos serviços.\
       A independência dos serviços é uma das características fundamentais dos microservices. Ela significa que cada microserviço é projetado para ser autônomo e desacoplado dos outros serviços no sistema.
  
       Essa independência é garantida por uma série de práticas e princípios arquiteturais: Independência no desenvolvimento, Independência na implantação, Independência na comunicação, Independência no armazenamento de dados, Independência em falhas.
  
       
     * Comunicação assíncrona ou síncrona.\
       A comunicação entre microservices pode ser síncrona ou assíncrona, e a escolha entre elas depende das necessidades do sistema, do tipo de interação e dos requisitos de desempenho e resiliência.
  
       Na comunicação síncrona, um microserviço faz uma chamada direta a outro e espera pela resposta antes de continuar. Essa abordagem é frequentemente implementada com protocolos baseados em requisição e resposta, como: HTTP/REST e gRPC.
  
       Na comunicação assíncrona, o microserviço chamador envia uma mensagem ou evento para o serviço chamado e não espera pela resposta imediatamente. A interação ocorre em segundo plano, utilizando sistemas de mensageria como: RabbitMQ, Apache Kafka e AWS SQS.
       
     * Autonomia e independência de dados.\
       A autonomia e independência de dados são princípios fundamentais na arquitetura de microservices. Elas garantem que cada serviço seja responsável por gerenciar seus próprios dados, sem depender diretamente de outros serviços. Isso ajuda a manter o sistema desacoplado e escalável.
       
   - Domain-Driven Design (DDD)\
     Domain-Driven Design (DDD), ou Design Orientado ao Domínio, é uma abordagem de desenvolvimento de software que foca em alinhar o design e a estrutura do sistema ao domínio de negócios que ele representa. Introduzido por Eric Evans no livro Domain-Driven Design: Tackling Complexity in the Heart of Software, o DDD oferece um conjunto de princípios e práticas para lidar com a complexidade em projetos de software grandes e complexos.
       
1. Linguagem e Fundamentos do Java
   - Revisão de conceitos básicos de Java.
   - Trabalhar com APIs REST usando JAX-RS ou Spring MVC.
   - Manipulação de JSON usando bibliotecas como Jackson ou Gson.

2. Frameworks Populares para Microservices
   - Spring Boot:
     * Criação de APIs RESTful.
     * Configuração de propriedades e profiles.
   - Spring Cloud:
     * Componentes como Eureka (Service Discovery), Zuul/Gateway, Config Server.
     * Circuit Breaker (Hystrix/Resilience4j).
   - Micronaut:
     * Framework alternativo, leve e otimizado para microservices.
    
3. Comunicação entre Microservices
   - Protocolos e formatos de comunicação:
     * REST (HTTP/HTTPS).
     * JSON e XML.
   - JSON e XML.
     * GRPC.
     * Apache Kafka (mensageria).
     * RabbitMQ ou ActiveMQ.
    
4. Gestão de Configuração
   - Configuração centralizada com Spring Cloud Config.
   - Gerenciamento de secrets e variáveis de ambiente (como usar Vault ou AWS Secrets Manager).

5. Banco de Dados e Persistência
   - Banco de Dados e Persistência:
     * Cada microservice gerencia seu próprio banco de dados.
   - Trabalhar com JPA/Hibernate ou Spring Data.
   - Alternativas como NoSQL (MongoDB, Cassandra).

6. Monitoramento e Resiliência
   - Monitoramento e Logging:
     * Uso de ferramentas como ELK Stack (Elasticsearch, Logstash, Kibana).
     * Distributed Tracing com Zipkin ou Jaeger.
   - Tolerância a falhas:
     * Implementação de Circuit Breaker (Resilience4j).
     * Retry e Timeout policies.

7. Contêineres e Orquestração
   - Docker:
     * Criação de contêineres para microservices.
     * Docker Compose para ambientes multi-contêiner.
   - Kubernetes:
     * Deploy e gerenciamento de microservices.
     * Conceitos como pods, services, ingress.
    
8. Testes de Microservices
    - Testes unitários e de integração com JUnit e MockMVC.
    - Testes de contrato com Spring Cloud Contract.
    - Testes end-to-end para verificar a integração entre serviços.
  
9. Segurança em Microservices
    - Autenticação e autorização com OAuth2 e JWT.
    - Integração com Spring Security.
    - Práticas de segurança para proteger APIs.
   
10. Versionamento e CI/CD
    - Versionamento de APIs (URI ou cabeçalhos).
    - Configuração de pipelines de CI/CD com Jenkins, GitHub Actions ou GitLab CI.


