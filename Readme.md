# GitHub

Arquivo da aula de Git e Github para iniantes

# Git Course

Este é um repositório teste para ensinar como o git funciona.

Saiba mais em: [github.com/fabiomelg](https://www.github.com/fabiomelg)

Gostou do curso? Quer mais? Ajude com uma doação, até um café é válido. =)

# Comandos do GitHub

===============================================================
CONFIGURAÇÕES GLOBAIS
===============================================================

git config --global user.name "user_name" => configura o usuário

git config --global user.email "e-mail" => configura o e-mail do usuário

git config --global core.editor vi => configura o editor do git

===============================================================
INICIAL
===============================================================

mkdir <nome_da_pasta> => cria diretório

cd <nome_da_pasta> => entra no diretório

git init => inicializa o diretório

ls => lista arquivos do diretório

ls -la => lista arquivos do diretório

cd .. => retorna o diretório

vi <nome_do_arquivo> => cria e abre um arquivo novo

git status => verifica como está o repositório

===============================================================
GIT ADD E COMMIT
===============================================================

git add Readme.md => adiciona o arquivo para o git para ser comitado

git commit -m "mensagem de alteração" => comita o arquivo para o diretório do git

git commit -am <"mensagem"> => adiciona todos os arquivos modificados e commita o arquivo direto

===============================================================
GIT LOG
===============================================================

git log => exibe os arquivos e suas atribuições
Obs: Dentro do git logo existe uma hash e para exibir você utiliza o:

git show <hash => possibilita você verificar informações diversas para o controle de versão

git log --decorate => verifica os arquivos e suas atribuições completas

git log --author="nome do autor" => exibe arquivos de determinado autor

git shortlog => exibe arquivos por autor e suas contribuições e commits

git shortlog -sn => exibe a quantidade de commits e a pessoa

git log --graph => exibe de forma gráfica o que está acontecendo com os branches e suas versões

===============================================================
GIT DIFF
===============================================================

git diff => mostra as últimas mudanças que houveram no arquivo antes de commitar

git diff --name-only =>  lista os arquivos com as últimas mudanças

g s => abreviação de git status, mesma função

===============================================================
DESFAZER ALTERAÇÕES NO ARQUIVO
===============================================================

git checkout <nome_do_arquivo> => desfaz alterações

git reset HEAD <nome_do_arquivo> => desfaz o add para commitar

git reset --soft => desfaz o comit

git reset --mixed => desfaz e o add

git reset --hard => desfaz o commit e todas as alterações do arquivo


===============================================================
CRIANDO CHAVE SSH
===============================================================

ssh-keygen -t rsa -b 4096 -C "seu_email"

cd ~/.ssh => para entrar no diretório da chave

ls => para listar arquivos

cat <nome_da_chave> => para obter a chave

===============================================================
ENVIAR ARQUIVOS PARA REPOSITÓRIO NA WEB
===============================================================

git remote add origin https://github.com/fabiomelg/github-course.git => sincroniza o diretório local com o diretório na web

git remote => exibe os nomes dos diretórios

git remote -v => exibe o endereço dos diretórios

git push -u origin master => envia os dados locais para o diretório web

===============================================================
APAGAR ARQUIVOS
===============================================================

git clean -i <nome_do_arquivo> => apaga um arquivo


