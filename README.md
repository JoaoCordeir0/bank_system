## Manual de como rodar o projeto local

> João Victor Cordeiro - 13/08/2023

#

Requisitos:

* PHP 8.1;
* Composer do PHP;
* Inserir nas variáveis de ambiente do Windows o caminho da instalação do PHP;
    * Detalhes sobre as variáveis: https://devcontratado.com/blog/php/como-configurar-um-ambiente-php-mysql

Instalação de pacotes:

* Para instalar as dependências do projeto basta rodar o seguinte comando: *"composer install"*

Rodar o projeto:

* Para rodar o projeto após instalar as dependências basta rodar o seguinte comando: *"php -S localhost:9090"*

Banco de dados:

* O backup e schema do banco de dados estão na pasta "db" do projeto, basta rodar os scripts para restaurar o banco.
* Caso necessite, ajuste a conexão do banco no arquivo: *"src/core/database.php"*

Credenciais de acesso para teste:

* Account: 08344-6
* Password: 129055
