# Comandos básicos para configuração e utilização do GIT
## git init
Inicializa um novo repositório Git e começa a acompanhar um diretório existente.
## git clone
Cria uma cópia local de um projeto que já existe remotamente. O clone inclui todos os arquivos, histórico e branches do projeto.
## git add .
É conhecido por “adicionar conteúdo” (propor uma mudança qualquer, seja ela alterar, adicionar ou remover um conteúdo) de um arquivo local no diretório local.
## git commit
Leva as mudanças de um ambiente local para o repositório no git, permitindo ainda a inserção de uma mensagem descritiva. Assim, a cada mudança ou finalização de uma tarefa, a pessoa desenvolvedora pode submeter seus feitos e deixar claro para as outras pessoas o que ela fez.
```
git commit -m "mensagem de exemplo"
```
## git status
Mostra o status das alterações como não controladas, modificadas ou preparadas.
## git branch
Mostra os branches que estão sendo trabalhados localmente.
## git marge
Permite que você pegue as linhas criadas a partir do git branch e faça uma integração para a ramificação principal.
## git pull
É usado para buscar e baixar conteúdo de repositórios remotos e fazer a atualização imediata ao repositório local para que os conteúdos sejam iguais.
## git push
Atualiza o repositório remoto com todos os commits feitos localmente em um branch.
## git log
Exibe o histórico de commits em um repositório Git. Ele exibe os exibe em formato de lista, incluindo o nome do autor do commit, a data e hora em que foi feito e a mensagem associada. Ele permite uma análise detalhada do desenvolvimento do projeto ao longo do tempo.
## git reset
É uma maneira simples de desfazer alterações que não foram compartilhadas com mais ninguém.
# Exercícios
## Para iniciar o GIT em um novo repositório:
R: `git init`
## Para adicionar as alterações realizadas no repositório:
R: `git add .`
## Para gravar as alterações:
R: `git commit -m "mensagem de exemplo"`
## Para enviar as alterações para a núvem/repositório online:
R: `git push`
## Se o repositório em meu computador estiver desatualizado, como faço para atualizá-lo?
### (Lembrando que estarei atualizando com base no repositório salvo no GitHub)
R: `git pull`

