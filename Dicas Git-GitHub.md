# Movendo arquivos do computador para o GitHub usando o Git
1º No seu computador, mova o arquivo do qual deseja fazer upload para o GitHub, no diretório local que foi criado quando o repositório foi clonado.
<br>2º Abra Git Bash. 
<br>3º Mude o diretório de trabalho atual para o seu repositório local.(um atalho é acessar seus arquivos, a pasta que está clonado e com o botão direito apertar em Git Bash Here)
<br>4º Prepare a arquivo para commit em seu repositório local.
   - No git use o comando "Git add ." (sem as aspas), logo depois precione enter
   - Faça commit do arquivo que você preparou no repositório local. Usando o comando "git commit -m (Add existing file)"
   - Por Fim Efetue push das alterações no repositório local para o GitHub.com. Usando o comando "git push origin YOUR_BRANCH"

# Atalhos Git
- Limpar a tela deixando a linha atual no topo da janela:Ctrl+L
- Apagar uma palavra:Ctrl+W
- Apagar uma linha:Ctrl+U
- Mover para o início da linha:Ctrl+A 
- Mover para o fim da linha:Ctrl+E
- Colar texto da área de transferência:Ctrl+Y

# Comandos Git
- Git status: O comando “git status” mostra nos o estado do diretório de trabalho, por exemplo os ficheiros que foram modificados e por ai vai.
- Git commit: O comando ‘git commit -a -m “mensagem”‘, adiciona os ficheiros modificados e adiciona a mensagem ao atual indexe. E se correr tudo bem está pronto para enviar as mudanças para o gitHub.
- Git push: O comando “git push origin master” sincroniza o repositório local com o repositório no gitHub.
