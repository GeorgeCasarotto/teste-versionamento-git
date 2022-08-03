Comandos Git básicos
1. git config
Quando você está utilizando o Git pela primeira vez ou com uma instalação nova, em um projeto colaborativo, esse comando é fundamental para configurar sua identidade de usuário, inserindo informações como nome e email que serão empregadas em cada commit.

2. git init
Esse é o comando que você irá utilizar para criar um novo projeto de git. O comando irá criar um repositório novo em branco e, a partir daí, será possível armazenar seu código fonte, alterar, salvaguardar alterações etc.

3. git clone
Esse comando Git cria uma cópia exata de um repositório já existente.

4. git add

Esse comando Git adiciona os arquivos especificados de código ao seu repositório, sejam arquivos novos ou arquivos anteriores que foram alterados. Oferece diferentes possibilidades de sintaxe.

5. git commit
É fundamental se estabelecer uma diferença entre git add e git commit:

6. git branch
É comum na maior parte do tempo possuir múltiplas variações em seu repositório Git, chamadas de branches (“ramificações”). A grosso modo, um branch é um caminho independente de desenvolvimento, uma alternativa.

7. git checkout
Ainda sobre branches, esse comando Git pode ser utilizado para trocar de uma ramificação para outra.

8. git remote
O comando Git remote estabelece uma conexão entre seu repositório local e um repositório remoto.

9. git push

Esse comando serve para subir suas modificações para um repositório remoto conectado anteriormente com git remote.

10. git fetch
Quando você precisa baixar as mudanças criadas por outros membros do seu projeto colaborativo, você precisa do comando Git fetch. A partir desse comando, você irá receber todas as informações de commits, para avaliar, antes de aplicar essas alterações na sua versão local do repositório.

11. git pull
O comando Git pull baixa o conteúdo (não os metadados) do que foi alterado no repositório remoto para o seu repositório local e imediatamente atualiza seu contreúdo para a última versão.

12. git stash

Esse comando Git armazena temporariamente seus arquivos modificados em uma área chamada stash (“esconderijo”), sem interagir com os outros arquivos até ser necessário.

13. git show
Quer detalhes específicos sobre um commit que o log não mostra? O comando Git show é a resposta.

14. git rm
Para remover arquivos da sua pasta, você pode utilizar o comando Git rm.

15. git help
Existem inúmeros comandos no Git, muito mais do que os 25 dessa lista, cada um com sua função, parâmetros e características. Felizmente, o próprio Git tem o comando help para trazer ajuda diretamente no terminal.

16. git merge
Esse comando Git integra as mudanças de dois branches diferentes em um único branch. Ele precisa ser iniciado a partir de um branch já selecionado, que será mesclado com outro, com o nome passado por parâmetro.

17. git rebase
Git rebase a princípio parece fazer o mesmo que um comando git merge: ele integra dois branches em um branch único. Porém, esse comando refaz o histórico de commits, tornando-o linear. É o mais indicado para consolidar múltiplos branches.

18. git pull –rebase
Essa é uma variação do comando pull mostrado anteriormente. A partir dessa instrução, o Git irá fazer um rebase (não um merge) depois de se utilizar um comando pull.

19. git cherry-pick
Esse é um comando poderoso que permite selecionar qualquer commit específico de um brach e aplicá-lo a outro branch, sem precisar de uma mescla completa. A operação fica adicionada no histórico.

20. git archive
Esse comando Git combina múltiplos arquivos em um único arquivo, como se fosse um arquivo zipado. Esse pacote pode ser aberto depois e os arquivos contidos podem ser extraídos individualmente.

21. git blame
O comando “dedo-duro”, blame ajuda a determinar qual usuário realizou qual mudança em um determinado arquivo.

22. git tag
Tags são uma boa opção para marcar uma branch e evitar alteração, principalmente em releases públicos.

23. git diff
Para comparar dois arquivos gits ou dois branches antes de passarem por um commit ou um push, é importante executar esse comando Git.

24. git citool
Esse comando Git oferece uma alternativa gráfica ao commit.

25. git whatchanged
Esse comando oferece informações de log, mas em formato raw.

