# Como buildar o app

Primeiro de tudo você precisa acessar esse site [Expo](https://expo.dev/signup) e criar uma conta

Logo em seguida escreva no seu terminal o seguinte comando

```bash
npx eas login
```

Ele ira pedir o seu email e depois a senha da sua conta Expo

Apos ter realizado seu login digite o seguinte comando para configurar seu projeto

```bash
npx eas build:configure
```

Apos isso crie um conta da Apple ID nesse [link](https://appleid.apple.com/account)

Com isso acesse o [link ](https://appstoreconnect.apple.com/login)da Apple Connect e realize seu login

Com isso ele ira perguntar qual ambiente é para configurar selecione a opção "All"

<figure><img src=".gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

Agora precisamos criar uma conta da Apple com o email da IN Junior, para isso basta acessar o seguinte [link](https://appleid.apple.com/account)

Preencha o formulario de cadastro inserindo o seu nome e sobrenome, pais, data de nascimento, email da IN Junior, senha e confirmação de senha

<figure><img src=".gitbook/assets/Screenshot 2024-01-22 at 08.10.50.png" alt=""><figcaption></figcaption></figure>

Descendo um pouco mais a pagina você ira inserir o seu numero de telefone e a forma que gostaria de confirma-lo, selecione as opções de email marketing que preferir responder, confirme o captcha e descendo mais clique no botão "Continue"

<figure><img src=".gitbook/assets/Screenshot 2024-01-22 at 08.16.05 (1).png" alt=""><figcaption></figcaption></figure>

Preencha com o codigo que recebeu no seu email e clique em "Continue"

<figure><img src=".gitbook/assets/Screenshot 2024-01-22 at 08.21.01.png" alt=""><figcaption></figcaption></figure>

Confirme o codigo que recebeu no seu celular da forma selecionada anteriormente e clique em "Continue"

<figure><img src=".gitbook/assets/Screenshot 2024-01-22 at 08.23.38.png" alt=""><figcaption></figcaption></figure>

Com isso a sua conta vai ter sido criada com sucesso e basta solicitar ao seu diretor de Projetos para te adicionar ao time da IN Junior

Apos isso digite o comando a seguir para realizar o build do app

```bash
npx eas build --platform all
```

Confirme seu app bundle pressionando "enter"

<figure><img src=".gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

Faça a mesma coisa para a apple

<figure><img src=".gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

Realize login na sua conta da apple escrevendo "y"

<figure><img src=".gitbook/assets/image (6).png" alt=""><figcaption></figcaption></figure>

Digite "y" para confirmar a reutilização de certificado de distribuição da Apple, mas caso apareça uma pergunta se deseja criar um novo basta digitar "y" também

<figure><img src=".gitbook/assets/WhatsApp Image 2024-01-22 at 08.34.12.jpeg" alt=""><figcaption></figcaption></figure>

Digite "y" para confirmar a criação de novo perfil para o app na Apple

<figure><img src=".gitbook/assets/WhatsApp Image 2024-01-22 at 08.38.35.jpeg" alt=""><figcaption></figcaption></figure>

Caso o seu app não tenha sistema de notificações basta clicar em "No", caso tenha clique em "Yes"

<figure><img src=".gitbook/assets/WhatsApp Image 2024-01-22 at 08.41.12.jpeg" alt=""><figcaption></figcaption></figure>

Agora o seu app vai estar sendo buildado tanto para IOs quanto para Android e basta clicar em um dos link para acompanhar com mais detalhes o que esta acontecendo

<figure><img src=".gitbook/assets/WhatsApp Image 2024-01-22 at 08.46.06.jpeg" alt=""><figcaption></figcaption></figure>
