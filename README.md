# Swift Treinamentos — versão estática

Este projeto transforma o arquivo original em uma página HTML única, com CSS e JavaScript já incluídos, para publicação no GitHub Pages.

## Publicar com GitHub Pages

1. Crie um repositório no GitHub (por exemplo, `swift-treinamentos`).
2. Faça upload do arquivo **`index.html`** para a pasta principal do repositório e confirme o commit.
3. Abra **Settings → Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**.
5. Escolha **main** e **/(root)**, depois clique em **Save**.
6. O endereço geralmente será `https://SEU-USUARIO.github.io/swift-treinamentos/` (exceto repositórios especiais como `SEU-USUARIO.github.io`).

## Importante: limitações desta versão

- O GitHub Pages hospeda HTML, CSS e JavaScript, mas não fornece banco de dados nem autenticação de usuários.
- Este protótipo usa `localStorage`: **cada navegador tem sua própria base de dados**. Um gerente no computador A não compartilha contas nem atividades com um funcionário no celular B.
- O código administrativo e as senhas deste protótipo ficam no lado do navegador. **Não é seguro para uso em produção**; não use senhas pessoais ou dados reais de funcionários.
- Para uma plataforma real, será necessário usar autenticação e banco de dados com regras de acesso, por exemplo, Firebase Auth + Firestore ou Supabase. O GitHub Pages ainda pode hospedar a interface.

## Como testar

Abra o arquivo `index.html` no navegador ou acesse a página publicada. Cadastre um gerente e um funcionário no **mesmo navegador**, usando o código da equipe exibido pelo gerente para testar atividades, mini provas, conclusão, pontos e relatórios.
