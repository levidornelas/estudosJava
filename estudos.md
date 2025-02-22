# Spring - Fundamentos

## Separação em Módulos:
- **Core**
- **Data:** JDBC, ORM
- **Web:** Web, Servlet, Struts
- **Tests:** Beans, Core, Context

## Ciclo de Vida de Beans:
- **Singleton** - Apenas uma instância do objeto é criada para toda a aplicação.
- **Prototype** - Um novo objeto será criado a cada solicitação ao container.

## Spring Boot:
- Configuração automática de dependências e inversão de controle.
- Embutimento de servidores (Tomcat, Jetty, Undertow).
- Arquitetura baseada em convenção sobre configuração.
- Suporte para perfis de aplicação (`application.properties` ou `application.yml`).
- Integração com Spring Data, Security, Cloud, etc.

## Spring Web:
- **Spring MVC** - Framework para desenvolvimento web baseado no padrão Model-View-Controller.
- **RestController** - Anotação que combina `@Controller` e `@ResponseBody`, simplificando APIs REST.
- **RequestMapping** - Define rotas HTTP para métodos do controlador.
- **PathVariable e RequestParam** - Captura de parâmetros de URL e requisição.
- **ResponseEntity** - Customização de respostas HTTP, incluindo status e headers.
- **Exception Handling** - Manipulação de exceções globais com `@ControllerAdvice` e `@ExceptionHandler`.

## Spring Security:
- Autenticação e autorização com configuração programática e declarativa.
- Suporte para OAuth2, JWT, e integração com provedores de identidade.
- Filtragem de requisições HTTP com filtros de segurança.

## Spring Data:
- Abstração para JPA, JDBC, MongoDB, Redis, e outros.
- Repositórios baseados em interfaces com `JpaRepository`.
- Suporte para consultas derivadas e personalizadas.

## Spring Cloud:
- Microsserviços e comunicação entre serviços.
- Configuração distribuída com Spring Cloud Config.
- Balanceamento de carga com Ribbon e OpenFeign.
- Service Discovery com Eureka.
- Gateway API com Spring Cloud Gateway.

## Testes no Spring:
- Testes unitários e de integração com `SpringBootTest`.
- Mock de dependências com `@MockBean` e `@WebMvcTest`.
- Teste de endpoints REST com `MockMvc`.
