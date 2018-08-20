# Sistema de Pedidos / Front-End

## Sinopse

Front-end aplicativo para venda de produtos (PDV). Veja também o [Back-end](https://github.com/diegobiazin/spring-boot-ionic-backend).

Projeto utilizando Ionic, arquitetura MVC do Angular, componentes visuais do Ionic, Angular reactive forms, interceptors, local storage,
tratamento de erros, paginação com infinite scroll, loading e refresher, navegação.
Aplicativo possui consumo de API REST, tela de login, cadastro de usuário, fluxo completo de navegação de carrinho de compras,
fluxo de fechamento de pedido, tela de perfil de usuário com envio de foto tanto pela câmera quanto pela galeria.

## Tecnologias e Frameworks
* Ionic 3
* Angular 5
* Cordova

## Estrutura de camadas 
![alt text](https://s3-sa-east-1.amazonaws.com/biazin-curso-spring-ionic/front-end.png)

```sh
|   index.html
|   manifest.json
|   service-worker.js
|
+---app
|       app.component.ts
|       app.html
|       app.module.ts
|       app.scss
|       main.ts
|
+---assets
|   +---icon
|   |       favicon.ico
|   |
|   \---imgs
|           avatar-blank.png
|           logo.png
|           prod.jpg
|           tela-inicial.png
|
+---config
|       api.config.ts
|       storage_keys.config.ts
|
+---interceptors
|       auth-interceptor.ts
|       error-interceptor.ts
|
+---models
|       cart-item.ts
|       cart.ts
|       categoria.dto.ts
|       cidade.dto.ts
|       cliente.dto.ts
|       credenciais.dto.ts
|       endereco.dto.ts
|       estado.dto.ts
|       fieldmessage.ts
|       item-pedido.dto.ts
|       local_user.ts
|       pagamento.dto.ts
|       pedido.dto.ts
|       produto.dto.ts
|       ref.dto.ts
|
+---pages
|   +---cart
|   |       cart.html
|   |       cart.module.ts
|   |       cart.scss
|   |       cart.ts
|   |
|   +---categorias
|   |       categorias.html
|   |       categorias.module.ts
|   |       categorias.scss
|   |       categorias.ts
|   |
|   +---home
|   |       home.html
|   |       home.module.ts
|   |       home.scss
|   |       home.ts
|   |
|   +---order-confirmation
|   |       order-confirmation.html
|   |       order-confirmation.module.ts
|   |       order-confirmation.scss
|   |       order-confirmation.ts
|   |
|   +---payment
|   |       payment.html
|   |       payment.module.ts
|   |       payment.scss
|   |       payment.ts
|   |
|   +---pick-address
|   |       pick-address.html
|   |       pick-address.module.ts
|   |       pick-address.scss
|   |       pick-address.ts
|   |
|   +---produto-detail
|   |       produto-detail.html
|   |       produto-detail.module.ts
|   |       produto-detail.scss
|   |       produto-detail.ts
|   |
|   +---produtos
|   |       produtos.html
|   |       produtos.module.ts
|   |       produtos.scss
|   |       produtos.ts
|   |
|   +---profile
|   |       profile.html
|   |       profile.module.ts
|   |       profile.scss
|   |       profile.ts
|   |
|   \---signup
|           signup.html
|           signup.module.ts
|           signup.scss
|           signup.ts
|
+---services
   |   auth.service.ts
   |   image-util.service.ts
   |   storage.service.ts
   |
   \---domain
           cart.service.ts
           categoria.service.ts
           cidade.service.ts
           cliente.service.ts
           estado.service.ts
           pedido.service.ts
           produto.service.ts


```

## Autor

* **[Diego Biazin](https://github.com/diegobiazin)** - *Sistema de Pedidos / Front-End* 
