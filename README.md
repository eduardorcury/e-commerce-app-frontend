<p align="center">
  <img width="100" height="100" src="https://github.com/eduardorcury/curso-spring-ionic-frontend/blob/master/resources/ionic.png">
</p>

# Aplicativo mobile de E-Commerce

> Aplicativo Android/iOS para compra de produtos criado com Ionic e Typescript. 
Backend da aplicação disponível [aqui](https://github.com/eduardorcury/e-commerce-app-backend).

## :wrench: &nbsp;&nbsp; Ferramentas utilizadas

- [Ionic Framework](https://github.com/ionic-team/ionic).
- [Typescript](https://github.com/Microsoft/TypeScript).
- [Cordova](https://github.com/apache/cordova) para acesso aos recursos nativos.

## :bulb: &nbsp;&nbsp; Funcionalidades

### Login e cadastro de usuários

Login de usuários com Autorização e Autenticação feita pelo [backend](https://github.com/eduardorcury/spring-boot-ionic-backend).
Criação de novos usuários a partir do preenchimento dos dados em um formulário, com armazenamento do usuário no banco de dados.

<p align="center">
  <img width="300" height="520" src="https://github.com/eduardorcury/e-commerce-app-frontend/blob/master/resources/screenshots/Login.png">
</p>
<p align="center">
  <img width="300" height="520" src="https://github.com/eduardorcury/e-commerce-app-frontend/blob/master/resources/screenshots/Cadastro%201.png">
  <img width="300" height="520" src="https://github.com/eduardorcury/e-commerce-app-frontend/blob/master/resources/screenshots/Cadastro%202.png">
</p>

### Página de categorias

Lista de categorias com imagems individuais armazenadas no serviço Amazon S3. Cada categoria leva à página de produtos, contendo todos os items associados a ela.

<p align="center">
  <img width="300" height="520" src="https://github.com/eduardorcury/e-commerce-app-frontend/blob/master/resources/screenshots/Categorias.png">
</p>

### Página de produtos

Lista de produtos de uma dada categoria, com imagems individuais. Página com recurso de *infinite scroll*. A seleção dos produtos adiciona o item ao carrinho de compras do usuário.

<p align="center">
  <img width="300" height="520" src="https://github.com/eduardorcury/e-commerce-app-frontend/blob/master/resources/screenshots/Produtos.png">
</p>

### Carrinho de compras

Contém os itens selecionados pelo usuário para compra. Mostra a quantidade de unidades de cada produto, o preço individual e o preço total. A partir dessa página, é possível continuar comprando (voltando à página de categorias) ou finalizar o pedido.

<p align="center">
  <img width="300" height="520" src="https://github.com/eduardorcury/e-commerce-app-frontend/blob/master/resources/screenshots/Carrinho.png">
</p>

### Finalização do pedido

Permite ao usuário selecionar dentre os endereços associados a sua conta, encontrados a partir de uma requisição ao [backend](https://github.com/eduardorcury/spring-boot-ionic-backend). Em seguida, o usuário seleciona a forma de pagamento (cartão de crédito ou boleto) e é direcionado à tela de confirmação.

<p align="center">
  <img width="300" height="520" src="https://github.com/eduardorcury/e-commerce-app-frontend/blob/master/resources/screenshots/Endereço.png">
  <img width="300" height="520" src="https://github.com/eduardorcury/e-commerce-app-frontend/blob/master/resources/screenshots/Pagamento.png">
</p>

### Confirmação do pedido

Tela de confirmação com um resumo da compra: itens selecionados, valor total, nome e email do cliente, endereço e forma de pagamento.

<p align="center">
  <img width="292" height="637" src="https://github.com/eduardorcury/e-commerce-app-frontend/blob/master/resources/screenshots/Confirmação.png">
</p>

### Envio de email 

<p align="center">
  <img width="588" height="546" src="https://github.com/eduardorcury/e-commerce-app-frontend/blob/master/resources/screenshots/Email.png">
</p>

### Página de perfil

Contém as informações do usuário: nome, email e imagem. Também permite a captura e upload de fotos de perfil para o backend, acessando  a Câmera do smartphone com [Apache Cordova](https://github.com/apache/cordova).

<p align="center">
  <img width="300" height="423" src="https://github.com/eduardorcury/e-commerce-app-frontend/blob/master/resources/screenshots/Perfil.png">
</p>
