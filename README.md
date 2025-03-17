<img src="doc/logo.png" align="right" height="90" />

# rAthena
![clang](https://img.shields.io/github/actions/workflow/status/rathena/rathena/build_servers_clang.yml?label=clang%20build&logo=llvm) ![cmake](https://img.shields.io/github/actions/workflow/status/rathena/rathena/build_servers_cmake.yml?label=cmake%20build&logo=cmake) ![gcc](https://img.shields.io/github/actions/workflow/status/rathena/rathena/build_servers_gcc.yml?label=gcc%20build&logo=gnu) ![ms](https://img.shields.io/github/actions/workflow/status/rathena/rathena/build_servers_msbuild.yml?label=ms%20build&logo=visualstudio) ![GitHub](https://img.shields.io/github/license/rathena/rathena.svg) ![commit activity](https://img.shields.io/github/commit-activity/w/rathena/rathena) ![GitHub repo size](https://img.shields.io/github/repo-size/rathena/rathena.svg)
> O rAthena é um projeto de desenvolvimento de software colaborativo que gira em torno da criação de um pacote de servidor robusto de RPG on-line para vários jogadores (MMORPG). Escrito em C++, o programa é muito versátil e fornece NPCs, warps e modificações. O projeto é gerenciado em conjunto por um grupo de voluntários localizados em todo o mundo, bem como por uma enorme comunidade que fornece controle de qualidade e suporte. rAthena é uma continuação do projeto eAthena.

[Forum](https://rathena.org/board)|[Discord](https://rathena.org/discord)|[Wiki](https://github.com/rathena/rathena/wiki)|[FluxCP](https://github.com/rathena/FluxCP)|[Crowdfunding](https://rathena.org/board/crowdfunding/)|[Fork and Pull Request Q&A](https://rathena.org/board/topic/86913-pull-request-qa/)
--------|--------|--------|--------|--------|--------

### Table of Contents
1. [Pré-requisitos](#1-prerequisites)
2. [Instalação](#2-installation)
3. [Solução de problemas](#3-troubleshooting)
4. [Mais documentação](#4-more-documentation)
5. [Como contribuir](#5-how-to-contribute)
6. [Licença](#6-license)

## 1. Pré-requisitos
Antes de instalar o rAthena(Servidor), você precisará de determinadas ferramentas e aplicativos, que
diferem entre os vários sistemas operacionais disponíveis.

### Hardware
Tipo de Hardware | Minimo | Recomendado
------|------|------
CPU | 1 Core | 2 Cores
RAM | 1 GB | 2 GB
SSD | 300 MB | 500 MB

### Sistema operacional e compilador preferido
Sistema operacional | Compilador
------|------
Linux  | [gcc-6 ou maior](https://www.gnu.org/software/gcc/gcc-6/) / [Make](https://www.gnu.org/software/make/)
Windows | [MS Visual Studio 2017 ou maior](https://www.visualstudio.com/downloads/)

### Aplicativos necessários
Nome do aplicativo

------|------

Database | [MySQL 5 ou maior](https://www.mysql.com/downloads/) / [MariaDB 5 or newer](https://downloads.mariadb.org/)
Git | [Windows](https://gitforwindows.org/) / [Linux](https://git-scm.com/download/linux)

### Aplicativos opcionais
Nome do aplicativo

------|------

Database | [MySQL Workbench 5 ou maior](http://www.mysql.com/downloads/workbench/)

## 2. Instalação 

### Instruções completas de instalação
  * [Windows](https://github.com/rathena/rathena/wiki/Install-on-Windows)
  * [CentOS](https://github.com/rathena/rathena/wiki/Install-on-Centos)
  * [Debian](https://github.com/rathena/rathena/wiki/Install-on-Debian)
  * [FreeBSD](https://github.com/rathena/rathena/wiki/Install-on-FreeBSD)

## 3. Solução de problemas

Se estiver tendo problemas para iniciar o servidor, a primeira coisa que você deve fazer é verificar o que está acontecendo nos consoles.
fazer é verificar o que está acontecendo em seus consoles. Na maioria das vezes, todos os problemas de suporte
podem ser resolvidos simplesmente observando as mensagens de erro fornecidas. Dê uma olhada em [wiki](https://github.com/rathena/rathena/wiki)
ou [forums](https://rathena.org/forum) se você precisar de mais suporte para a solução de problemas.

## 4. Mais documentação
O rAthena tem uma grande coleção de arquivos de ajuda e exemplos de scripts NPC localizados no diretório /doc/
localizado no diretório /doc/. Eles incluem explicações detalhadas dos comandos de script de NPC, atcommands (@),
permissões de grupo, bônus de itens e estruturas de pacotes, entre muitos outros tópicos. Nós
recomendamos que todos os usuários dediquem um tempo para examinar esse diretório antes de pedir
assistência em outro lugar.

## 5. Como contribuir
Detalhes sobre como contribuir com o rAthena podem ser encontrados em [CONTRIBUTING.md](https://github.com/rathena/rathena/blob/master/.github/CONTRIBUTING.md)!

## 6. License
Copyright (c) rAthena Development Team - Licensed under [GNU General Public License v3.0](https://github.com/rathena/rathena/blob/master/LICENSE)
