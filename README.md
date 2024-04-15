# Comandos Básicos do Git

## `git init`
Inicializa um repositório Git em um diretório local.

## `git clone [URL]`
Clona um repositório Git para o seu diretório local.

## `git add [arquivo]`
Adiciona um arquivo ao índice (staging area) para ser versionado.

## `git commit -m "[mensagem]"`
Registra as mudanças feitas no repositório, adicionando uma mensagem descritiva.

## `git status`
Exibe o status atual do repositório, mostrando os arquivos modificados, adicionados ou removidos.

## `git diff`
Mostra as diferenças entre as mudanças no diretório de trabalho e o índice.

## `git log`
Exibe o histórico de commits do repositório.

## `git pull`
Puxa as mudanças do repositório remoto para o seu repositório local.

## `git push`
Envia as mudanças do seu repositório local para o repositório remoto.

# Comandos de Ramificação e Mesclagem

## `git branch`
Lista todas as branches no repositório local.

## `git branch [nome]`
Cria uma nova branch com o nome especificado.

## `git checkout [branch]`
Muda para a branch especificada.

## `git merge [branch]`
Mescla a branch especificada com a branch atual.

## `git rebase [branch]`
Reorganiza o histórico do commit para incluir os commits da branch especificada.

# Comandos de Tag

## `git tag`
Lista todas as tags no repositório.

## `git tag [nome]`
Cria uma nova tag com o nome especificado no commit atual.

## `git tag -a [nome] -m "[mensagem]"`
Cria uma nova tag anotada com uma mensagem descritiva.

## `git push --tags`
Envia todas as tags para o repositório remoto.

# Comandos de Desfazer e Corrigir

## `git reset [arquivo]`
Retira o arquivo do índice, mas mantém as mudanças no diretório de trabalho.

## `git reset --soft [commit]`
Retira commits do histórico sem modificar o índice ou o diretório de trabalho.

## `git reset --hard [commit]`
Retira commits do histórico, modificando o índice e o diretório de trabalho.

## `git revert [commit]`
Desfaz um commit específico, criando um novo commit com as mudanças reversas.

