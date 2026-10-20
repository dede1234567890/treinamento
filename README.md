# Swift Treinamentos — versão de teste para GitHub Pages

Portal HTML estático com conta de funcionário para testar e pasta `/logins/` com contas **de demonstração pública**.

## Entradas de teste

| Perfil | Nome completo | Senha | Código da equipe |
| --- | --- | --- | --- |
| Funcionário | `Funcionario Teste` | `Teste@123` | `TESTE123` |
| Gerente | `Gerente Demo` | `Teste@123` | `TESTE123` |

Para **Gerente**, o formulário atual também pede o código da administração: `202526`. Esse código está no JavaScript público e **não oferece segurança real**.

O funcionário de teste já tem uma **mini prova de demonstração** disponível. Na entrada de funcionário, há também um botão para acesso direto ao usuário de teste.

## Como atualizar seu repositório no GitHub

1. Extraia o ZIP deste projeto em seu computador.
2. No repositório `dede1234567890/treinamento`, substitua o `index.html` pelo novo arquivo.
3. Envie também a pasta `logins` com `contas-teste.json` e `README.md` dentro.
4. Confirme o commit e aguarde a publicação em **Actions** / **Settings → Pages**.
5. Acesse: https://dede1234567890.github.io/treinamento/

O arquivo `index.html` também inclui uma versão de reserva dos logins de teste, então o botão funciona mesmo antes de enviar a pasta `logins`. Mas envie a pasta para manter a configuração organizada.

## Atenção: não há salvamento central de contas

O GitHub Pages publica arquivos estáticos, mas **não grava** usuários cadastrados pelo site em uma pasta. Cadastro, atividades e progresso permanecem no armazenamento local de cada navegador (localStorage); não há sincronização entre pessoas e dispositivos.

O arquivo `/logins/contas-teste.json` está publicado e é acessível a qualquer pessoa: use-o somente para **usuários de demonstração**, nunca logins reais.

Para gerentes e funcionários reais compartilharem contas, treinamentos, notas e resultados, a próxima etapa é adicionar banco de dados e autenticação gerenciada (Supabase Auth, Firebase Auth etc.).
