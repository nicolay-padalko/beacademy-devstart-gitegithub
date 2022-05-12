# Git e GitHub

Instalação e comandos básicos do GIT.

- O Git é um sistema de versionamento de projetos.
  Onde mudanças e features pode ser implamentadas de forma incremental e compartilhada com a equipe.

- GitHub é uma plataforma de hospedagem de repositórios GIT.
  Existem outras plataformas como o GitLab, BitBuckett entre outras.

# Instalação

- Para instalar o Git acessar o site - https://git-scm.com/about

Instala o Git na sua maquina local e permite o uso em repositórios locais.

- https://github.com/ - Criar um perfil na plataforma. Permite a hospedagem e compartilhamento de repositórios.

# Comandos

Após a instalação, configurar o email e usúario e email com o comando git config. Executamos apenas uma vez após a instalação.

- git config --global user.name "José Silva"
- git config --global user.email silva@mail.com

Duvidas e ajudas.

- git help

Inicializar o Git no seu projeto.

- git init

# Comandos Básicos

- git add

passar a monitorar um novo arquivo.

- git status

monitirar o estado dos arquivos

- git diff

mostra o que foi alterado em determinado arquivo.

- git commit - m "Inicio projeto"

adicona os arquivos e um commit com uma mensagem.

- git reset

usado para desfazer modificações.

- git rm

remove um arquivo do monitoramento.

# Branch

- git branch

Cria uma versão do repositório. Usado para adicionar funcionalidades - Criamos uma branch login, que quando testada e finalizada pode ser mergeada na branch master.

- git checkout

Usado para trocar de branch, pode ser concatenado com -b para troca e criação do branch.

- git checkout -b "login"

Cria e e muda para o branch login.

- git merge

Usadao para unir uma brach no branch master.

- git mergetool

Ferramenta gráfica que ajuda na resolução de conflitos.

- git log

Mostra um histórico dos commits.

- git stash

Armazena suas alterações que não estão prontas para serem comintadas. Permitindo que você troque de branch.

# Compartilhar projetos

- git fetch

Pega todos os dados de um repositório remoto.

- git pull

Pega todas as alterações no arquivos remosto para o repositório local.

- git push

Transfer arquivos do seu repositório para um repositório remoto.
