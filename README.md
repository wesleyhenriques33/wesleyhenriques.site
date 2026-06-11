# wesleyhenriques.site

Este repositório foi criado para hospedar landing pages estáticas (HTML/CSS/JS).
A página inicial (`index.html`) é mantida em branco intencionalmente.

## Como adicionar novas sub-páginas

Para adicionar uma nova landing page (por exemplo, "promocao-de-vendas"):
1. Crie uma nova pasta aqui com o nome desejado: `promocao-de-vendas`
2. Coloque os arquivos da landing page dentro desta pasta. Certifique-se de que o arquivo principal se chame `index.html` (ex: `promocao-de-vendas/index.html`).
3. Ao acessar `wesleyhenriques.site/promocao-de-vendas/`, a página será carregada automaticamente.

## Como publicar no Github
1. Acesse o [Github](https://github.com/) e crie um novo repositório (pode ser público ou privado).
2. Pelo terminal ou interface do Git, dentro desta pasta (`wesleyhenriques.site`), inicialize o repositório e envie os arquivos:
   ```bash
   git init
   git add .
   git commit -m "Commit inicial"
   git branch -M main
   git remote add origin URL_DO_SEU_REPOSITORIO_AQUI
   git push -u origin main
   ```

## Como fazer o deploy no Netlify
1. Crie uma conta ou faça login no [Netlify](https://www.netlify.com/).
2. Vá em **Add new site** > **Import an existing project**.
3. Escolha **GitHub** e autorize o acesso.
4. Selecione o repositório `wesleyhenriques.site` que você acabou de criar.
5. Deixe as configurações de "Build command" e "Publish directory" em branco (pois é um site HTML estático).
6. Clique em **Deploy site**.
7. Pronto! Após o deploy, você pode configurar seu domínio personalizado (`wesleyhenriques.site`) nas configurações de "Domain management" do Netlify.
