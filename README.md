# MVC-PHP
Um programa que visa ilustrar o uso do CRUDD em  MVC e PHP 

Detalhes:
Os Produtos devem contar com as seguintes informações:
1. Nome
2. Categoria
3. Quantidade
4. Preço

Regras:

As regras abaixo devem ser seguidas ao cadastrar/editar um Produto:
1. Não devem haver Produtos com o mesmo nome uma vez que o produto é uma chave primaria
2. A quantidade e o preço, não podem ser zerados nem negativos

Detalhes sobre o programa:

1. Conexao.php são os arquivos de configurações do sistema de produto
2. diretório "view" é onde fica todas as telas do sistema
3. diretório "controller" é onde fica fica as funcionalidades do sistema que interragem com o banco
de dados
4. diretório "model" é onde fica os arquivos de conexão com o banco de dados
No diretório "view" existem 3 páginas principais: editar.php, cadastro.php e index.php. a página head
e menu são os escopos do HTML e Menu do sistemas respectivamente.
No diretório "controller" estão os arquivos PHP que executam as funcionalidades do sistema.
No diretório "model" estão os arquivos de conexão com o Banco de Dados
O arquivo bancodeDados.sql é o scrip em sql que cria o banco e a tabela.
