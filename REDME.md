Artefatos:
 cursos 
 desafios de  codigo 
 desafios de projetos 
 Mentorias 
 Certificados 

LEARNIG
 Lógica
 Especialistas
 Aprendizado
 Reconhecimento
 Notoriedade

HERO
 Humanidade
 Experiências 
 Rooms
 Oportunidades

ACT
 Aquisição
 Construção 
 Transição

# Sistema de Versionamento de Código com Git e GitHub

## Introdução

O sistema de versionamento de código é essencial para o desenvolvimento colaborativo de software. Permite que múltiplos desenvolvedores trabalhem simultaneamente em um projeto, sem interferir no trabalho um do outro. Entre os sistemas de versionamento, o Git é o mais popular, e o GitHub é uma plataforma de hospedagem de código que utiliza o Git, oferecendo uma interface gráfica amigável e recursos adicionais.

## O que é Git?

Git é um sistema de controle de versão distribuído, criado por Linus Torvalds, o mesmo desenvolvedor do Linux. Git permite que você rastreie as alterações feitas no código, reverta para versões anteriores, crie ramificações (branches) para experimentar novas funcionalidades em separado e muito mais.

## Instalando o Git

Para começar a usar o Git, você precisa instalá-lo em seu sistema:

- **Windows**: Baixe o instalador do [site oficial](https://git-scm.com/).
- **macOS**: Instale pelo terminal com `brew install git` se tiver o Homebrew, ou baixe do [site oficial](https://git-scm.com/).
- **Linux**: Use o gerenciador de pacotes da sua distribuição, por exemplo, `sudo apt-get install git` para sistemas baseados em Debian.

## Configurando o Git

Após a instalação, abra o terminal e configure seu nome de usuário e e-mail:

```bash
git config --global user.name "Seu Nome"
git config --global user.email "seuemail@exemplo.com"
```

Estas informações serão utilizadas em seus commits.

## Iniciando um Repositório Git

Para começar a versionar seus projetos com o Git, você deve inicializar um repositório. Navegue até a pasta do seu projeto no terminal e digite:

```bash
git init
```

Isso criará um novo subdiretório chamado `.git`, onde o Git armazena os metadados e a base de dados do repositório.

## Trabalhando com Repositórios Remotos

O GitHub é uma plataforma baseada na web para hospedagem de código usando o Git. Para subir seu repositório local para o GitHub, você precisa criar um repositório remoto no GitHub e vinculá-lo ao seu repositório local.

1. Crie uma conta no [GitHub](https://github.com/).
2. No GitHub, clique em "New repository" para criar um novo repositório.
3. Nomeie seu repositório e clique em "Create repository".
4. Copie o URL do repositório criado.
5. No terminal, dentro da pasta do seu projeto, vincule o repositório local ao remoto:

```bash
git remote add origin URL_DO_SEU_REPOSITORIO
```

6. Envie seu código para o GitHub:

```bash
git push -u origin master
```

## Principais Comandos do Git

- `git status`: Verifica o status atual do repositório.
- `git add`: Adiciona arquivos à área de staging.
- `git commit`: Cria um commit com os arquivos da área de staging.
- `git push`: Envia os commits locais para o repositório remoto.
- `git pull`: Atualiza o repositório local com as alterações do repositório remoto.
- `git branch`: Gerencia branches.
- `git checkout`: Troca entre branches ou restaura arquivos do diretório de trabalho.

## Conclusão

Git e GitHub são ferramentas indispensáveis para o desenvolvimento moderno de software. Aprender a utilizá-los não só facilitará seu trabalho em projetos individuais e em equipe, mas também ampliará suas oportunidades no mundo do desenvolvimento de software.
