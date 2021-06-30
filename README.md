Estes documento README tem como objetivo fornecer as informaçõeses necessárias para realização do projeto Contas.

### O QUE FAZER ?

- Você deve realizar um fork deste repositório e, ao finalizar, enviar o link do seu repositório para a nossa equipe. Lembre-se, Não é necessário criar um Pull Request para isso, não iremos avaliar e retornar por email o resultado do seu teste.

### ESCOPO DO PROJETO

- Deve ser criada uma API em **Java** utilizando **Spring** ou **JAX-RS (RESTEasy)**.
- A API deve fazer o seguinte:

    1. Listar contas;
    2. Consultar uma conta por id;
    3. Criar contas;
    4. Atualizar contas;
    5. Remover contas.

### Informações Importantes

- A tabela de contas deve conter as seguintes colunas:

    - id
    - agencia
    - numero_conta
    - codigo_banco

- Ao final da implementação o sistema deve expor as seguintes rotas:

    - GET /api/v1/contas
        - Listagem de contas.
    - GET /api/v1/contas/{id}
        - Consulta de conta por id.
    - POST /api/v1/contas
        - Criação de conta
    - PUT /api/v1/contas/{id}
        - Atualização de conta por id.
    - DELETE /api/v1/contas/{id}
        - Remoção de conta por id.

- O retorno dos serviçoos deve ser em JSON.

- É obrigatório utilização de Banco de Dados **MySql** ou **PostgreSQL**.

- Quando seu código for finalizado e disponibilizado para validarmos, vamos subir em nosso servidor e realizar os devidos testes.

- Independente de onde conseguiu chegar no teste é importante disponibilizar seu fonte para analisarmos.

### Dicas

- Introdução ao REST: 
    1. https://www.infoq.com/br/articles/rest-introduction/
    2. https://www.devmedia.com.br/introducao-ao-rest-ws/26964

- Spring:

    1. https://spring.io/guides
    2. https://www.youtube.com/watch?v=QHjFVajYYHM&t=16s

- JAX-RS:

    1. https://www.baeldung.com/resteasy-tutorial
    2. https://docs.jboss.org/resteasy/docs/4.3.1.Final/userguide/html_single/index.html
    3. https://github.com/resteasy/resteasy-examples/tree/3.6.0.Final
