# Guia para publicar seu portfólio (para iniciantes)

Você não precisa instalar nada para publicar. Vamos usar o GitHub para guardar os arquivos e o Netlify para colocar o site no ar.

## Parte A — Baixar e descompactar
1. Baixe o arquivo ZIP recebido.
2. No computador, clique com o botão direito e escolha **Extrair tudo**.
3. Abra a pasta `portfolio_comunicacao_rick`.
4. Confira se aparecem `index.html`, `style.css`, `script.js` e este guia.

## Parte B — Criar um repositório no GitHub
1. Entre em https://github.com e faça login.
2. Clique no sinal **+** no alto da página e escolha **New repository** (ou abra https://github.com/new).
3. Em **Repository name**, escreva `portfolio-comunicacao`.
4. Escolha **Public**.
5. Pode deixar a opção de criar README desmarcada, pois o projeto já tem um.
6. Clique em **Create repository**.

## Parte C — Enviar os arquivos para o GitHub
1. Dentro do repositório novo, clique em **Add file** e depois em **Upload files**.
2. Abra a pasta que você extraiu no computador.
3. Arraste para a página do GitHub os arquivos e a pasta `assets` que estão dentro dela. Envie o conteúdo da pasta, não apenas o arquivo ZIP.
4. Desça a página até **Commit changes**.
5. Clique em **Commit changes** para confirmar o envio.
6. Confira se `index.html`, `style.css` e `script.js` aparecem na página principal do repositório.

## Parte D — Publicar no Netlify
1. Entre em https://www.netlify.com/ e crie uma conta ou faça login. Se for mais fácil, escolha entrar com GitHub.
2. No painel do Netlify, procure **Add new project** (ou **Add new site**) e escolha importar um projeto existente via Git.
3. Escolha **GitHub** e autorize a conexão se o site pedir.
4. Selecione o repositório `portfolio-comunicacao`.
5. Como este site usa HTML, CSS e JavaScript simples, deixe **Build command** vazio e **Publish directory** como `.` (um ponto), se esses campos aparecerem.
6. Clique em **Deploy**.
7. Aguarde a publicação. O Netlify mostrará um endereço terminado em `netlify.app`. Abra esse endereço para ver o site.

Os nomes dos botões podem variar um pouco conforme a versão da interface. Se você não encontrar uma opção, envie uma captura de tela e eu te digo onde clicar.

## Parte E — Como atualizar depois
1. Abra o repositório no GitHub.
2. Clique no arquivo que deseja mudar e no lápis para editar textos simples, ou use **Add file → Upload files** para enviar imagens.
3. Clique em **Commit changes** para salvar.
4. O Netlify detectará a atualização e publicará uma nova versão automaticamente.

## Antes de divulgar o endereço
- Troque o e-mail de exemplo pelo seu e-mail verdadeiro.
- Atualize o link do LinkedIn.
- Revise todos os textos.
- Substitua os projetos de demonstração por trabalhos reais ou deixe claro que são exemplos.
- Teste o site no celular.
