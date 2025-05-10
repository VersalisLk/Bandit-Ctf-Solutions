# Nível 2 - Bandit

## Objetivo: 
Conectar no SSH e encontrar a senha para o próximo nível.

## Comando usado:
´´´bash ssh bandit1@bandit.labs.overthewire.org -p 2220

## Após conectar:
ls, cat ./-

## Explicação: 
O arquivo em questão com a senha estava com o nome de um caractere especial, usei "ls" para listar os arquivos e após, usei "cat" para fazer a leitura do arquivo, por se tratar de um caractere especial o comportamento padrão do UNIX/Linux é interpretar como um parâmetro especial, por isso foi usado desta forma: "cat ./-"

## Senha para o nível 2:
(Não será exibida para fins didáticos)
