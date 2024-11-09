[[1. Introdução ao Spring Boot]]
- O que é Spring Boot e seus benefícios.
- Diferença entre Spring Framework e Spring Boot.
- Como configurar e iniciar um projeto Spring Boot.

[[2. Estrutura de Projeto no Spring Boot]]

- Organização de pastas e pacotes (Controllers, Services, Repositories).
- Convenções de nomeação e configuração.

[[3. Configurações no Spring Boot]]

- Arquivo `application.properties` e `application.yml`.
- Variáveis de ambiente e profiles (como `dev`, `test`, `prod`).
- Configuração de porta e outras propriedades.

[[4. Injeção de Dependência e Beans]]

- Injeção de dependência (Autowired).
- Gerenciamento de Beans com Spring.
- Ciclo de vida de Beans no Spring Boot.

[[5. Anotações Principais]]

- `@SpringBootApplication`, `@RestController`, `@Service`, `@Repository`, `@Entity`.
- Anotações de mapeamento HTTP (`@GetMapping`, `@PostMapping`, etc.).
- `@Autowired`, `@Qualifier`, `@Component`.

[[6. Controllers e Rotas]]

- Criação de endpoints RESTful.
- Manipulação de rotas e parâmetros.
- Retorno de respostas JSON.

[[7. Trabalhando com Banco de Dados]]

- Configuração de conexão com bancos de dados (ex: MySQL, PostgreSQL).
- JPA e Hibernate (ORM).
- Anotações JPA (`@Entity`, `@Id`, `@GeneratedValue`, etc.).
- Repositories no Spring Data JPA (`JpaRepository`, `CrudRepository`).

[[8. Spring Boot DevTools]]

- Ferramentas para desenvolvimento e atualização automática.
- Como ativar e configurar o DevTools.

[[9. Spring Security (Básico)]]

- Introdução à autenticação e autorização.
- Configuração de segurança básica.
- Conceitos de tokens JWT para autenticação (opcional).

[[10. Gerenciamento de Exceções]]

- Manipulação de erros e exceções.
- Anotações `@ControllerAdvice` e `@ExceptionHandler`.

[[11. Documentação de APIs com Swagger]]

- Configuração e uso do Swagger para documentar APIs.
- Endpoints automáticos de documentação.

[[12. Testes no Spring Boot]]

- Introdução aos testes unitários e de integração.
- Ferramentas de teste (`JUnit`, `Mockito`).
- Testes de APIs e banco de dados.

[[13. Deploy e Produção]]

- Empacotamento da aplicação como `.jar` ou `.war`.
- Deploy em servidores (ex: AWS, Heroku, DigitalOcean).
- Monitoramento e log de aplicações Spring Boot em produção.
