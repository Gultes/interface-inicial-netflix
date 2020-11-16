Representa a recriação FRONT-END da interface inicial do NETFLIX, de forma responsiva, segundo as aulas do bootcamp Everis FullStack!

**Personalizações realizadas:**

Navegação:

- Ao clicar no logo (Título em vermelho 'NETFLIX'), vai para a página de login oficial da NETFLIX
- Ao clicar em 'Início' vai para a página inicial oficial da NETFLIX
- Ao clicar em 'Séries', 'Filmes' ou 'Documentários', vai para o catálogo da NETFLIX.
- Ao clicar em 'ASSISTA AGORA' ou 'MAIS INFORMAÇÔES', vai para a página da série 'VIKINGS' na NETFLIX.

Layout:

​	main.css

* Fonte em body{} e logo{} alteradas para 'Arial Narrow'

* Elemento header nav{} setado para o centro do página com margin-right: 50%. [Está sendo verificado o porque de .container{justify-content: space-between;} não ter funcionado da forma esperada]

* header .container a{} setado com text-decoration: none para não influênciar na apresentação da fonte da logo

* botao a{} setado com text-decoration: none e color: whitesmoke para não influenciar na apresentação da fonte dos botões

* botao:hover modificado para alterar a cor para cinza escuro preservando o aspecto da ação flutuar sobre os botões

* Diminuida a margem do título para ter um aspecto mais justo ao tamanho da tela.

  

  responsive.css

* header nav{} configurado com margin: auto para centralizar as opções do menu quando a largura for até 1000px

  

  

