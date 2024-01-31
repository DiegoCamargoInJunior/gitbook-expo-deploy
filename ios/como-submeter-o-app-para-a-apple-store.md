# Como submeter o app para a Apple Store

Primero precisamos ir até o projeto e editar o "eas.json"

Dentro de "production" que esta dentro "submit" nos vamos adicionar  "ios" e dentro dele irá ter os dados do nosso app e da loja

<figure><img src="../.gitbook/assets/WhatsApp Image 2024-01-22 at 10.58.13.jpeg" alt=""><figcaption></figcaption></figure>

Esses dados são:

appleId: O seu email da Apple

ascAppId: O id do seu app na loja da apple, acesse o painel de administração do seu app no Apple Connect e em "App Information" procure por "Apple ID"

<figure><img src="../.gitbook/assets/Screenshot 2024-01-22 at 10.52.42.png" alt=""><figcaption></figcaption></figure>

appleTeamId: O id do seu time de desenvolvimento, para conseguir isso acesse o seu perfil da conta da apple e procure por "Team ID"

<figure><img src="../.gitbook/assets/Screenshot 2024-01-22 at 10.56.25.png" alt=""><figcaption></figcaption></figure>

Após ter configurado o "eas.json" vá ate o seu terminal e execute o seguinte comando para submeter o build mais recente gerado pelo expo

```bash
eas submit -p ios --latest
```

Com isso será perguntado se deseja escolher uma chave da Apple Connect ou criar uma nova, selecione "Add a new key"

<figure><img src="../.gitbook/assets/WhatsApp Image 2024-01-22 at 11.02.49.jpeg" alt=""><figcaption></figcaption></figure>

Logo em seguida digite "y" para criar uma nova chave

<figure><img src="../.gitbook/assets/WhatsApp Image 2024-01-22 at 11.03.02.jpeg" alt=""><figcaption></figcaption></figure>

Confime o seu Apple ID

<figure><img src="../.gitbook/assets/WhatsApp Image 2024-01-22 at 11.03.15.jpeg" alt=""><figcaption></figcaption></figure>

Agora é so aguardar o app ser submetido e para ter mais detalher basta clicar no link do expo

<figure><img src="../.gitbook/assets/WhatsApp Image 2024-01-22 at 11.06.27.jpeg" alt=""><figcaption></figcaption></figure>
