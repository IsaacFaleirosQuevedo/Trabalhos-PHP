# Trabalhos php

# Escrever uma descrição

---

# ACT-PHP-002-cookie-session
4. Exercícios
Exercício 1 — Pergunta conceitual
Explique a diferença entre cookies e sessions no PHP.

Em sua resposta, considere:

onde os dados são armazenados
quais são mais seguros
em quais situações cada um pode ser mais adequado.

Resposta: No session, os dados são armazenados no servidor enquanto nos cookies são armazenados no navegador, fazendo com que o session seja mais seguro. O session é mais usado para dados sensíveis, temporários; cookies são usados para dados que não sejam sensíveis e que persistem por mais tempo.

Exercício 2 — Pergunta de aplicação
Imagine que você está desenvolvendo um sistema de loja virtual.

Explique como cookies e sessions poderiam ser utilizados para:

manter o usuário logado
armazenar itens temporários no carrinho
registrar preferências do usuário.
Justifique suas escolhas.

Resposta: Para manter o login o ideal é utilizar sessions pois é mais seguro e fica guardado no servidor, porém caso queira manter o login mesmo após fechar o navegador é nessessário usar cookies pois eles guardam as informações por mais tempo. para armazenar itens temporários no carrinho utilizamos cookies pois ele guardam os itens por um tempo. Para registrar preferências do usuário tem que usar cookies pois guarda por mais tempo.

Exercício 3 — Pergunta de investigação
Crie um arquivo chamado teste.php com o seguinte código:

<?php

setcookie("contador", "1", time()+3600);

if(isset($_COOKIE["contador"])) {
    echo "Valor do cookie: " . $_COOKIE["contador"];
} else {
    echo "Cookie ainda não disponível.";
}

?>
Agora realize os seguintes passos:

Execute o arquivo no navegador.
Atualize a página.
Abra as ferramentas do navegador e visualize os cookies.
Limpe os cookies do site e atualize novamente.
Descreva:

o que aconteceu em cada etapa
por que o cookie não aparece imediatamente na primeira execução.

Resposta: Primeiro não há nenhum cookie disponível, aí quando você recarrega tem um cookie, depois quando você deleta e recarrega não tem mais cookie.

Por que sessions são geralmente preferidas para autenticação de usuários em sistemas web?

Discuta:

segurança
manipulação de dados
possíveis riscos ao utilizar apenas cookies.

Resposta: Porque é mais seguro, visto que os cookies guardam as informações no navegador e o session no servidor




