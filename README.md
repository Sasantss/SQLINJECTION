# <img src="https://emojis.slackmojis.com/emojis/images/1531849353/4244/blob-octopus.gif" width="60" height="60"/>  SQLINJECTION - MY STUDY NOTES


# # SQL Injection Awareness

## O que é SQL Injection?

SQL Injection é uma técnica de ataque na qual um invasor insere código SQL malicioso em uma consulta SQL. Isso pode levar à execução não autorizada de comandos SQL e comprometer a integridade e a segurança do sistema.

## Como Funciona

1. **Entrada Não Validada:**
   - A vulnerabilidade geralmente ocorre quando as entradas do usuário não são devidamente validadas antes de serem utilizadas em consultas SQL.

2. **Inserção de Código Malicioso:**
   - Um atacante insere código SQL malicioso por meio de campos de entrada, como formulários da web, parâmetros de URL ou cookies.

3. **Execução de Comandos Não Autorizados:**
   - O código malicioso é executado no banco de dados, permitindo ao invasor manipular, excluir ou extrair informações não autorizadas.

## Como Evitar SQL Injection

1. **Parâmetros Preparados:**
   - Utilize parâmetros preparados ou consultas parametrizadas para separar dados do código SQL.

2. **Validação de Entrada:**
   - Valide e filtre todas as entradas do usuário para garantir que apenas dados válidos sejam aceitos.

3. **Princípio do Menor Privilégio:**
   - Atribua as permissões mínimas necessárias para as consultas SQL, evitando o acesso desnecessário a dados sensíveis.

4. **Use ORM (Object-Relational Mapping):**
   - Considere o uso de ORM para interagir com o banco de dados de uma maneira mais segura e menos propensa a erros.



