 * Git init - inicia o repositório no git (dentro da pasta que vai ser utilizada, dar um git init cria um repositório)
 * Git add - move arquivos e dá início ao versionamento. (git add * adiciona todos os novos arquivos ao diretório)
 * Git commit -m"" - cria commits, dentro das aspas se coloca a informação do que foi comitado.
 * Git remote add **origin**   **url do repositório no git** - aponta para qual repositorio remoto os arquivos do repositorio local serão enviados.
 * Git remote -v - informa a lista de repositrios remotos que eu tenho cadastrados no git.
 * Git push origin master (origin main) - envia os arquivos do git para o github no repositorio que foi informado previamente , na branch master.
 
 **RESOLVENDO CONFLITOS**
 
 * Git pull origin master - Caso alguem faça uma alteração no repositorio remoto, é necessario primeiro fazer o pull para o repositorio local e só então faer o push com o arquivo modificado.
 * Git clone - quando se quer copiar todo um repositório remoto de outra pessoa, copia-se o código do repositorio em <code> no github e no git executa o **git clone + url copiada**
 
