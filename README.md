<h1 align="center"> Teste Frontend Híbrido </h1>
<p>O teste foi feito no Magento 2.4.5 Community</p>
<p>Blocos da homepage foram feitos por PHTML e estilizado com LESS/CSS</p>
<p>Somente os blocos de slider de produtos foram feitos com PageBuilder porém são puxados para o front com XML</p>
<p>Blocos de banners todos feitos com PHTML, mesmo eu crendo que seria melhor usar PageBuilder para uma futura customização dos banners e links pelo cliente.</p>

<h2 align="center"> Instalação da loja: </h2>

<p>Baixar DUMP do SQL disponível no GitHub;</p>
<p>Rodar os comandos de instalação padrão do Magento;</p>
<p>Caso o tema não venha ativo, entrar no painel de admin e ativar;</p>
<p>Recomendo usar PHP Server do próprio Magento com o seguinte comando:</p> 

<p>php -S 127.0.0.1:8082 -t ./pub/ ./phpserver/router.php</p>

<p>porém pode ser utulizado em demais ambientes (Docker, Valet...)</p>