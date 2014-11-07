COLOCANDO UM REPOSITÓRIO NO GITHUB
--
**Considerando que o git já está instalado na maquina local e a Chave SSH configurada**. 

>1 - Entrar em http://www.github.com e criar um novo repositório.

>2 - Na MÁQUINA LOCAL, entrar na pasta aonde quer QUE SEJA SALVO (clonado) o repositório do GitHub.

>3 - $ git clone git@github.com:grassini/Trabalhando_Com_Github.git

>4 - Pronto já esta com o repositório colonado em sua maquina local.

FAZENDO AS MODIFICAÇÕES NO PROJETO
--

>1 - Criando o arquivo README.txt - $ touch README.txt

>2 - Olhando o Status do repositório - $ git status

>2 - $ git add . (vai JOGAR todos os arquivos e diretórios para “Sala de Espera”) 

>3 - $ git commit -m “Mensagem Relacionada a Alteração”

>4 - ATÉ AQUI TUDO SALVO NA MÁQUINA LOCAL.

>5 - $ git push origin master (Enviando para o GitHub as Mudanças e atualizando o Repositório).
