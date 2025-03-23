# Fake Shop


## Variável de Ambiente
DB_HOST	=> Host do banco de dados PostgreSQL.

DB_USER => Nome do usuário do banco de dados PostgreSQL.

DB_PASSWORD	=> Senha do usuário do banco de dados PostgreSQL.

DB_NAME	=>	Nome do banco de dados PostgreSQL.

DB_PORT	=>	Porta de conexão com o banco de dados PostgreSQL.

# Instrução de execução
Endereço aplicação: http://134.209.130.117/

- Pipeline CI
  - Utilização de actions para logar no Docker Hub utilizando secrets.
  - Utilização de actions para buildar a imagem e enviar para o repositório no Docker Hub com atualização de versão automática.

- Pipeline CD
  - Fazer configuração do ambiente com o kubeconfig utilizando secrets.
  - Fazer o deploy e atualização da aplicação caso necessário.
