Github

Arquivo da aula de Git e Github para iniciantes
Aula 9
git status - status dos arquivos

passos para adicionar e commitar um arquivo:
-git add nomeDoArquivo.extensão
-git commit -m "mensagen de log"

Aula 10
git log/git log --decorate/git log --author="Nome do autor"/git shortlog/git shortlog -sn/git log --graph -> informações dos arquivos

Aula 11
-git diff/ git diff --name-only -> mostra as modificaões no arquivo antes de commitar
-git commit -am "mensagem" -> quando o arquivo ja existe

Aula 12
-git checkout arquivo -> retorna elimina uma modificação no arquivo antes do commit
-git reset HEAD arquivo.ext -> retorna do staged para o inicial
-git reset --soft(mata o commit retorna para o estado staged) --mixed(mata o commit retorna para unmodified) --hard(mata tudo q foi feito no commit), usa a rash do commit ao que se quer retornar

aula 15
-git remote add origin git@github.com:wanderley794/github-course.git ->subir repositorio pr o github
-git remote/git remote -v -> mostra os repositorios upados para o github
-git push -u origin master -> envia os arquios para o repositorio do github sentido origin<-master.

aula 17
-g clone endereçoDoRepositorio nomeAtribuido -> copia um repositorio do github para o da maquina

aula bramch 
-git checkout -b testing -> cria um branch
-git branch -> mostra os branch existentes
-git checkout -b testing -> muda de um para o outro passando o nome do branch
-git branch -D testing -> apaga um branch
