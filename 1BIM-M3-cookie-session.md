# Exercício 1 — Pergunta conceitual
## Explique a diferença entre cookies e sessions no PHP.

Em sua resposta, considere:

onde os dados são armazenados
quais são mais seguros
em quais situações cada um pode ser mais adequado.

*Resposta:* Sessions armazenam os dados no servidor, enquanto apenas um identificador (ID da sessão) fica no navegador do usuário. Já os cookies armazenam os dados diretamente no navegador.
Por isso, as sessions são consideradas mais seguras, pois as informações sensíveis não ficam expostas no lado do cliente. Elas são geralmente usadas para armazenar dados temporários e sensíveis, como informações de login e autenticação.
Os cookies, por outro lado, são mais utilizados para armazenar dados não sensíveis e que precisam persistir por mais tempo, como preferências do usuário (tema do site, idioma, lembrar login, etc.).

---
# Exercício 2 — Pergunta de aplicação
## Imagine que você está desenvolvendo um sistema de loja virtual.

Explique como cookies e sessions poderiam ser utilizados para:

manter o usuário logado
armazenar itens temporários no carrinho
registrar preferências do usuário.
Justifique suas escolhas.

*Resposta*: Para manter o login o ideal é utilizar sessions pois é mais seguro e fica guardado no servidor, porém caso queira manter o login mesmo após fechar o navegador é necessário usar cookies pois eles guardam as informações por mais tempo. para armazenar itens temporários no carrinho utilizamos cookies pois ele guardam os itens por um tempo. Para registrar preferências do usuário tem que usar cookies pois guarda por mais tempo.
