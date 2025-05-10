# Nível 5 - Bandit

## Objetivo:
Conectar ao SSH e obter acesso ao próximo nível

## Comando usado: 
´´´bash ssh bandit4@bandit.labs.overthewire.org -p 2220

## Após o acesso:
ls, cd, ls -li, file ./*, cat

## Explicação:
A chave está localizada em um arquivo entre vários semelhantes, nesta etapa temos que encontrar o arquivo que contém caracteres humanamente legíveis. Novamente fazemos o uso do "ls" para listar os arquivos/diretórios, após isso utilizados o "cd" para acessar o diretório em questão, posteriormente usamos "ls -li" para exibir a listagem detalhada, então usamos o comando "file ./*" para listar os tipos de dados nesses determinados arquivos, assim, encontrando o arquivo que contém a nossa chave.

## Senha para o nível 6:
(Ok! Você sabe que eu não irei dizer, mas se chegou até aqui junto comigo, você está indo bem, continue!!)
