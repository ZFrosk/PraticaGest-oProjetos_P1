_______________________________________________________

<b><h2>Explicação dos diretórios criados:</h2></b><br>
- admin: branch criada para armazenar arquivos relacionados ao admin da página.
- front-end: branch criada para armazenar arquivos relacionados ao front-end da página.
- site: branch criada para vincular o website com o github

_______________________________________________________

<b><h2>COMANDOS USADOS PARA CONSTRUIR O DIRETÓRIO</h2></b>

<b>1-)</b> Primeiro foi necessário criar o repositório no Github e deixa-lo público com o READ.ME marcado.

<b>2-)</b> Logo após a criação do repositório, é necessário obter o link do repositório no Github, para fazer isso é necessário ir até o repositório e clicar no botão "Code", lembrando que deve ser pego o "HTTPS" dele.

<b>3-)</b> Agora é necessário ir até o desktop, clicar com o botão direito em uma área vazia e escolher a opção "Open Git Bash Here".

<b>4-)</b> Logo após é necessário digitar "git clone <link do repositório>" e colar o link obtido pelo repositório. A pasta respectiva do repositório aparecerá no destkop, 
é necessário clicar com o botão direito nela e clicar em "Open Git Bash Here".

<b>5-)</b> Para a criação das branchs "front-end" e "admin" foi necessário usar o  "git checkout -b front-end" e "git checkout -b admin" , 
podendo assim armazenar os arquivos correspondente em cada uma.

<b>6-)</b> Logo após foi utilizado um "git branch -l" para visualização das branchs criadas.

<b>7-)</b> Depois foi necessário usar o comando "git checkout admin" para sair da branch main e ir na branch admin, 
e logo após usar o comando "git push origin admin" para enviar a branch para o repositório. Repetimos o processo com o front-end, "git checkout front-end"
para sair da branch admin e ir na front-end "git checkout front-end", usar o comando "git push origin front-end" para enviar a branch no repositório.

<b>8-)</b> Logo após adicionamos os arquivos "index.html" e "style.css" na branch "front-end" e digitamos o comando "git status" para a visualização dos arquivos e confirmação de que eles estão na branch correta.

<b>9-)</b> Digitamos "git add ." para adicionar todos os itens que estão pendentes. Só para a confirmação, devemos digitar "git status" e visualizar os itens já em espera para ser commitados, a cor deles é alterada.

<b>10-)</b> Logo após digitamos "git commit -m <mensagem de registro>" para que assim possamos commitar e registrar que estamos prestes a dar push nos arquivos.

<b>11-)</b> Assim podemos dar o comando "git push origin front-end", finalmente enviando os arquivos correspondentes para o repositório e na branch "front-end".

<b>12-)</b> Foi criado a branch site para subir o website no ar e disponibilizar a home da loja de hardware. Utilizamos o comando "git checkout -b site" para a criação da branch.

<b>13-)</b> Agora é preciso ir nas configurações do repositório, pages e vincular a branch site para que o Github indetifique o website. 
Poderá demorar alguns minutos até que fique no ar.
_______________________________________________________
<br><b><h2>INSTRUÇÕES DE COMO ACESSAR O WEBSITE</h2></b><br>
Existe duas maneiras de acessar o site criado para os usuários.<br>

<b>1º</b> O usuário dono do repositório poderá acessar atráves das configurações do repositório, indo até pages e obtendo o link disponibilizado.<br>
<b>2º</b> O usuário deverá copiar o link gerado na aba pages e vincular na sessão About do repositório, assim todos os usuários que visualizarem o repositório, poderá acessar. Aproveite e coloque também os tópicos ao seu repositório.

_______________________________________________________
