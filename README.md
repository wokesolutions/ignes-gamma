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
