

<img src="https://devblogs.microsoft.com/commandline/wp-content/uploads/sites/33/2019/03/CommandLineIcon.png" width="155px">

<img src="https://img.shields.io/badge/windows%20terminal-4D4D4D?style=for-the-badge&logo=windows%20terminal&logoColor=whit">

# PROMPT-DE-COMANDO
_**Comandos do Prompt de Comando do WINDOWS**_

## COMANDOS DE DIRETÓRIOS/ARQUIVOS
- ```dir``` : Lista arquivos e pastas.
  - ```dir /p``` : Ele quebra a exibição em partes.
  - ```dir /w``` : Exie o conteúdo da pasta organizado por colunas.
  - ```dir /o``` : Exibe o contéudo organizado alfabeticamente.
  - ```dir /od``` : Mostra pastas/arquivos pcom sua hora e dia que foram criados.
  - ```dir /b``` : Lista por linha os nomes das pastas e arquivos.
- ```cd``` : Entra em um diretório.
  - ```cd /``` : Vai pra raiz do Windows.
  - ```cd *``` : Mostra o diretório atual.
- ```type``` : Mostra o conteúdo de um arquivo de texto.
- ```echo``` : Escreve uma mensagem inserida pelo usuário no terminal.
  - ```echo ola mundo > olamundo.txt``` : Escreve e manda para um arquivo de texto.
  - ```echo ola mundo2 >> olamundo.txt``` : Insere na proxima linha do arquivo .txt.
- ```tree``` : Mostra o diretorios pai e filhos, junto com seus arquivos (**modo de árvore**).

## COMANDOS DO SISTEMA
- ```doskey /history``` : Mostra o histórico de comandos já executados anteriormente.
- ```drivequery``` : Mostra todos os drives instalados no seu computador.
- ```time``` : Mostra a hora atual do sistema, podendo modifica-lá.
- ```date``` : Mostra a data atual do sistema, podendo modifica=lá.
- ```vol``` : Mostra a unidade do disco e seu número de série.
- ```wmic``` : Acessa informações do sistema, **veja seus parâmetros**.
  - ```wmic product get name,version``` : Mostra o nome ea vesão dos softwares instalados.
