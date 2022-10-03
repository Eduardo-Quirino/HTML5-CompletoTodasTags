![Tags HTML5 – Diego Mariano](https://diegomariano.com/wp-content/uploads/2020/08/tag.png)



- ## [Validador de código](https://validator.w3.org/)

- ## [Site w3schools - Suporte para desenvolvedores](https://www.w3.org/)

  

> 1 -✔ <img src="https://diegomariano.com/wp-content/uploads/2020/08/tag.png" alt="img" style="zoom: 25%;" /> [Codificação básica ](https://www.youtube.com/watch?v=BUpk68lggtY&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=1&t=33s)
>
> > ```html
> > <!DOCTYPE html>
> > <html lang="pt-br">
> >     <head>
> >         <title></title>
> >     </head>
> >          <body>
> >          </body>
> > </html>
> > ```
> >
> > - < ! DOCTYPE > = Instrução que diz qual versão do HTML estamos trabalhando
> > - < HTML > = Tag container raiz DOM Interface Uses HTMLElement
> > - < HEAD > = Cabeça da página DOM Interface Uses HTMLElement Contido por < HTML >
> > - < TITLE > = Título da página DOM Interface Uses HTMLElement
> >   Categoria = Metadado Contido por : < HEAD >
> > - < BODY > = Corpo da página DOM Interface interface HTMLBodyElement : HTMLElement Categoria = Seção Raiz Contido por : < HTML >
>
> 
>
> 2 -✔  <img src="https://diegomariano.com/wp-content/uploads/2020/08/tag.png" alt="img" style="zoom: 25%;" /> [Tag P e mais regras e detalhes importantes HTML ](https://www.youtube.com/watch?v=kFitfXelH0Q&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=2)
>
> - [Categorias](https://html.spec.whatwg.org/multipage/dom.html#concept-element-categories) :Conteúdo do fluxo, Conteúdo palpável.
>
> 
>
> 3 -✔   <img src="https://diegomariano.com/wp-content/uploads/2020/08/tag.png" alt="img" style="zoom: 25%;" /> [Tags H, h1 até h6 ](https://www.youtube.com/watch?v=Xw_dEW7R3SM&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=3&t=264s)
>
> > Categoria : Fluxo e Cabeçalho
> > Display : Block
> > DOM Interface : Uses HTMLElement
> >
> > 
>
> 
>
> 4 -✔   <img src="https://diegomariano.com/wp-content/uploads/2020/08/tag.png" alt="img" style="zoom: 25%;" /> [Tag a - Âncora ](https://www.youtube.com/watch?v=9ByTCcGSIcw&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=4&t=1177s)
>
> >**DOM Interface**
> >interface HTMLAnchor Element : HTMLElement {
> >    attribute DOMString target ;
> >    attribute DOMString download ;
> >    attribute DOMString rel ;
> >         [ SameObject , Put Forwards - value ] readonly attribute DOMTokenlist rellist ;
> >    attribute DOMString hreflang ;
> >    attribute DOMString type ;
> >    attribute DOMString text ;
> >HTMLAnchor Element implements HTMLHyperlinkElementUtils ;
> >
> >
> >
> >**TARGET**
> >     blank
> >    _parent
> >    _self
> >   _top
> >    framename 
> >
> >**MEDIA**
> >    all = ( padrão ) Adequado para todos os dispositivos -
> >    aural =  de fala auditiva Sintetizadores
> >    braille =  Dispositivod de Braille
> >    handheld =  Dispositivos de tela pequena e banda limitada
> >    projection =  Projetores
> >    print = Impressoras
> >    screen = Telas de computador
> >    tv = Televisores    
> >
> >   
>
> 
>
> 5 - ✔  <img src="https://diegomariano.com/wp-content/uploads/2020/08/tag.png" alt="img" style="zoom: 25%;" />[Tag abbr - Abreviações](https://www.youtube.com/watch?v=aE07AI2mwSE&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=5)
>
> > - Faz um breve comentário sobre o elemento.
> >
> > Display : inline
> > Categoria : Fluxo e Fraseado
> > Contido por : Fraseado
> > Filhos : Fraseado
> > Atributos = title e globais
> >
> > ```html
> > <p>Cursode <abbr title="Hypertext Markup Language">       HTML</abbr> Completo e Proficional <abbr
> >         title="Canal Curso Fessor Bruno"> CFBC </abbr></p>
> > ```
>
> 
>
> 6 -✔   <img src="https://diegomariano.com/wp-content/uploads/2020/08/tag.png" alt="img" style="zoom: 25%;" /> [Tag address - Informações de contato](https://www.youtube.com/watch?v=swUF0MQBq10&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=6)
>
> > - Tag utilizada para contato
> >
> > Display : Block
> > Categoria : Fluxo
> > Filhos : Fluxo
> > DOM interface : Uses HTMLElement
> >
> > ```html
> > <footer>
> >     <address>
> >         Autor: Eduardo Quirino <br>
> >         Programador: <a href="https://github.com/Eduardo-Quirino" target="_blank">Informaões do
> >             Programador</a>
> >     </address>
> > </footer>
> > ```
> >
> > 
>
> 
>
> 
>
> 7 - ✔  <img src="https://diegomariano.com/wp-content/uploads/2020/08/tag.png" alt="img" style="zoom: 25%;" />[Tags area e map](https://www.youtube.com/watch?v=2wOXCNBfUK8&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=7)
>
> > **area**
> >
> > **interface HTMLArea Element : HTMLElement** {
> > attribute DOMString alt ;
> > attribute DOMString coords ;
> > attribute DOMString shape ;
> > attribute DOMString target ;
> > attribute DOMString download ;
> > attribute DOMString rel ;
> > [ Same Object , Put Forwards = value ] readonly attribute
> > DOMToken List relList ;
> > attribute DOMString hreflang ;
> > attribute DOMString type ;
> > attribute DOMString referrer Policy ;
> > } ;
> > HTMLArea Element implements
> > MIMLMуреrlinkElementutifs
> >
> > 
> >
> > Display : None ( nenhum )
> > Categoria : Fluxo e
> > Fraseado
> > Contido por : < map >
> > Filhos : None ( vazio )
> >
>
> 
>
> 
>
> 8 - <img src="https://diegomariano.com/wp-content/uploads/2020/08/tag.png" alt="img" style="zoom: 25%;" />[Tags article e a Nova Semântica](https://www.youtube.com/watch?v=ePUD7uBdV9o&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=8)
>
> > - **article** - representa uma sessão independente no projeto  
> >
> >   Display: Block
> >
> >   Categoria: Fluxo e Seção
> >
> >   Contido por: Fluxo
> >
> >   Filhos: Fluxo
> >
> >   DOM Interface: Uses HTMLElement
> >
> > 
>
> 
>
> 9 -✔ <img src="https://diegomariano.com/wp-content/uploads/2020/08/tag.png" alt="img" style="zoom: 25%;" />[Tag aside da Nova Semântica ](https://www.youtube.com/watch?v=1qvcjr9DFJc&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=9)
>
> > - O elemento de lado representa uma seção de uma página que consiste em conteúdo tangencialmente relacionado ao conteúdo ao redor do elemento de lado e que pode ser considerado separado desse conteúdo.
> >
> > Display: Block
> >
> > Categoria: Fluxo e Seção
> >
> > Contido por: Fluxo
> >
> > Filhos: Fluxo
> >
> > DOM Interface: Uses HTMLElement
>
> ### 
>
> 10 -✔<img src="https://diegomariano.com/wp-content/uploads/2020/08/tag.png" alt="img" style="zoom: 25%;" />[Tag audio, inserindo música e sons na página](https://www.youtube.com/watch?v=seFNHyf_3ps&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=10)
>
> > - Descrição
> >
> >   Um elemento de áudio representa um som ou fluxo de áudio. O conteúdo pode ser fornecido dentro do elemento de áudio. Os agentes do usuário não devem mostrar esse conteúdo ao usuário; destina-se a navegadores da Web mais antigos que não suportam áudio, para que os plug-ins de áudio legados possam ser testados ou para mostrar texto aos usuários desses navegadores mais antigos informando como acessar o conteúdo de áudio. O elemento de áudio é um elemento de mídia cujos dados de mídia são ostensivamente dados de áudio. Os atributos src, preload, autoplay, mediagroup, loop, muted e controls são os atributos comuns a todos os elementos de mídia.
> >
> > - Atributos
> >
> > [atributos HTML globais novo](https://www.w3.org/2009/cheatsheet/#inf,html,a,global HTML attributes) 
> >
> > - [autoplay novo](https://www.w3.org/2009/cheatsheet/#inf,html,a,autoplay) 
> > - [pré -carregamento novos](https://www.w3.org/2009/cheatsheet/#inf,html,a,preload) 
> > - [controles novo](https://www.w3.org/2009/cheatsheet/#inf,html,a,controls) 
> > - [loop novo](https://www.w3.org/2009/cheatsheet/#inf,html,a,loop) 
> > - [mediagroup novo](https://www.w3.org/2009/cheatsheet/#inf,html,a,mediagroup) 
> > - [silenciado novo](https://www.w3.org/2009/cheatsheet/#inf,html,a,muted) 
> > - [src novo](https://www.w3.org/2009/cheatsheet/#inf,html,a,src)
> >
> > Exemplo de código:
> >
> > ```html
> > <audio src="../_áudio/Doce Encontro - Alucinado (Pagode Do Doce - Ao Vivo)_256k.mp3" autoplay controls>
> >     <p>Navegador não suporta esse audio!</p>
> > </audio>
> > ```
> >
> > 
>
> 
>
> 
>
> 11- <img src="https://diegomariano.com/wp-content/uploads/2020/08/tag.png" alt="img" style="zoom: 25%;" />[Tag b, Bold/Negrito](https://www.youtube.com/watch?v=-u5UA57uKu4&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=11)
>
> > **Bold**
> >
> > Display: inline
> >
> > Categoria: Fluxo e Fraseado
> > Contido por: Fraseado
> > Filhos: Fraseado
>
> 
>
> 
>
> 12
>
> [![img](https://i.ytimg.com/vi/mJvwG2f07qQ/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLD1ZfiTEVb6d9_FfuK0rx_Pu7T_Nw)14:56TOCANDO AGORA](https://www.youtube.com/watch?v=mJvwG2f07qQ&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=12)
>
> ### [Tag base, apontamento de local padrão - Curso de HTML Completo e Profissional #12](https://www.youtube.com/watch?v=mJvwG2f07qQ&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=12)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 13
>
> [![img](https://i.ytimg.com/vi/R5LRu9UULJ8/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLB3Mdb8P99ID69GUE82u5_JEYf5xg)6:55TOCANDO AGORA](https://www.youtube.com/watch?v=R5LRu9UULJ8&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=13)
>
> ### [Tag bdo, diração do texto - Curso de HTML Completo e Profissional #13](https://www.youtube.com/watch?v=R5LRu9UULJ8&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=13)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 14
>
> [![img](https://i.ytimg.com/vi/7o125pGe0a4/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLCYxZY9KkVH4Jji1p3U0Hcepa0RUA)11:33TOCANDO AGORA](https://www.youtube.com/watch?v=7o125pGe0a4&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=14)
>
> ### [Tags blockquote e cite, trabalhando com citações - Curso de HTML Completo e Profissional #14](https://www.youtube.com/watch?v=7o125pGe0a4&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=14)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 15
>
> [![img](https://i.ytimg.com/vi/fvLb4Gfpm9Q/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLCc7ILIhF1SXhpGr_KY8CWpKZYcag)18:54TOCANDO AGORA](https://www.youtube.com/watch?v=fvLb4Gfpm9Q&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=15)
>
> ### [Tag br, quebra de linha - Curso de HTML Completo e Profissional #15](https://www.youtube.com/watch?v=fvLb4Gfpm9Q&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=15)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 16
>
> [![img](https://i.ytimg.com/vi/YAr5yz4Rf8Q/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLATqcggJhzI6wvytshbHmWUmq7w4Q)13:32TOCANDO AGORA](https://www.youtube.com/watch?v=YAr5yz4Rf8Q&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=16)
>
> ### [Tag button - Curso de HTML Completo e Profissional #16](https://www.youtube.com/watch?v=YAr5yz4Rf8Q&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=16)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 17
>
> [![img](https://i.ytimg.com/vi/hUUdqQr2oBc/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLDbOM1FXQLsdb2i_gbI9E2dfBO89Q)7:32TOCANDO AGORA](https://www.youtube.com/watch?v=hUUdqQr2oBc&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=17)
>
> ### [Tag canvas - Curso de HTML Completo e Profissional #17](https://www.youtube.com/watch?v=hUUdqQr2oBc&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=17)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 18
>
> [![img](https://i.ytimg.com/vi/iKoFovMBvkU/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLCGVIowClHWVr8k2wEQyXIyYPOkMA)11:03TOCANDO AGORA](https://www.youtube.com/watch?v=iKoFovMBvkU&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=18)
>
> ### [Tags code e pre - Curso de HTML Completo e Profissional #18](https://www.youtube.com/watch?v=iKoFovMBvkU&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=18)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 19
>
> [![img](https://i.ytimg.com/vi/c56bK_HpNgE/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLBeV6XgPljkF-fpMm27-Mac25nmAQ)10:40TOCANDO AGORA](https://www.youtube.com/watch?v=c56bK_HpNgE&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=19)
>
> ### [Tags del e ins - Curso de HTML Completo e Profissional #19](https://www.youtube.com/watch?v=c56bK_HpNgE&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=19)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 20
>
> [![img](https://i.ytimg.com/vi/mylp2b1U7mA/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLBWFnlRDtTXQOYX55eyHM5wASK9SQ)16:16TOCANDO AGORA](https://www.youtube.com/watch?v=mylp2b1U7mA&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=20)
>
> ### [Tags details e Summary - Curso de HTML Completo e Profissional #20](https://www.youtube.com/watch?v=mylp2b1U7mA&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=20)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 21
>
> [![img](https://i.ytimg.com/vi/2fUHq6pa_PY/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLDS4wpueFfuJySbcaJTh_0x19MnPQ)5:36TOCANDO AGORA](https://www.youtube.com/watch?v=2fUHq6pa_PY&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=21)
>
> ### [Tag dfn - Curso de HTML Completo e Profissional #21](https://www.youtube.com/watch?v=2fUHq6pa_PY&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=21)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 22
>
> [![img](https://i.ytimg.com/vi/891e3lc7l28/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLA8Pf6yQ6inQ2UXY4OAcRs0R81UlQ)6:50TOCANDO AGORA](https://www.youtube.com/watch?v=891e3lc7l28&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=22)
>
> ### [Tag dialog - Curso de HTML Completo e Profissional #22](https://www.youtube.com/watch?v=891e3lc7l28&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=22)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 23
>
> [![img](https://i.ytimg.com/vi/YRcmot2S0Y0/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLAHf4MN1rumryaJas-xAFM2BAcO2A)13:33TOCANDO AGORA](https://www.youtube.com/watch?v=YRcmot2S0Y0&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=23)
>
> ### [Tag div (parte 1) - Curso de HTML Completo e Profissional #23](https://www.youtube.com/watch?v=YRcmot2S0Y0&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=23)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 24
>
> [![img](https://i.ytimg.com/vi/WxMEj-Jud_U/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLCSNS6nmlhM8wGlPfooNEOFlH1sOw)21:30TOCANDO AGORA](https://www.youtube.com/watch?v=WxMEj-Jud_U&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=24)
>
> ### [Tag dialog P2 - Curso de HTML Completo e Profissional #24](https://www.youtube.com/watch?v=WxMEj-Jud_U&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=24)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 25
>
> [![img](https://i.ytimg.com/vi/CQf4QTGDwvw/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLAfSw-SntwzCwoKDNPVqZhNZIkXOw)23:23TOCANDO AGORA](https://www.youtube.com/watch?v=CQf4QTGDwvw&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=25)
>
> ### [Tag div P2 - Curso de HTML Completo e Profissional #25](https://www.youtube.com/watch?v=CQf4QTGDwvw&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=25)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 26
>
> [![img](https://i.ytimg.com/vi/RBKKPX34-7I/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLBJnGS4rJjFXfN8AmCnL-mD5-uVdw)13:26TOCANDO AGORA](https://www.youtube.com/watch?v=RBKKPX34-7I&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=26)
>
> ### [Lista de definição, Tags dl, dt e dd - Curso de HTML Completo e Profissional #26](https://www.youtube.com/watch?v=RBKKPX34-7I&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=26)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 27
>
> [![img](https://i.ytimg.com/vi/GeO5Pdcxd84/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLDEEBafYn6TNWsKYD0VafSnfmLSbw)9:39TOCANDO AGORA](https://www.youtube.com/watch?v=GeO5Pdcxd84&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=27)
>
> ### [Tag em, para ênfase - Curso de HTML Completo e Profissional #27](https://www.youtube.com/watch?v=GeO5Pdcxd84&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=27)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 28
>
> [![img](https://i.ytimg.com/vi/v5DAO6VV6O8/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLDpskPzgvM6tRT105dPctlfoVY_Yg)8:32TOCANDO AGORA](https://www.youtube.com/watch?v=v5DAO6VV6O8&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=28)
>
> ### [Tag embed - Curso de HTML Completo e Profissional #28](https://www.youtube.com/watch?v=v5DAO6VV6O8&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=28)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 29
>
> [![img](https://i.ytimg.com/vi/sW_zXFRns5E/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLAuWApzWxYgHBkPe4YT78MjVMmg-w)9:24TOCANDO AGORA](https://www.youtube.com/watch?v=sW_zXFRns5E&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=29)
>
> ### [Tag figure - Curso de HTML Completo e Profissional #29](https://www.youtube.com/watch?v=sW_zXFRns5E&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=29)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 30
>
> [![img](https://i.ytimg.com/vi/Xbo67DvwB8A/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLAobhEg5f_fzf_mQHMmUHICzuPGRg)17:06TOCANDO AGORA](https://www.youtube.com/watch?v=Xbo67DvwB8A&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=30)
>
> ### [Tag footer (rodapé) - Curso de HTML Completo e Profissional #30](https://www.youtube.com/watch?v=Xbo67DvwB8A&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=30)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 31
>
> [![img](https://i.ytimg.com/vi/F0cKF7jkTsc/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLBzxHp5IsA4p4VjTusaD72tJ2bt4g)10:53TOCANDO AGORA](https://www.youtube.com/watch?v=F0cKF7jkTsc&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=31)
>
> ### [Formulário P1 - Curso de HTML Completo e Profissional #31](https://www.youtube.com/watch?v=F0cKF7jkTsc&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=31)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 32
>
> [![img](https://i.ytimg.com/vi/7bi1SLpZO5w/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLDsk1CFvuH89YrQxLL4Dng2If7hNg)8:48TOCANDO AGORA](https://www.youtube.com/watch?v=7bi1SLpZO5w&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=32)
>
> ### [Formulário P2 - Curso de HTML Completo e Profissional #32](https://www.youtube.com/watch?v=7bi1SLpZO5w&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=32)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 33
>
> [![img](https://i.ytimg.com/vi/bCByAs7eu_E/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLCl6R711_AR5yRUak1WFqO98Wjb6Q)20:47TOCANDO AGORA](https://www.youtube.com/watch?v=bCByAs7eu_E&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=33)
>
> ### [Formulário P3 (password, checkbox, radio) - Curso de HTML Completo e Profissional #33](https://www.youtube.com/watch?v=bCByAs7eu_E&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=33)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 34
>
> [![img](https://i.ytimg.com/vi/gx-De195nIg/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLAGqAwHW5hTdwQGUcg_59wLGld5eg)8:10TOCANDO AGORA](https://www.youtube.com/watch?v=gx-De195nIg&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=34)
>
> ### [Formulário P4 (date, time, datetime-local) - Curso de HTML Completo e Profissional #34](https://www.youtube.com/watch?v=gx-De195nIg&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=34)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 35
>
> [![img](https://i.ytimg.com/vi/QN_oujOxxIw/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLAjb6ICvcx12YplXO_G6RE1ExzUYg)6:08TOCANDO AGORA](https://www.youtube.com/watch?v=QN_oujOxxIw&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=35)
>
> ### [Formulário P5 (month, week, hidden) - Curso de HTML Completo e Profissional #35](https://www.youtube.com/watch?v=QN_oujOxxIw&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=35)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 36
>
> [![img](https://i.ytimg.com/vi/CBFJCXSWUBo/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLBIAWxojLj7Vk42itJK7TdhZaDAWg)9:13TOCANDO AGORA](https://www.youtube.com/watch?v=CBFJCXSWUBo&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=36)
>
> ### [Formulário P6 (input color, email, image) - Curso de HTML Completo e Profissional #36](https://www.youtube.com/watch?v=CBFJCXSWUBo&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=36)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 37
>
> [![img](https://i.ytimg.com/vi/lALfzoAWHYQ/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLB-RIyY8oEIj-Ok2lFBL4Azc7oXqg)11:19TOCANDO AGORA](https://www.youtube.com/watch?v=lALfzoAWHYQ&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=37)
>
> ### [Formulário P7 (input input tel, number, search) - Curso de HTML Completo e Profissional #37](https://www.youtube.com/watch?v=lALfzoAWHYQ&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=37)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 38
>
> [![img](https://i.ytimg.com/vi/51BGNvJOex8/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLC6GwBdCoc9uw96IROZddC0lvnkqg)9:07TOCANDO AGORA](https://www.youtube.com/watch?v=51BGNvJOex8&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=38)
>
> ### [Formulário P8 (input file, input url) - Curso de HTML Completo e Profissional #38](https://www.youtube.com/watch?v=51BGNvJOex8&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=38)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 39
>
> [![img](https://i.ytimg.com/vi/biCFxnXrQQc/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLBva-NBGwh8Ck6JmgZu4qL1-vJ2MA)9:26TOCANDO AGORA](https://www.youtube.com/watch?v=biCFxnXrQQc&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=39)
>
> ### [Formulário P9 (select, option) - Curso de HTML Completo e Profissional #39](https://www.youtube.com/watch?v=biCFxnXrQQc&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=39)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 40
>
> [![img](https://i.ytimg.com/vi/hgioCJ8OnzQ/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLBBCQZi6nJR58xgkgtc5lKxfhGWYA)9:03TOCANDO AGORA](https://www.youtube.com/watch?v=hgioCJ8OnzQ&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=40)
>
> ### [Formulário P10 (list, datalist) - Curso de HTML Completo e Profissional #40](https://www.youtube.com/watch?v=hgioCJ8OnzQ&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=40)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 41
>
> [![img](https://i.ytimg.com/vi/AgAB33E2N7U/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLAhN7EzbEdLNtXEG1MPrKs1MX7mLw)4:57TOCANDO AGORA](https://www.youtube.com/watch?v=AgAB33E2N7U&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=41)
>
> ### [Formulário P11 (fieldset) - Curso de HTML Completo e Profissional #41](https://www.youtube.com/watch?v=AgAB33E2N7U&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=41)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 42
>
> [![img](https://i.ytimg.com/vi/cvCsVU7RvcA/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLBEPObT1tJw9vCft5Fx_bTqtczbBQ)5:06TOCANDO AGORA](https://www.youtube.com/watch?v=cvCsVU7RvcA&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=42)
>
> ### [Formulário P12 (textarea) - Curso de HTML Completo e Profissional #42](https://www.youtube.com/watch?v=cvCsVU7RvcA&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=42)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 43
>
> [![img](https://i.ytimg.com/vi/nYQUfoOu6Ag/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLB32K-kU0UiFN2rHT8sw3Wc5eeqAg)17:23TOCANDO AGORA](https://www.youtube.com/watch?v=nYQUfoOu6Ag&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=43)
>
> ### [Headings, H1 a H6 - Curso de HTML Completo e Profissional #43](https://www.youtube.com/watch?v=nYQUfoOu6Ag&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=43)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 44
>
> [![img](https://i.ytimg.com/vi/HbHVcODfRSg/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLD-IGfhtTG13dGymiT2jnfiAhivxw)11:47TOCANDO AGORA](https://www.youtube.com/watch?v=HbHVcODfRSg&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=44)
>
> ### [Google Fonts, mudando as fontes do seu site - Curso de HTML Completo e Profissional #44](https://www.youtube.com/watch?v=HbHVcODfRSg&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=44)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 45
>
> [![img](https://i.ytimg.com/vi/LARHwWLSEHk/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLD6AjQuOptDub3Qd43gcIHP7URwZg)10:00TOCANDO AGORA](https://www.youtube.com/watch?v=LARHwWLSEHk&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=45)
>
> ### [Tag head (cabeça) - Curso de HTML Completo e Profissional #45](https://www.youtube.com/watch?v=LARHwWLSEHk&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=45)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 46
>
> [![img](https://i.ytimg.com/vi/8LRxc17GRVs/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLCgRBV13T0tJs1iKMIXu083PLRRcg)13:22TOCANDO AGORA](https://www.youtube.com/watch?v=8LRxc17GRVs&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=46)
>
> ### [tag header (cabeçalho de seções) - Curso de HTML Completo e Profissional #46](https://www.youtube.com/watch?v=8LRxc17GRVs&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=46)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 47
>
> [![img](https://i.ytimg.com/vi/0zUGYf7K0Cw/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLCT8R7uJbsttd7QxVQ_lF3AuEdq4g)8:56TOCANDO AGORA](https://www.youtube.com/watch?v=0zUGYf7K0Cw&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=47)
>
> ### [tag hr (Barra horizontal / Horizontal Rule) - Curso de HTML Completo e Profissional #47](https://www.youtube.com/watch?v=0zUGYf7K0Cw&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=47)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 48
>
> [![img](https://i.ytimg.com/vi/MExqRkcDReA/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLBPmSuqXamYy8l523cBb6ZWOBLCRg)7:57TOCANDO AGORA](https://www.youtube.com/watch?v=MExqRkcDReA&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=48)
>
> ### [Tag html - Curso de HTML Completo e Profissional #48](https://www.youtube.com/watch?v=MExqRkcDReA&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=48)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 49
>
> [![img](https://i.ytimg.com/vi/jTeXr7CqGNw/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLCfYok5UiBDvrF-YrGorOygFYZuFg)8:38TOCANDO AGORA](https://www.youtube.com/watch?v=jTeXr7CqGNw&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=49)
>
> ### [tag i - Curso de HTML Completo e Profissional #49](https://www.youtube.com/watch?v=jTeXr7CqGNw&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=49)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 50
>
> [![img](https://i.ytimg.com/vi/XimmximMPnE/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLBpxnFP0rjkl7WFkvmRMVzffVfZKA)11:06TOCANDO AGORA](https://www.youtube.com/watch?v=XimmximMPnE&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=50)
>
> ### [tag iframe - parte 1 - Curso de HTML Completo e Profissional #50](https://www.youtube.com/watch?v=XimmximMPnE&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=50)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 51
>
> [![img](https://i.ytimg.com/vi/9RMMH3Y4rcY/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLAr1J4VOGE9fjyyLvQCnymyZpkpdg)10:28TOCANDO AGORA](https://www.youtube.com/watch?v=9RMMH3Y4rcY&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=51)
>
> ### [Tag img - inserindo imagens na página web - Curso de HTML Completo e Profissional #51](https://www.youtube.com/watch?v=9RMMH3Y4rcY&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=51)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 52
>
> [![img](https://i.ytimg.com/vi/Gr6pR3VcmNc/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLCO-SVtAE1D8A9Y6h2D2oTwinrQPQ)4:43TOCANDO AGORA](https://www.youtube.com/watch?v=Gr6pR3VcmNc&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=52)
>
> ### [Tag kbd - Curso de HTML Completo e Profissional #52](https://www.youtube.com/watch?v=Gr6pR3VcmNc&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=52)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 53
>
> [![img](https://i.ytimg.com/vi/Hv01udPQsHk/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLDS-L9m3YNWwK1ssh1t9OxPl4hUig)9:07TOCANDO AGORA](https://www.youtube.com/watch?v=Hv01udPQsHk&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=53)
>
> ### [Tag link - Curso de HTML Completo e Profissional #53](https://www.youtube.com/watch?v=Hv01udPQsHk&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=53)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 54
>
> [![img](https://i.ytimg.com/vi/8pqiUYP0KmY/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLAHqOr5i1NUY1PnHEHOw_mRWInTqg)6:01TOCANDO AGORA](https://www.youtube.com/watch?v=8pqiUYP0KmY&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=54)
>
> ### [Tag mark - Curso de HTML Completo e Profissional #54](https://www.youtube.com/watch?v=8pqiUYP0KmY&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=54)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 55
>
> [![img](https://i.ytimg.com/vi/3_4eQmqC1bs/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLCueUl1oFZljbvM9BqTGJlA3ZaGUA)14:51TOCANDO AGORA](https://www.youtube.com/watch?v=3_4eQmqC1bs&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=55)
>
> ### [Tag iframe parte 2 - Curso de HTML Completo e Profissional #55](https://www.youtube.com/watch?v=3_4eQmqC1bs&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=55)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 56
>
> [![img](https://i.ytimg.com/vi/mtY-C9YpgSo/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLBrFJla1rrJMas9UvEO2-HW923FlA)22:10TOCANDO AGORA](https://www.youtube.com/watch?v=mtY-C9YpgSo&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=56)
>
> ### [Tags meta - Curso de HTML Completo e Profissional #56](https://www.youtube.com/watch?v=mtY-C9YpgSo&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=56)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 57
>
> [![img](https://i.ytimg.com/vi/5Wd1mQkob3A/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLA4UVQMlOkZNGDtn0M4PA2UsuplZA)7:11TOCANDO AGORA](https://www.youtube.com/watch?v=5Wd1mQkob3A&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=57)
>
> ### [Tag meter - Curso de HTML Completo e Profissional #57](https://www.youtube.com/watch?v=5Wd1mQkob3A&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=57)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 58
>
> [![img](https://i.ytimg.com/vi/XOlpzrYc4gA/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLCbeLFgDZVn1qQaqskyUY9hxNT_Zg)7:06TOCANDO AGORA](https://www.youtube.com/watch?v=XOlpzrYc4gA&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=58)
>
> ### [Tag nav - Curso de HTML Completo e Profissional #58](https://www.youtube.com/watch?v=XOlpzrYc4gA&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=58)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 59
>
> [![img](https://i.ytimg.com/vi/GHJD-bTnMS0/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLC0rB87ZuJA3vaCi83XO6uBL5im_A)4:34TOCANDO AGORA](https://www.youtube.com/watch?v=GHJD-bTnMS0&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=59)
>
> ### [Tag noscript- Curso de HTML Completo e Profissional #59](https://www.youtube.com/watch?v=GHJD-bTnMS0&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=59)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 60
>
> [![img](https://i.ytimg.com/vi/JnAvDAL2h4E/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLAErcyA0dhEi7bC7TEljRKHBHLOCg)11:34TOCANDO AGORA](https://www.youtube.com/watch?v=JnAvDAL2h4E&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=60)
>
> ### [Tag object- Curso de HTML Completo e Profissional #60](https://www.youtube.com/watch?v=JnAvDAL2h4E&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=60)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 61
>
> [![img](https://i.ytimg.com/vi/RmE9Ehxz78Q/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLDyh1b6vNESfqlXi-z7DeKNqFJ2dQ)9:40TOCANDO AGORA](https://www.youtube.com/watch?v=RmE9Ehxz78Q&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=61)
>
> ### [Tag OL (Listas Ordenadas) - Curso de HTML Completo e Profissional #61](https://www.youtube.com/watch?v=RmE9Ehxz78Q&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=61)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 62
>
> [![img](https://i.ytimg.com/vi/Pm9hd3chWbM/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLCkwUEBX1YRPGgPBE-AAe8e9mNhvA)7:27TOCANDO AGORA](https://www.youtube.com/watch?v=Pm9hd3chWbM&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=62)
>
> ### [Tag optgroup, agrupar elementos no select- Curso de HTML Completo e Profissional #62](https://www.youtube.com/watch?v=Pm9hd3chWbM&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=62)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 63
>
> [![img](https://i.ytimg.com/vi/G8kY_xdka0Y/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLAJSjgw1gGh8CDYHpTVeByrVYUtow)7:12TOCANDO AGORA](https://www.youtube.com/watch?v=G8kY_xdka0Y&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=63)
>
> ### [Tag output - Curso de HTML Completo e Profissional #63](https://www.youtube.com/watch?v=G8kY_xdka0Y&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=63)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 64
>
> [![img](https://i.ytimg.com/vi/c6sM0oTHlAk/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLCxuUgKlEJi5QGYnqmye0-iay2U-w)5:39TOCANDO AGORA](https://www.youtube.com/watch?v=c6sM0oTHlAk&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=64)
>
> ### [Tag progress - Curso de HTML Completo e Profissional #64](https://www.youtube.com/watch?v=c6sM0oTHlAk&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=64)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 65
>
> [![img](https://i.ytimg.com/vi/bCPQ4_oRFQ4/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLALy-jA6XOXgZ2HVl0qBcB3vMqsdg)4:49TOCANDO AGORA](https://www.youtube.com/watch?v=bCPQ4_oRFQ4&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=65)
>
> ### [Tag q (quote) - Curso de HTML Completo e Profissional #65](https://www.youtube.com/watch?v=bCPQ4_oRFQ4&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=65)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 66
>
> [![img](https://i.ytimg.com/vi/tpNJEF4qXw4/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLDvSVL-eQ_E41DLzeBu7G-PhRbyrQ)5:41TOCANDO AGORA](https://www.youtube.com/watch?v=tpNJEF4qXw4&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=66)
>
> ### [Tags ruby e rt - Curso de HTML Completo e Profissional #66](https://www.youtube.com/watch?v=tpNJEF4qXw4&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=66)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 67
>
> [![img](https://i.ytimg.com/vi/kLuNaX_O3oA/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLD45XmZZHCRpPnQLRffA8MxsG6YKQ)5:45TOCANDO AGORA](https://www.youtube.com/watch?v=kLuNaX_O3oA&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=67)
>
> ### [Tag samp - Curso de HTML Completo e Profissional #67](https://www.youtube.com/watch?v=kLuNaX_O3oA&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=67)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 68
>
> [![img](https://i.ytimg.com/vi/zlHowI7ClOk/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLAq8Xm5UDNCbMPmWibuPLUkUE6MzQ)16:51TOCANDO AGORA](https://www.youtube.com/watch?v=zlHowI7ClOk&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=68)
>
> ### [Tag section - Curso de HTML Completo e Profissional #68](https://www.youtube.com/watch?v=zlHowI7ClOk&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=68)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 69
>
> [![img](https://i.ytimg.com/vi/MpKV8WPNx0k/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLCEMObGWYr8qR3kJ-2zrxbd7S_sdQ)8:36TOCANDO AGORA](https://www.youtube.com/watch?v=MpKV8WPNx0k&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=69)
>
> ### [Tag small - Curso de HTML Completo e Profissional #69](https://www.youtube.com/watch?v=MpKV8WPNx0k&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=69)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 70
>
> [![img](https://i.ytimg.com/vi/zcMjUExEKm8/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLD-khvxDH4M0kGg7ZfKi9GdHggnDw)7:30TOCANDO AGORA](https://www.youtube.com/watch?v=zcMjUExEKm8&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=70)
>
> ### [Tag source - Curso de HTML Completo e Profissional #70](https://www.youtube.com/watch?v=zcMjUExEKm8&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=70)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 71
>
> [![img](https://i.ytimg.com/vi/mLgvFdBLlkI/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLCOkXLc-omR18ZsvBvKDI_EjiX3OQ)8:13TOCANDO AGORA](https://www.youtube.com/watch?v=mLgvFdBLlkI&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=71)
>
> ### [Tag span - Curso de HTML Completo e Profissional #71](https://www.youtube.com/watch?v=mLgvFdBLlkI&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=71)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 72
>
> [![img](https://i.ytimg.com/vi/yrb4OPk_Xtw/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLDGbD3pqwhZ8LxgktbjUOCMp_Yveg)5:52TOCANDO AGORA](https://www.youtube.com/watch?v=yrb4OPk_Xtw&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=72)
>
> ### [Tag strong - Curso de HTML Completo e Profissional #72](https://www.youtube.com/watch?v=yrb4OPk_Xtw&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=72)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 73
>
> [![img](https://i.ytimg.com/vi/aukKlJ_zGE4/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLAQZZUgiDrxppd9Q1cvF9ywQcoFxw)5:48TOCANDO AGORA](https://www.youtube.com/watch?v=aukKlJ_zGE4&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=73)
>
> ### [Tag style - Curso de HTML Completo e Profissional #73](https://www.youtube.com/watch?v=aukKlJ_zGE4&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=73)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 74
>
> [![img](https://i.ytimg.com/vi/wsoCjazzU9Q/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLB9XVRx6ennlH0cGoe7gTlwXtK6Kg)4:00TOCANDO AGORA](https://www.youtube.com/watch?v=wsoCjazzU9Q&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=74)
>
> ### [Tags sup e sub (subscrito e sobrescrito) - Curso de HTML Completo e Profissional #74](https://www.youtube.com/watch?v=wsoCjazzU9Q&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=74)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 75
>
> [![img](https://i.ytimg.com/vi/oSQfzjl110k/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLCbJvmorLC5WS0miVice8nenPf0Rg)9:35TOCANDO AGORA](https://www.youtube.com/watch?v=oSQfzjl110k&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=75)
>
> ### [Como criar tabelas em HTML P1 (table, tr, td) - Curso de HTML Completo e Profissional #75](https://www.youtube.com/watch?v=oSQfzjl110k&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=75)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 76
>
> [![img](https://i.ytimg.com/vi/DN7nGC4mxbM/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLBY78bfLJNo03OCg3B0eDWY87P1YQ)8:45TOCANDO AGORA](https://www.youtube.com/watch?v=DN7nGC4mxbM&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=76)
>
> ### [Tabelas html, mesclando células (colspan e rowspan) - Curso de HTML Completo e Profissional #76](https://www.youtube.com/watch?v=DN7nGC4mxbM&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=76)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 77
>
> [![img](https://i.ytimg.com/vi/FBSVT_IJ2rA/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLDKIHFDbxvnvfMTPAOM1v-8mzIL4A)7:04TOCANDO AGORA](https://www.youtube.com/watch?v=FBSVT_IJ2rA&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=77)
>
> ### [Tabelas html, thead, tbody e tfoot - Curso de HTML Completo e Profissional #77](https://www.youtube.com/watch?v=FBSVT_IJ2rA&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=77)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 78
>
> [![img](https://i.ytimg.com/vi/kdVw5kciSAQ/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLCWbFWNDPz6e-m9mRRQiobqonxepA)6:23TOCANDO AGORA](https://www.youtube.com/watch?v=kdVw5kciSAQ&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=78)
>
> ### [Formatando tabela com CSS - Curso de HTML Completo e Profissional #78](https://www.youtube.com/watch?v=kdVw5kciSAQ&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=78)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 79
>
> [![img](https://i.ytimg.com/vi/dWqAWnJscfU/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLCQtMfZs3M7H2PCZlV_IiNhPKFG5A)6:55TOCANDO AGORA](https://www.youtube.com/watch?v=dWqAWnJscfU&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=79)
>
> ### [Tag Time - Curso de HTML Completo e Profissional #79](https://www.youtube.com/watch?v=dWqAWnJscfU&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=79)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 80
>
> [![img](https://i.ytimg.com/vi/pvPjFWVb32w/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLDDg8OKAF7QeX-zSpI_6a3E4JXN4w)4:12TOCANDO AGORA](https://www.youtube.com/watch?v=pvPjFWVb32w&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=80)
>
> ### [Tag Title - Curso de HTML Completo e Profissional #80](https://www.youtube.com/watch?v=pvPjFWVb32w&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=80)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 81
>
> [![img](https://i.ytimg.com/vi/CpohuQXyUmU/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLAh_V2acLb9iqfI8WB07Ljj-dQ8BA)6:26TOCANDO AGORA](https://www.youtube.com/watch?v=CpohuQXyUmU&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=81)
>
> ### [Tag ul - Lista não ordenada - Curso de HTML Completo e Profissional #81](https://www.youtube.com/watch?v=CpohuQXyUmU&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=81)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 82
>
> [![img](https://i.ytimg.com/vi/QuFmI3WvAAI/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLD414F24CKuwGcuul6Ou2usL3RTuQ)4:15TOCANDO AGORA](https://www.youtube.com/watch?v=QuFmI3WvAAI&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=82)
>
> ### [Tag var - Lista não ordenada - Curso de HTML Completo e Profissional #82](https://www.youtube.com/watch?v=QuFmI3WvAAI&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=82)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 83
>
> [![img](https://i.ytimg.com/vi/f28Tql1sbXs/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLBJNEEDl40IFeUbnP5ZKy9ScTdhHQ)7:57TOCANDO AGORA](https://www.youtube.com/watch?v=f28Tql1sbXs&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=83)
>
> ### [Tag video - Curso de HTML Completo e Profissional #83](https://www.youtube.com/watch?v=f28Tql1sbXs&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=83)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 84
>
> [![img](https://i.ytimg.com/vi/Cc2zuHN6pVY/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLB_xwhx5lus51nySZ-LbyY5dfs4pA)12:13TOCANDO AGORA](https://www.youtube.com/watch?v=Cc2zuHN6pVY&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=84)
>
> ### [Construindo página com layout FULL PAGE #P1 - Curso de HTML Completo e Profissional #84](https://www.youtube.com/watch?v=Cc2zuHN6pVY&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=84)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 85
>
> [![img](https://i.ytimg.com/vi/1SK10vYFIS4/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLCl4N-p9D1uhzmFOUaVzKYtKP-gLg)13:11TOCANDO AGORA](https://www.youtube.com/watch?v=1SK10vYFIS4&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=85)
>
> ### [Construindo página com layout FULL PAGE #P2 - Curso de HTML Completo e Profissional #85](https://www.youtube.com/watch?v=1SK10vYFIS4&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=85)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 86
>
> [![img](https://i.ytimg.com/vi/liiuwrA_YpE/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLCghfIAxPKWdHAZrZRSgCRLbTJnTg)11:29TOCANDO AGORA](https://www.youtube.com/watch?v=liiuwrA_YpE&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=86)
>
> ### [Construindo página com layout FULL PAGE #P3 - Curso de HTML Completo e Profissional #86](https://www.youtube.com/watch?v=liiuwrA_YpE&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=86)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 87
>
> [![img](https://i.ytimg.com/vi/gUFLtDUPyVY/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLAtiOSSx8ogix8B5AS4kxSYqmi1_Q)10:30TOCANDO AGORA](https://www.youtube.com/watch?v=gUFLtDUPyVY&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=87)
>
> ### [Construindo página com layout FULL PAGE #P4 - Curso de HTML Completo e Profissional #87](https://www.youtube.com/watch?v=gUFLtDUPyVY&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=87)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 88
>
> [![img](https://i.ytimg.com/vi/HSWf5YW3WOI/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLCbSRknfRxI9aVz0f3tyvCmSznKXA)19:44TOCANDO AGORA](https://www.youtube.com/watch?v=HSWf5YW3WOI&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=88)
>
> ### [Animação ao Scroll / Página com layout FULL PAGE #P5 - Curso de HTML Completo e Profissional #88](https://www.youtube.com/watch?v=HSWf5YW3WOI&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=88)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 89
>
> [![img](https://i.ytimg.com/vi/zz7kbHhy56E/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLCkLd5f7-GJrGOWZNdfl2OzqZGEAg)12:18TOCANDO AGORA](https://www.youtube.com/watch?v=zz7kbHhy56E&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=89)
>
> ### [Efeito Parallax / Página com layout FULL PAGE #P6 - Curso de HTML Completo e Profissional #89](https://www.youtube.com/watch?v=zz7kbHhy56E&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=89)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 90
>
> [![img](https://i.ytimg.com/vi/aO-8M7EUuoM/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLCqO60Tvfi2P1W2DxLsg3FOR8aSYQ)13:03TOCANDO AGORA](https://www.youtube.com/watch?v=aO-8M7EUuoM&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=90)
>
> ### [Janela Modal / Página com layout FULL PAGE #P7 - Curso de HTML Completo e Profissional #90](https://www.youtube.com/watch?v=aO-8M7EUuoM&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=90)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 91
>
> [![img](https://i.ytimg.com/vi/eXH-hV80bW8/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLCr1gRIkq2RUGBiZdrsIACIBmGQSg)11:12TOCANDO AGORA](https://www.youtube.com/watch?v=eXH-hV80bW8&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=91)
>
> ### [Janela Modal P2 / Página com layout FULL PAGE #P8 - Curso de HTML Completo e Profissional #91](https://www.youtube.com/watch?v=eXH-hV80bW8&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=91)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 92
>
> [![img](https://i.ytimg.com/vi/gMNM5sirktI/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLCGQ1s8Ood7RHeVrX3IcvllRCZNtw)10:29TOCANDO AGORA](https://www.youtube.com/watch?v=gMNM5sirktI&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=92)
>
> ### [Janela Modal P3 / Página com layout FULL PAGE #P8 - Curso de HTML Completo e Profissional #92](https://www.youtube.com/watch?v=gMNM5sirktI&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=92)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 93
>
> [![img](https://i.ytimg.com/vi/ZiMLFwkn80c/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLAuVPzKhC51hrrjpYmIA2Z8hOdUpA)17:18TOCANDO AGORA](https://www.youtube.com/watch?v=ZiMLFwkn80c&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=93)
>
> ### [Menu de ícones fixo - Curso de HTML Completo e Profissional #93](https://www.youtube.com/watch?v=ZiMLFwkn80c&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=93)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 94
>
> [![img](https://i.ytimg.com/vi/fie4E27WRI4/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLDzcvU_snwAEvTeqAZ8WPuGbdVt8Q)13:17TOCANDO AGORA](https://www.youtube.com/watch?v=fie4E27WRI4&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=94)
>
> ### [Menu de ícones Retrátil - Curso de HTML Completo e Profissional #94](https://www.youtube.com/watch?v=fie4E27WRI4&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=94)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 95
>
> [![img](https://i.ytimg.com/vi/9RdKlESSqr0/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLB8PrJbarXis1QymhPGe5yih-Jt2Q)17:51TOCANDO AGORA](https://www.youtube.com/watch?v=9RdKlESSqr0&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=95)
>
> ### [Acordeon - Curso de HTML Completo e Profissional #95](https://www.youtube.com/watch?v=9RdKlESSqr0&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=95)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 96
>
> [![img](https://i.ytimg.com/vi/GYPgm4UUdHg/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLDkVU0I4VgiKurFRbKKQ-ZvWrcoNQ)18:45TOCANDO AGORA](https://www.youtube.com/watch?v=GYPgm4UUdHg&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=96)
>
> ### [Seção de guias/tabs P1 - Curso de HTML Completo e Profissional #96](https://www.youtube.com/watch?v=GYPgm4UUdHg&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=96)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 97
>
> [![img](https://i.ytimg.com/vi/BGlbdATqPOY/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLCQOoFafBLJG7qQLgeHaL6CVAV-pg)13:54TOCANDO AGORA](https://www.youtube.com/watch?v=BGlbdATqPOY&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=97)
>
> ### [Seção de guias/tabs P2 - Curso de HTML Completo e Profissional #97](https://www.youtube.com/watch?v=BGlbdATqPOY&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=97)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 98
>
> [![img](https://i.ytimg.com/vi/WRlVc8CI3bg/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLDfV56x6sFpT5dg2NO3RXlczw06QQ)25:39TOCANDO AGORA](https://www.youtube.com/watch?v=WRlVc8CI3bg&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=98)
>
> ### [Menu com pesquisa interna - Curso de HTML Completo e Profissional #98](https://www.youtube.com/watch?v=WRlVc8CI3bg&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=98)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 99
>
> [![img](https://i.ytimg.com/vi/0TMzDr9fHGg/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLCkZxjY0eUN-LHRf50ggsc1wK6hcg)20:36TOCANDO AGORA](https://www.youtube.com/watch?v=0TMzDr9fHGg&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=99)
>
> ### [Menu lateral oculto interativo - Curso de HTML Completo e Profissional #99](https://www.youtube.com/watch?v=0TMzDr9fHGg&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=99)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 100
>
> [![img](https://i.ytimg.com/vi/kKpiQKW8VFk/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLCpaDNxUSlEdhM1HNKD-0WN9S2Y8Q)18:38TOCANDO AGORA](https://www.youtube.com/watch?v=kKpiQKW8VFk&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=100)
>
> ### [Header auto ajustável - Curso de HTML Completo e Profissional #100](https://www.youtube.com/watch?v=kKpiQKW8VFk&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=100)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 101
>
> [![img](https://i.ytimg.com/vi/voyMlme00YA/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLCZG2q5Rv-b9DUh-6K_WqNYLu7FCg)8:27TOCANDO AGORA](https://www.youtube.com/watch?v=voyMlme00YA&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=101)
>
> ### [Menu de abas laterais interativo - Curso de HTML Completo e Profissional #101](https://www.youtube.com/watch?v=voyMlme00YA&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=101)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 102
>
> [![img](https://i.ytimg.com/vi/oAjhMC5gtHs/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLA4YxObF4ai4Rd3UsGZaJ4rGYg2DA)17:45TOCANDO AGORA](https://www.youtube.com/watch?v=oAjhMC5gtHs&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=102)
>
> ### [Menu rolante que fixa no topo - Curso de HTML Completo e Profissional #102](https://www.youtube.com/watch?v=oAjhMC5gtHs&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=102)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 103
>
> [![img](https://i.ytimg.com/vi/jh_UtQAsScE/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLBSbi-_dpnqj_KZcrRilm8hJrsYdQ)19:09TOCANDO AGORA](https://www.youtube.com/watch?v=jh_UtQAsScE&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=103)
>
> ### [Menu estilo Mobile - Curso de HTML Completo e Profissional #103](https://www.youtube.com/watch?v=jh_UtQAsScE&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=103)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 104
>
> [![img](https://i.ytimg.com/vi/O0rVf8ziCMc/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLCVmkzbuIFm_j0q8iTsGQ1Sn6o4xQ)19:31TOCANDO AGORA](https://www.youtube.com/watch?v=O0rVf8ziCMc&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=104)
>
> ### [Menu DropDown - Curso de HTML Completo e Profissional #104](https://www.youtube.com/watch?v=O0rVf8ziCMc&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=104)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 105
>
> [![img](https://i.ytimg.com/vi/twKBvTbhGDo/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLAmxfMICt3Jz8sk_ECoWYnK9SvyAg)21:26TOCANDO AGORA](https://www.youtube.com/watch?v=twKBvTbhGDo&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=105)
>
> ### [Slideshow #p1 - Curso de HTML Completo e Profissional #105](https://www.youtube.com/watch?v=twKBvTbhGDo&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=105)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 106
>
> [![img](https://i.ytimg.com/vi/2nbhEu3rcBM/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLBvRvvAdZkx7IivGQ3BLAmVNRLCPQ)16:00TOCANDO AGORA](https://www.youtube.com/watch?v=2nbhEu3rcBM&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=106)
>
> ### [Slideshow #p2 - Curso de HTML Completo e Profissional #106](https://www.youtube.com/watch?v=2nbhEu3rcBM&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=106)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 107
>
> [![img](https://i.ytimg.com/vi/kU4DZtOAL8Y/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLCDTEn1CpDwlwpL40rH5DdFBOlP6Q)18:17TOCANDO AGORA](https://www.youtube.com/watch?v=kU4DZtOAL8Y&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=107)
>
> ### [Slideshow #p3 - Curso de HTML Completo e Profissional #107](https://www.youtube.com/watch?v=kU4DZtOAL8Y&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=107)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 108
>
> [![img](https://i.ytimg.com/vi/nXf99HnwMbg/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLDlVZPoYaewBzirZtw8vIGVgo6lmw)21:06TOCANDO AGORA](https://www.youtube.com/watch?v=nXf99HnwMbg&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=108)
>
> ### [Galeria de imagens - Curso de HTML Completo e Profissional #108](https://www.youtube.com/watch?v=nXf99HnwMbg&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=108)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 109
>
> [![img](https://i.ytimg.com/vi/AVUvd0iu97c/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLAXAEDh_Q9gaklGzqG5QDaHZN9R1g)12:00TOCANDO AGORA](https://www.youtube.com/watch?v=AVUvd0iu97c&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=109)
>
> ### [Sobreposição de imagens - Curso de HTML Completo e Profissional #109](https://www.youtube.com/watch?v=AVUvd0iu97c&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=109)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 110
>
> [![img](https://i.ytimg.com/vi/gfkuOxin_gU/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLAAwpjeyMGXL2uYM2dNmVCfH0zcXA)17:04TOCANDO AGORA](https://www.youtube.com/watch?v=gfkuOxin_gU&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=110)
>
> ### [Aplicando filtros em imagens - Curso de HTML Completo e Profissional #110](https://www.youtube.com/watch?v=gfkuOxin_gU&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=110)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 111
>
> [![img](https://i.ytimg.com/vi/66SY-HpgS_0/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLBibzpwYGsOnjnp5K2H9RaufJwBXw)13:03TOCANDO AGORA](https://www.youtube.com/watch?v=66SY-HpgS_0&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=111)
>
> ### [Caixas de texto sobre imagens - Curso de HTML Completo e Profissional #111](https://www.youtube.com/watch?v=66SY-HpgS_0&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=111)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 112
>
> [![img](https://i.ytimg.com/vi/8OgQEexT2ps/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLAQykR1Z03pHAfvjq7f27gA_8Y4Dw)7:14TOCANDO AGORA](https://www.youtube.com/watch?v=8OgQEexT2ps&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=112)
>
> ### [Imagem de fundo (background) FullPage - Curso de HTML Completo e Profissional #112](https://www.youtube.com/watch?v=8OgQEexT2ps&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=112)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 113
>
> [![img](https://i.ytimg.com/vi/umZXDFnCH0Q/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLCaTqYrq_FLkU-q67ME1ldjkRcItg)5:35TOCANDO AGORA](https://www.youtube.com/watch?v=umZXDFnCH0Q&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=113)
>
> ### [Arredondando imagens - Curso de HTML Completo e Profissional #113](https://www.youtube.com/watch?v=umZXDFnCH0Q&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=113)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 114
>
> [![img](https://i.ytimg.com/vi/mgm0BREVigc/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLBApPIrKvItwK2squJi7yKfi4uiTg)22:03TOCANDO AGORA](https://www.youtube.com/watch?v=mgm0BREVigc&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=114)
>
> ### [Cartões digitais - Curso de HTML Completo e Profissional #114](https://www.youtube.com/watch?v=mgm0BREVigc&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=114)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 115
>
> [![img](https://i.ytimg.com/vi/xqKemLTpff8/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLB4fZBevjzj-UMkTF4-7xjWVkJzEQ)8:24TOCANDO AGORA](https://www.youtube.com/watch?v=xqKemLTpff8&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=115)
>
> ### [Efeito Shake / Tremida / Terremoto - Curso de HTML Completo e Profissional #115](https://www.youtube.com/watch?v=xqKemLTpff8&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=115)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 116
>
> [![img](https://i.ytimg.com/vi/A4uUiqlqR1U/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLDGLFFvk8zet5J-kjKDmx2UD1PjfA)22:08TOCANDO AGORA](https://www.youtube.com/watch?v=A4uUiqlqR1U&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=116)
>
> ### [Galeria de imagens filtrável - Curso de HTML Completo e Profissional #116](https://www.youtube.com/watch?v=A4uUiqlqR1U&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=116)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 117
>
> [![img](https://i.ytimg.com/vi/04RM3mETpKo/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLABmw7jXqfcg3znFr16VF0vIHnyoA)11:24TOCANDO AGORA](https://www.youtube.com/watch?v=04RM3mETpKo&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=117)
>
> ### [Botão com animação - Curso de HTML Completo e Profissional #117](https://www.youtube.com/watch?v=04RM3mETpKo&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=117)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 118
>
> [![img](https://i.ytimg.com/vi/yafiQy7XHeM/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLCp4ZsBv1e_HI08bEehq3Y3FdPn8g)9:52TOCANDO AGORA](https://www.youtube.com/watch?v=yafiQy7XHeM&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=118)
>
> ### [Expandir e Retrair texto/ botão leia mais - Curso de HTML Completo e Profissional #118](https://www.youtube.com/watch?v=yafiQy7XHeM&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=118)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 119
>
> [![img](https://i.ytimg.com/vi/TP08cLjFBsA/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLAK6sUxU2d0DTfXAB6pI9P96dsruA)7:55TOCANDO AGORA](https://www.youtube.com/watch?v=TP08cLjFBsA&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=119)
>
> ### [Alerta tecla CapsLock - Curso de HTML Completo e Profissional #119](https://www.youtube.com/watch?v=TP08cLjFBsA&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=119)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 120
>
> [![img](https://i.ytimg.com/vi/DR-jyJTIB2E/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLAc6VBMp5y3trrp4bUs9hzZ50Th_A)5:18TOCANDO AGORA](https://www.youtube.com/watch?v=DR-jyJTIB2E&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=120)
>
> ### [Mostrar/Ocultar senha - Curso de HTML Completo e Profissional #120](https://www.youtube.com/watch?v=DR-jyJTIB2E&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=120)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 121
>
> [![img](https://i.ytimg.com/vi/AGFtQPDre_U/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLA7C8fEolMbIBornvm85IOrYvUrfA)15:18TOCANDO AGORA](https://www.youtube.com/watch?v=AGFtQPDre_U&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=121)
>
> ### [Background animado - Curso de HTML Completo e Profissional #121](https://www.youtube.com/watch?v=AGFtQPDre_U&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=121)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 122
>
> [![img](https://i.ytimg.com/vi/YKHTY1pSF-M/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLCkfvmNGSSNUtuPf3ie_qnZ12A1FQ)5:10TOCANDO AGORA](https://www.youtube.com/watch?v=YKHTY1pSF-M&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=122)
>
> ### [Rolagem suave da página - Curso de HTML Completo e Profissional #122](https://www.youtube.com/watch?v=YKHTY1pSF-M&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=122)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 123
>
> [![img](https://i.ytimg.com/vi/P0S0JHAb3DY/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLAEBRHvcEnPetQlguM8qNf-udjtLw)7:14TOCANDO AGORA](https://www.youtube.com/watch?v=P0S0JHAb3DY&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=123)
>
> ### [Barra de rolagem personalizada - Curso de HTML Completo e Profissional #123](https://www.youtube.com/watch?v=P0S0JHAb3DY&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=123)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 124
>
> [![img](https://i.ytimg.com/vi/XIZqeTZoE-A/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLDNqi_cpuSU-ViYBBnJt1cA9crCFw)11:54TOCANDO AGORA](https://www.youtube.com/watch?v=XIZqeTZoE-A&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=124)
>
> ### [Efeito Digitação de Texto - Curso de HTML Completo e Profissional #124](https://www.youtube.com/watch?v=XIZqeTZoE-A&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=124)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 125
>
> [![img](https://i.ytimg.com/vi/LQpxDIBPDMA/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLDVONAE-xDjelBocEN0s_NWXT-SZQ)17:40TOCANDO AGORA](https://www.youtube.com/watch?v=LQpxDIBPDMA&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=125)
>
> ### [Introdução ao Canvas HTML e Javascript [Canvas\] - Curso de Canvas - Aula 01](https://www.youtube.com/watch?v=LQpxDIBPDMA&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=125)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 126
>
> [![img](https://i.ytimg.com/vi/ARhhsJeZxlw/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLDYGCIaIsLikl5QoY8OfHk6fQjb_Q)12:23TOCANDO AGORA](https://www.youtube.com/watch?v=ARhhsJeZxlw&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=126)
>
> ### [Aprendendo sobre rect, clearRect e fillRect [Canvas\] - Curso de Canvas - Aula 02](https://www.youtube.com/watch?v=ARhhsJeZxlw&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=126)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 127
>
> [![img](https://i.ytimg.com/vi/IZzNQqF1_oc/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLCyYpiWE1u3fV-B5rz_QEjCfKhpxw)9:05TOCANDO AGORA](https://www.youtube.com/watch?v=IZzNQqF1_oc&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=127)
>
> ### [Desenhando linhas no Canvas [Canvas\] - Curso de Canvas - Aula 03](https://www.youtube.com/watch?v=IZzNQqF1_oc&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=127)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 128
>
> [![img](https://i.ytimg.com/vi/7Kcnk9J8APA/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLBauHOEr4C_1uBICliSNHv_fol_XQ)11:50TOCANDO AGORA](https://www.youtube.com/watch?v=7Kcnk9J8APA&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=128)
>
> ### [Movimentar elementos por programação #P1 [Canvas\] - Curso de Canvas - Aula 04](https://www.youtube.com/watch?v=7Kcnk9J8APA&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=128)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 129
>
> [![img](https://i.ytimg.com/vi/GNJJJSEJb5o/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLDsrL8G-ksgo-oaWiQckTBT9kyo5Q)14:23TOCANDO AGORA](https://www.youtube.com/watch?v=GNJJJSEJb5o&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=129)
>
> ### [Movimentar elementos por programação #P2 [Canvas\] - Curso de Canvas - Aula 05](https://www.youtube.com/watch?v=GNJJJSEJb5o&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=129)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 130
>
> [![img](https://i.ytimg.com/vi/jbJjPUXycIQ/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLASbTeBOx5fxwpIcI8qxL-JSsyQiA)11:40TOCANDO AGORA](https://www.youtube.com/watch?v=jbJjPUXycIQ&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=130)
>
> ### [Movimentar elementos por programação #P3 - Aula Com desafio [Canvas\] - Curso de Canvas - Aula 06](https://www.youtube.com/watch?v=jbJjPUXycIQ&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=130)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 131
>
> [![img](https://i.ytimg.com/vi/rKoqSot8ga0/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLD9BEKN4E8BF8D8KYZnMEK9xdSFZQ)9:47TOCANDO AGORA](https://www.youtube.com/watch?v=rKoqSot8ga0&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=131)
>
> ### [Desenhando arcos e círculos com a Função ARC do canvas [Canvas\] - Curso de Canvas - Aula 07](https://www.youtube.com/watch?v=rKoqSot8ga0&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=131)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 132
>
> [![img](https://i.ytimg.com/vi/gQnrAc8tXBk/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLDbcAg5WY4Pos7wj_NVffY8Zf_IGA)13:26TOCANDO AGORA](https://www.youtube.com/watch?v=gQnrAc8tXBk&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=132)
>
> ### [Desenhando e Animando circulos com a função ARC do canvas #P2 [Canvas\] - Curso de Canvas - Aula 08](https://www.youtube.com/watch?v=gQnrAc8tXBk&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=132)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 133
>
> [![img](https://i.ytimg.com/vi/bFbBSw7ZytI/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLCN7iZlDbTPUh1TDnEhVoALveo53w)16:36TOCANDO AGORA](https://www.youtube.com/watch?v=bFbBSw7ZytI&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=133)
>
> ### [Entendendo a função arcTo do canvas [Canvas\] - Curso de Canvas - Aula 09](https://www.youtube.com/watch?v=bFbBSw7ZytI&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=133)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 134
>
> [![img](https://i.ytimg.com/vi/nj_ZciB6bM0/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLChKH5dLoQoTB68eF2i7BukBSLaHg)18:28TOCANDO AGORA](https://www.youtube.com/watch?v=nj_ZciB6bM0&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=134)
>
> ### [Aprenda como inserir imagens no canvas [Canvas\] - Curso de Canvas - Aula 10](https://www.youtube.com/watch?v=nj_ZciB6bM0&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=134)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 135
>
> [![img](https://i.ytimg.com/vi/7AQDKNDzdqo/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLBXMjO7P4LbowtB5gUA6tC2Js1E8g)16:43TOCANDO AGORA](https://www.youtube.com/watch?v=7AQDKNDzdqo&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=135)
>
> ### [Sprite Sheet em canvas [Canvas\] - Curso de Canvas - Aula 11](https://www.youtube.com/watch?v=7AQDKNDzdqo&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=135)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 136
>
> [![img](https://i.ytimg.com/vi/h7WZRsZWk5c/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLC8VrWMr9Vl4_CComhT5kq6AdogNw)6:52TOCANDO AGORA](https://www.youtube.com/watch?v=h7WZRsZWk5c&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=136)
>
> ### [Movendo imagens no canvas pelo teclado [Canvas\] - Curso de Canvas - Aula 12](https://www.youtube.com/watch?v=h7WZRsZWk5c&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=136)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 137
>
> [![img](https://i.ytimg.com/vi/qOa9nS828H4/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLDO92WwiIJKH2sFCJtoulA6fkt4uw)8:53TOCANDO AGORA](https://www.youtube.com/watch?v=qOa9nS828H4&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=137)
>
> ### [Movendo imagens no canvas pelo teclado #P2 [Canvas\] - Curso de Canvas - Aula 13](https://www.youtube.com/watch?v=qOa9nS828H4&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=137)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 138
>
> [![img](https://i.ytimg.com/vi/5z5PVjVcfDs/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLDvlSgpxilYqpx9KNdcu7G58dWvEg)15:19TOCANDO AGORA](https://www.youtube.com/watch?v=5z5PVjVcfDs&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=138)
>
> ### [Movendo imagens no canvas pelo teclado usando classes #P3 [Canvas\] - Curso de Canvas - Aula 14](https://www.youtube.com/watch?v=5z5PVjVcfDs&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=138)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)
>
> 
>
> 
>
> 139
>
> [![img](https://i.ytimg.com/vi/f09i0FYXPf0/hqdefault.jpg?sqp=-oaymwEbCKgBEF5IVfKriqkDDggBFQAAiEIYAXABwAEG&rs=AOn4CLBcZnyLl55Je8vhswDfAIL27LH8Bg)12:04TOCANDO AGORA](https://www.youtube.com/watch?v=f09i0FYXPf0&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=139)
>
> ### [Movendo imagens no canvas pelo teclado usando classes #P4 [Canvas\] - Curso de Canvas - Aula 15](https://www.youtube.com/watch?v=f09i0FYXPf0&list=PLx4x_zx8csUiVHRDO_7qhOaeNrrQ5uU8c&index=139)
>
> [CFBCursos](https://www.youtube.com/c/cfbcursos)

