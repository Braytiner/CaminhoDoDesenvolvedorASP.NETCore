# Roteiro do Desenvolvedor ASP.NET Core

> Roteiro para se tornar um desenvolvedor ASP.NET Core em 2021:

    Abaixo, você pode encontrar um gráfico que demonstra os caminhos que     você pode seguir e as bibliotecas que gostaria de aprender para se     tornar um desenvolvedor ASP.NET Core. Fiz este gráfico como uma dica     para todos que me perguntam: "O que devo aprender a seguir como     desenvolvedor ASP.NET Core?"
    Isenção de responsabilidade

    O objetivo deste roteiro é dar uma ideia sobre a paisagem. O roteiro irá guiá-lo se você estiver confuso sobre o que aprender a seguir, em vez de encorajá-lo a escolher o que está na moda e na moda. Você deve compreender melhor por que uma ferramenta seria mais adequada para alguns casos do que a outra e lembre-se de que moderno e moderno nem sempre significa mais adequado para o trabalho

Dê uma estrela! Estrela

Se você gosta ou está usando este projeto para aprender ou iniciar sua solução, dê uma estrela a ele. Obrigado!

![aspnetcore-developer-roadmap-printable](https://user-images.githubusercontent.com/52793184/119379099-6d9bad00-bc95-11eb-85d8-e73394c08dd9.png)


Resources

1. Conheça os pré-requisitos
    - [C#](https://www.pluralsight.com/paths/csharp)
    - [.NET 5](https://devblogs.microsoft.com/dotnet/introducing-net-5)
    - [Entity Framework](https://www.pluralsight.com/search?q=entity%20framework%20core)
    - [Dapper](https://github.com/StackExchange/Dapper)
    - [NHibernate](https://github.com/nhibernate/nhibernate-core)
    - [ASP.NET Core](https://www.pluralsight.com/search?q=asp.net%20core)
    - [SQL Fundamentals](https://www.datacamp.com/tracks/sql-fundamentals)

2. Habilidades de desenvolvimento geral
    
    - Learn GIT, create a few repositories on GitHub, share your code with other people
    - Know HTTP(S) protocol, request methods (GET, POST, PUT, PATCH, DELETE, OPTIONS)
    - Don't be afraid of using Google, Power Searching with Google
    - Learn dotnet CLI
    - Read a few books about algorithms and data structures

3. ASP.NET Core Básico
    - [MVC](https://docs.microsoft.com/en-us/aspnet/core/mvc/overview?view=aspnetcore-5.0)
    - [REST](https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-web-api?view=aspnetcore-5.0&tabs=visual-studio)
    - [Razor Pages](https://docs.microsoft.com/en-us/aspnet/core/razor-pages/?view=aspnetcore-5.0&tabs=visual-studio)
    - [Razor Components](https://docs.microsoft.com/en-us/aspnet/core/blazor/components/?view=aspnetcore-5.0)
    - [Middlewares](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/middleware/?view=aspnetcore-5.0)
    - [Filters & Attributes](https://docs.microsoft.com/en-us/aspnet/core/mvc/controllers/filters?view=aspnetcore-5.0)
    - [Application Settings & Configurations](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/configuration/?view=aspnetcore-5.0)
    - [Authentication](https://docs.microsoft.com/en-us/aspnet/core/security/authentication/?view=aspnetcore-5.0)
    - [Authorization](https://docs.microsoft.com/en-us/aspnet/core/security/authorization/introduction?view=aspnetcore-5.0)

4. SOLID

    - [Single Responsibility Principle (SRP)](https://www.dotnetcurry.com/software-gardening/1148/solid-single-responsibility-principle)
    - [Open-Closed Principle (OCP)](https://www.dotnetcurry.com/software-gardening/1176/solid-open-closed-principle)
    - [Liskov Substitution Principle (LSP)](https://www.dotnetcurry.com/software-gardening/1235/liskov-substitution-principle-lsp-solid-patterns)
    - [Interface Segregation Principle (ISP)](https://www.dotnetcurry.com/software-gardening/1257/interface-segregation-principle-isp-solid-principle)
    - [Dependency Inversion Principle (DIP)](https://www.dotnetcurry.com/software-gardening/1284/dependency-injection-solid-principles)

5. Injeção de Dependência
    1. DI Containers
      - [Microsoft.Extensions.DependencyInjection](https://docs.microsoft.com/aspnet/core/fundamentals/dependency-injection)
      - [AutoFac](https://autofaccn.readthedocs.io/en/latest/integration/aspnetcore.html)
      - [Ninject](http://www.ninject.org)
      - [Castle Windsor](https://github.com/castleproject/Windsor)
	  - [Simple Injector](https://github.com/simpleinjector/SimpleInjector)
   2. [Life Cycles](https://docs.microsoft.com/aspnet/core/fundamentals/dependency-injection#service-lifetimes)
   3. [Scrutor](https://github.com/khellang/Scrutor)

6. Bancos de dados
     1. Relational
      1. [SQL Server](https://www.microsoft.com/sql-server/sql-server-2019)
      2. [PostgreSQL](https://www.postgresql.org)
      3. [MariaDB](https://mariadb.org)
      4. [MySQL](https://www.mysql.com)
   2. Cloud Databases
      - [CosmosDB](https://docs.microsoft.com/azure/cosmos-db)
      - [DynamoDB](https://aws.amazon.com/dynamodb)
   3. Motores de busca
      - [ElasticSearch](https://www.elastic.co)
      - [Solr](http://lucene.apache.org/solr)
      - [Sphinx](http://sphinxsearch.com)
   4. NoSQL
      - [Redis](https://redis.io)
      - [MongoDB](https://docs.microsoft.com/aspnet/core/tutorials/first-mongo-app)
      - [Apache Cassandra](http://cassandra.apache.org)
      - [LiteDB](https://github.com/mbdavid/LiteDB)
      - [RavenDB](https://github.com/ravendb/ravendb)
      - [CouchDB](http://couchdb.apache.org)

7. Cache
    1. [Memory Cache](https://docs.microsoft.com/aspnet/core/performance/caching/memory)
   2. [Distributed Cache](https://docs.microsoft.com/aspnet/core/performance/caching/distributed)
      1. [Redis](https://redis.io/)
         1. [StackExchange.Redis](https://stackexchange.github.io/StackExchange.Redis)
         2. [EasyCaching](https://github.com/dotnetcore/EasyCaching)
      2. [Memcached](https://memcached.org)
   3. Entity Framework Cache de 2º Nível
      1. [EFCoreSecondLevelCacheInterceptor](https://github.com/VahidN/EFCoreSecondLevelCacheInterceptor)
      2. [EntityFrameworkCore.Cacheable](https://github.com/SteffenMangold/EntityFrameworkCore.Cacheable)

8. Logging
    1. Log Frameworks
      - [Serilog](https://github.com/serilog/serilog)
      - [NLog](https://github.com/NLog/NLog)
   2. Log Management System
      - [ELK Stack](https://www.elastic.co/what-is/elk-stack)
      - [Sentry.io](http://sentry.io)
      - [Loggly.com](https://loggly.com)
      - [Elmah.io](http://elmah.io)

9. API Clientes e Comunicações
    1. REST
       - [OData](https://devblogs.microsoft.com/odata/experimenting-with-odata-in-asp-net-core-3-1)
       - [Sieve](https://github.com/Biarity/Sieve)
    2. [gRPC](https://docs.microsoft.com/en-us/aspnet/core/grpc)
    3. GraphQL
       - [HotChocolate](https://github.com/ChilliCream/hotchocolate)
       - [GraphQL-dotnet](https://github.com/graphql-dotnet/graphql-dotnet)

10. Comunicação em Tempo Real
    - [SignalR](https://docs.microsoft.com/aspnet/core/signalr)
    - [WebSockets](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/websockets)

11. Mapeamento de Objetos
    - [AutoMapper](https://github.com/AutoMapper/AutoMapper)
    - [Mapster](https://github.com/MapsterMapper/Mapster)
    - [ExpressMapper](http://expressmapper.org/)
    - [AgileMapper](https://github.com/agileobjects/AgileMapper)

12. Agendamento de Tarefas
    - [Coravel](https://github.com/jamesmh/coravel)
    - [HangFire](https://github.com/HangfireIO/Hangfire)
    - [Background Service](https://docs.microsoft.com/en-us/aspnet/core/fundamentals/host/hosted-services)
    - [Fluent Scheduler](https://github.com/fluentscheduler/FluentScheduler)

13. Testando
    1. Unit Testing
       1. Frameworks
          - [xUnit](https://docs.microsoft.com/dotnet/core/testing/unit-testing-with-dotnet-test)
          - [NUnit](https://docs.microsoft.com/dotnet/core/testing/unit-testing-with-nunit)
          - [MSTest](https://docs.microsoft.com/dotnet/core/testing/unit-testing-with-mstest)
       2. Mocking
          - [Moq](https://github.com/moq/moq4)
          - [NSubstitute](https://github.com/nsubstitute/NSubstitute)
          - [FakeItEasy](https://github.com/FakeItEasy/FakeItEasy)
       3. Assertion
          - [FluentAssertion](https://github.com/fluentassertions/fluentassertions)
          - [Shouldly](https://github.com/shouldly/shouldly)
    2. Integration Testing
       - [WebApplicationFactory](https://docs.microsoft.com/aspnet/core/test/integration-tests)
       - [TestServer](https://koukia.ca/integration-testing-in-asp-net-core-2-0-51d14ede3968)
    3. Behavior Testing
       - [SpecFlow](https://github.com/techtalk/SpecFlow/tree/DotNetCore)
       - [BDDfy](https://github.com/TestStack/TestStack.BDDfy)
       - [LightBDD](https://github.com/LightBDD/LightBDD)
    4. E2E Testing
       - [Selenium](https://www.hanselman.com/blog/real-browser-integration-testing-with-selenium-standalone-chrome-and-aspnet-core-21)
       - [Puppeteer-Sharp](https://github.com/kblok/puppeteer-sharp)

14. Micro-Serviços
    1. Message-Broker
       - [RabbitMQ](https://www.rabbitmq.com/tutorials/tutorial-one-dotnet.html)
       - [Apache Kafka](https://github.com/confluentinc/confluent-kafka-dotnet)
       - [ActiveMQ](https://github.com/apache/activemq)
       - [Azure Service Bus](https://docs.microsoft.com/azure/service-bus-messaging/service-bus-messaging-overview)
       - [NetMQ](https://github.com/zeromq/netmq)
    2. Message-Bus
       - [MassTransit](https://github.com/MassTransit/MassTransit)
       - [NServiceBus](https://github.com/Particular/NServiceBus)
       - [EasyNetQ](https://github.com/EasyNetQ/EasyNetQ)
       - [CAP](https://github.com/dotnetcore/CAP)
    3. API Gateway
       - [Ocelot](https://github.com/ThreeMammals/Ocelot)
    4. Containerization
       - [Docker](https://www.docker.com)
    5. Orcherstration
       - [Kubernetes](https://kubernetes.io)
       - [Docker Swarm](https://docs.docker.com/engine/swarm)
    6. Reverse Proxy
       - [YARP](https://github.com/microsoft/reverse-proxy)
    7. Other
       - [Orleans](https://github.com/dotnet/orleans)
       - [Steeltoe](https://steeltoe.io)
       - [Dapr](https://github.com/dapr/dapr)
       - [Tye](https://github.com/dotnet/tye)

15. Integração e Entrega Contínua
    - [Gihub Actions](https://github.com/features/actions)
    - [Azure Pipelines](https://azure.microsoft.com/en-us/services/devops/pipelines)
    - [Travis CI](https://travis-ci.org/)
    - [Jenkins](https://www.jenkins.io/)
    - [Circle CI](https://circleci.com/)
    - [TeamCity](https://www.jetbrains.com/teamcity)

16. Design-Patterns
    - [CQRS](https://docs.microsoft.com/azure/architecture/patterns/cqrs)
    - [Decorator](https://www.dofactory.com/net/decorator-design-pattern)
    - [Strategy](https://www.dofactory.com/net/strategy-design-pattern)
    - [Builder](https://www.dofactory.com/net/builder-design-pattern)
    - [Singleton](https://www.dofactory.com/net/singleton-design-pattern)
    - [Facade](https://www.dofactory.com/net/facade-design-pattern)

17. Bibliotecas do Lado do Cliente
    - [Blazor](https://dotnet.microsoft.com/apps/aspnet/web-apps/blazor)

18. Mecanismos de Modelo
    - [Razor](https://docs.microsoft.com/aspnet/core/mvc/views/razor)
    - [DotLiquid](https://github.com/dotliquid/dotliquid)
    - [Scriban](https://github.com/lunet-io/scriban)
    - [Fluid](https://github.com/sebastienros/fluid)

19. Bom saber
    - [MediatR](https://github.com/jbogard/MediatR)
    - [Fluent Validation](https://github.com/JeremySkinner/FluentValidation)
    - [Polly](https://github.com/App-vNext/Polly)
    - [Benchmark.NET](https://github.com/dotnet/BenchmarkDotNet)
    - [NodaTime](https://github.com/nodatime/nodatime)
    - [GenFu](https://github.com/MisterJames/GenFu)
    - [Swashbuckle](https://github.com/domaindrivendev/Swashbuckle.AspNetCore)
