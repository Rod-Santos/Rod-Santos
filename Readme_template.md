# Remove Files from Git History 🗑️📜

## Índice 📚

- [Visão Geral](#visão-geral)
- [Tecnologias Utilizadas](#tecnologias-utilizadas-🛠️)
- [Sistemas Operacionais](#sistemas-operacionais-🎛️)
- [Requisitos](#requisitos-📋)
- [Scripts do Projeto](#scripts-do-projeto-📜)
- [Funcionalidades](#funcionalidades-🎯)
- [Configuração](#configuração-⚙️)
- [Como usar o script](#como-usar-o-script)
- [Contato](#criado-por-rodrigo-santos)

## Visão Geral 🌐
Este projeto contém scripts para remover arquivos específicos do histórico de commits de um repositório Git. Os scripts estão disponíveis em Python e Batch.

## Tecnologias Utilizadas 🛠️

<code><img width="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" title="Python"/></code>
<code><img width="40px" src="https://img.icons8.com/ios-filled/50/4a90e2/console.png" title="Batch (Windows)"/></code>
<code><img width="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/gitlab/gitlab-original.svg" title="GitLab"/></code>
<code><img width="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" title="GitHub"/></code>
<code><img width="40px" src="https://img.icons8.com/color/48/000000/amazon-web-services.png" title="AWS"/></code>
<code><img width="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" title="VSCode"/></code>
</br>

## Sistemas Operacionais 🎛️

![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)

## Requisitos 📋



## Scripts do Projeto 📜

O projeto possui dois scripts com propósitos idênticos, mas em linguagens diferentes:

1. `./`: Este script é um arquivo Batch para usuários do Windows. Ele remove arquivos específicos do histórico de commits e força o push das alterações para o repositório remoto.

2. `./`: Este script é um arquivo Python que faz a mesma coisa que o arquivo Batch, mas é mais portátil e pode ser executado em diferentes sistemas operacionais.

## Funcionalidades 🎯

* **Identifica** os arquivos a serem removidos do histórico de commits.
* **Utiliza** o `git-filter-repo` para reescrever o histórico de commits.
* **Força** o push das alterações para o repositório remoto.

## Configuração ⚙️

1. Coloque os nomes dos arquivos que você deseja remover no arquivo `.env`.
2. Execute o script correspondente ao seu sistema operacional.

## Como usar o script 🛠️

1. Salve o script em um diretório de sua escolha.
2. Abra o terminal e navegue até o diretório onde o script foi salvo.
3. Execute o script:
   - Para o script Batch: `*`
   - Para o script Python: `*`

**Criado por Rodrigo Santos**

[![LinkedIn](https://img.icons8.com/nolan/50/linkedin.png)](https://www.linkedin.com/in/rodrigodasilvasantos/) [![GitHub](https://img.icons8.com/nolan/50/github.png)](https://github.com/Rod-Santos)
