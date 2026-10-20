# Pasta logins — somente demonstração

- `contas-teste.json`: contas **fictícias e públicas** usadas para o teste no GitHub Pages.
- Ao abrir o site, `index.html` lê o arquivo e cria as contas de teste no navegador, caso ainda não existam.
- Alterar o JSON e publicar novamente pode incluir novos **usuários fictícios** em cada navegador, mas não sincroniza progresso ou registros entre aparelhos.
- **Não coloque aqui dados de funcionários reais, senhas pessoais, tokens, chaves ou outras informações privadas.** Tudo publicado neste repositório público pode ser acessado por qualquer pessoa.
- Contas cadastradas normalmente pelo formulário ficam apenas no `localStorage` de quem usa o navegador; elas **não** são gravadas neste diretório automaticamente.
- Para salvar autenticações reais de vários usuários, implemente serviço de autenticação e banco de dados com regras de acesso (ex.: Supabase Auth ou Firebase Auth).
