# Ignes - versão gamma (versão estável de testes)

## API
Utilizamos uma folha de testes como API, para fácil comunicação entre servidor:
https://docs.google.com/spreadsheets/d/1alpbNX6W7s7vOcnEsrskG3ZchfqBb1-nufM_pa-XlLY/edit?usp=sharing

## Aplicação Android
Neste repositório encontra-se um .apk da aplicação Android. A aplicação está funcional na versão 6 Marshmallow, e não foi testada em versões anteriores do SO.

A aplicação web foca-se apenas nas contas de utilizador e trabalhador.
Uma breve lista das funcionabilidades disponíveis:
### Utilizador
* Registar
* Log in
* Log out
* Reportar ocorrências
* Pesquisar ocorrências por localização
* Ver perfil (onde se encontram apenas as ocorrências desse utilizador)
* Editar perfil
* Alterar password
* Ver lista de ocorrências presentes no mapa
* Votar "up" ou "down" nas ocorrências
* Comentar nas ocorrências (apenas para utilizadores de nível 2)
* Mudar o raio default da procura de ocorrências
### Trabalhador
* No mapa, ver as tarefas que lhe foram atribuidas
* Listar essas mesmas tarefas
* Ver direções para o local da tarefa
* Abrir o Google Maps, se necessário
* Ver as notas de uma tarefa (partilhadas por todos os trabalhadores dessa tarefa)
* Acrescentar notas a uma tarefa
* Mudar estado de uma ocorrência/tarefa (apenas interface, sem comunicação ao servidor)

## Aplicação Web
O URL do website, neste momento, é:
https://mimetic-encoder-209111.appspot.com
mas temos comprado o URL https://wokesolutionsignes.com, no entanto este não está operacional devido a problemas com o CORS.

O website está funcional nos browsers Chrome e Firefox, apenas em desktop. O site não foi otimizado para todos os tamanhos de ecrã, mas isto é apenas visual e não afeta o funcionamento.

A aplicação web foca-se apenas nas contas de organização e administrador.
Uma breve lista das funcionabilidades disponíveis:

### Organização
* Registar
* Log in
* Log out
* Registar novo trabalhador
* Apagar trabalhador
* Atribuir ocorrência a um trabalhador
* Listar as tarefas de todos os trabalhadores
* Ver detalhes de uma ocorrência
### Administração
* Listar todos os utilizadores
* Promover utilizadores a administradores
* Ativar organizações pendentes de confirmação
## Servidor
Uma pequena lista de algumas funcionabilidades de que o servidor dispõe como regulamento automático da utilização da aplicação:
* Envio de emails de confirmação de conta (com código gerado aleatoriamente)
* Verificação de tokens e dispositivos, ou seja, um token só é válido num dispositivo
* Envio de email sempre que é feito um login num dispositivo novo, para o email do utilizador, como medida de segurança
* Tracking de quantos e quais dispositivos são usados pelos utilizadores
* Tracking de praticamente todas as ações realizadas nos clientes (mudanças de infirmações de perfil, operações de administração, etc)
* Algumas outras operações relevantes, mas ainda inutilizadas do lado do cliente.
## Contas que podem ser utilizadas
Tipo de utilizador | Nome de utilizador | Palavra-passe
:-------------: |:-------------:| :-----:
Utilizador (nível 1) | catarina | naoqueressaber
Utilizador (nível 2) | goncalosr | 123456
Trabalhador | purpleviewsgsr@gmail.com | 19895180p
Organização (confirmada) | 123456789 | 123456789
Organização (não confirmada) | 987654321 | 1qaz2wsx3edc
Administrador | wokesolutions | wokesolutions

##### Podem contactar-nos através do email: wokesolutionsignes@gmail.com, ou falando pessoalmente connosco, sobre qualquer dúvida que haja.
##### Obrigado,
### WokeSolutions
