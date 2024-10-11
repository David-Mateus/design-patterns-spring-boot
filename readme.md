###  Padrões de Projeto na API Spring Boot

- Singleton
`No Spring, o padrão Singleton é implementado automaticamente ao usar @Autowired. Isso garante que apenas uma instância do bean é criada e gerenciada pelo contêiner do Spring durante todo o ciclo de vida da aplicação.
Uso: A injeção de dependência com @Autowired garante que você tenha uma única instância, otimizando recursos e simplificando a gestão de estados compartilhados.
`
---
- Strategy
`Na camada de serviço, criei uma interface que é implementada por diferentes classes, cada uma com um comportamento específico. Esse padrão facilita a substituição ou adição de novas estratégias sem alterar o código principal, aproveitando o polimorfismo.`
---
- Facade ` é usada para esconder a complexidade de interações com subsistemas na API, oferecendo uma interface simples para os clientes. Ela agrega várias chamadas e processos complexos em métodos únicos, simplificando a lógica e facilitando o uso.`
