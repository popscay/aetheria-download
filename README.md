# Aetheria Heart Monitor — página de testes

## 1. Publicar o APK

Crie um repositório no GitHub, preferencialmente separado do código-fonte Android, por exemplo `aetheria-download`.
Crie uma Release com tag `v0.1.0` e anexe `AetheriaHeartMonitor-v0.1.0.apk` (não envie a keystore).
Copie o endereço **real** do ficheiro APK da Release.

## 2. Configurar os links

Edite `config.js` e preencha `apkUrl` com o endereço do APK. Opcionalmente, preencha `feedbackUrl` com o endereço de Issues ou de um formulário de feedback.

## 3. Publicar a página

Envie `index.html` e `config.js` para a raiz do repositório GitHub.
Em Settings → Pages, selecione Deploy from a branch, `main`, `/ (root)`.
A página ficará num endereço do tipo `https://UTILIZADOR.github.io/aetheria-download/`.

## 4. Antes de partilhar

- Teste o botão de download e a instalação num dispositivo de testes.
- Confirme versão e assinatura do APK.
- Não publique ficheiros `.jks`, `.keystore` ou palavras-passe.
- Revise os textos e acrescente uma política de privacidade apropriada ao comportamento real da app.
- A aplicação é experimental e as estimativas CNN não estão clinicamente validadas.
