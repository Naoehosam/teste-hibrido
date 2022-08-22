<h1 align="center"> Teste Frontend Híbrido </h1>
O teste foi feito no Magento 2.4.5 Community
Blocos da homepage foram feitos por PHTML e estilizado com LESS/CSS
Somente os blocos de slider de produtos foram feitos com PageBuilder porém são puxados para o front com XML
Blocos de banners todos feitos com PHTML, mesmo eu crendo que seria melhor usar PageBuilder para uma futura customização dos banners e links pelo cliente.


Instalação da loja:

Baixar DUMP do SQL disponível no GitHub;
Rodar os comandos de instalação padrão do Magento;
Caso o tema não venha ativo, entrar no painel de admin e ativar;
Recomendo usar PHP Server do próprio Magento com o seguinte comando: 

php -S 127.0.0.1:8082 -t ./pub/ ./phpserver/router.php

porém pode ser utulizado em demais ambientes (Docker, Valet...)
