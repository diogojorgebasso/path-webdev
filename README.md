# A path to making great web development.
This repository brings together links, ideas, and excerpts of code. All of this, for you to be more confident in your Webdev creation!

# FrontEnd

Design References:

https://www.behance.net/

https://www.coroflot.com/


Free photographies:

https://unsplash.com/

https://br.freepik.com/

https://pixabay.com/pt/


Vector elements(SVG):

https://pt.vecteezy.com/

https://www.flaticon.com/


Stopwatch of text to audio:

https://oigoaudio.com/cronometro/


Free music:

https://www.youtube.com/audiolibrary/music


Typographys:

https://fonts.google.com/



## Ecommerce
* Add a review and ratings system under the price; at the top of the page.
* One-click ordering.
* Mobile-friendly
1. [https://github.com/kamens/jQuery-menu-aim](Amazon's Menu style) – great UX.

## SEO
1. [https://outspokenmedia.com/international-seo-strategy/](decide to translate the website by a ccTLD or with subdomains)

## Learning
### CSS
4. [https://flexboxfroggy.com](FlexBox)
5. [https://frontendchecklist.io/](FrontEnd checklist): when making a front end Job, don't forget to check if everything is in order.

# Backend

## Node.Js

### CONCEPTS
MVC - MODEL VIEW CONTROLLER (ARQUITETURA DO PROJETO)

Como criar aplicativos com node: sanando a parte mais chata!---
criar pasta central chamada src e então, subpastas com o nome de: config, controller, middlewares, model, routes.
Na config, um arquivo chamado database.js para fazer a ligação com ele: mongo, firebase e afins.
Na model, um arquivo chamado (feature do app)Model.js que crie o Schema (SQUEMA) de quais informações serão coletadas pelo app, macadress, nome, descrições e afins. 
Na controller, um arquivo chamado (feature do app)Controller.js que possua o modelo importanto, portanto, "require('../model/Model')" e a classe que conterá as rotas para essa mesma feature : criar, atualizar, deletar, filtros e etc.
Salienta que as funções são assincronas e o que ela almeja pegar no servidor tem "await", ou seja, ele espera pegar e devolver no servidor para não dar problema de renderização.
(GET é sempre usando como parametro)
No middlwerase, será colocado qualquer validação que deverá ser feita: checagem se houve a passagem de informação, checagem de número de telefone e afins.
No routes, será colocado as rotas propriamente dito. Cria um arquivo chamado (feauture do app)Routes.js onde ele requere o controller e as validações. Além disso, coloca-se as rotas
por meio da sehguinte estrutura: router.post/get/delete('/algumacoisa/algumacoisa/', validação(se houver), (feauture do app)Controller.nomedafuncao)

## Django
