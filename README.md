*SOBRE O PROJETO:*

Primeiro projeto utilizando a biblioteca AXIOS, que é uma biblioteca que permite a utilização de requisições de maneira facilitada. Nesse projeto usei AXIOS para requisições com métodos GET, POST, DELETE, PUT...
Outra funcionalidade utilizada foi a criação de uma "baseURL", diminuindo repetições de código e facilitando possíveis futuras alterações.
Além disso, utilizei a biblioteca React, com "react-router-dom", para a construção de um site SPA( Single Page Application/Aplicação de Página Única ), ou seja, inibindo a necessidade de recarregar a página durante a navegação pelo site,
apenas renderizando alguns elementos de uma única página HTML, gerando mais responsividade e agilidade, com a inibição de carregamentos.
Também utilizei, obviamente, elementos básicos de HTML para estruturar os componentes que alteram a página, CSS para estilizar cada componente de forma intuitiva e bonita, tornando os componentes agradáveis ao usuário,
e JavaScript, para adicionar interatividade ao projeto. Com os códigos JS foi possível adicionar algumas funcionalidades como, por exemplo, a edição de posts, a exclusão de posts e dentre outros.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

*OBSERVAÇÕES:*

1) BIBLIOTECA X FRAMEWORK:
  Tanto frameworks quanto bibliotecas são conjuntos de códigos ( funções, objetos, classes... ) escritas por outras pessoas que podem ser reutilizados para facilitar seu código e resolver certos problemas.
  A diferença entre um e outro está na INVERSÃO DE CONTROLE: enquanto na biblioteca você escolhe o fluxo da aplicação, escolhendo quando usar e chamar a biblioteca, no framework é ele quem controla o fluxo, direcionando
  locais onde você pode colocar seu código e chamando-o quando necessário. Ou seja, nos frameworks há a inversão de controle, enquanto na biblioteca não há. Além disso, frameworks são mais opinativos, ou seja, tem um menor grau de liberdade
  para o desenvolvedor quanto à estruturação do seu código. Logo, percebe-se que frameworks possuem regras mais rígidas, com uma estrutura completa para o desenvolvimento do projeto,
  sendo mais complexos de aprender a utilizar, já as bibliotecas podem ser usadas em pontos específicos do código e tem menor complexidade em seu uso.

============================================================================================

2) SPA:
  Single Page Application são aplicações que carregam apenas um documento WEB, ou seja, na primeira vez que o usuário entra na aplicação todos os códigos serão carregados.
  A mudança na página ocorre por meio de JavaScript, carregando o conteúdo conforme o usuário for navegando, pois todo o conteúdo ja foi tranferido para o client-side.
  O uso de SPA faz com que não haja necessidade de fazer novas requisições ao servidor para carregamento de páginas, isso torna tudo mais rápido para o cliente e mais leve para o servidor.
  O uso de SPA requer que o JS esteja sempre funcionando, ou seja, se o usuário desativar o JS porvavelmente ocrrerão erros, além de dificultar a otimização do SEO( Search Engine Optimization ).

============================================================================================
 3) AXIOS:
   Axio é um cliente HTTP promises based, ou seja, ele faz requisições HTTP para o servidor, para que não tenhamos que configurar toda essa comunicação entre cliente e servidor manualmente.
   Ele é isomófico, o que significa que roda tanto no navegador quanto no Node.Js com o mesmo código base.
   Para o servidor ele usa o código nativo Node.js ( módulo http ) e no lado do cliente utiliza XMLHttpRequest ( objeto utilizado para interações com o servidor, podendo "buscar" qualquer tipo de dado para a 
   página sem a necessidade de que essa seja recarregada completamente ).
   
============================================================================================
