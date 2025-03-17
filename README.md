<img src="doc/logo.png" align="right" height="90" />

# rAthena
![clang](https://img.shields.io/github/actions/workflow/status/rathena/rathena/build_servers_clang.yml?label=clang%20build&logo=llvm) ![cmake](https://img.shields.io/github/actions/workflow/status/rathena/rathena/build_servers_cmake.yml?label=cmake%20build&logo=cmake) ![gcc](https://img.shields.io/github/actions/workflow/status/rathena/rathena/build_servers_gcc.yml?label=gcc%20build&logo=gnu) ![ms](https://img.shields.io/github/actions/workflow/status/rathena/rathena/build_servers_msbuild.yml?label=ms%20build&logo=visualstudio) ![GitHub](https://img.shields.io/github/license/rathena/rathena.svg) ![commit activity](https://img.shields.io/github/commit-activity/w/rathena/rathena) ![GitHub repo size](https://img.shields.io/github/repo-size/rathena/rathena.svg)
> O rAthena é um projeto de desenvolvimento de software colaborativo que gira em torno da criação de um pacote de servidor robusto de RPG on-line para vários jogadores (MMORPG). Escrito em C++, o programa é muito versátil e fornece NPCs, warps e modificações. O projeto é gerenciado em conjunto por um grupo de voluntários localizados em todo o mundo, bem como por uma enorme comunidade que fornece controle de qualidade e suporte. rAthena é uma continuação do projeto eAthena.

[Forum](https://rathena.org/board)|[Discord](https://rathena.org/discord)|[Wiki](https://github.com/rathena/rathena/wiki)|[FluxCP](https://github.com/rathena/FluxCP)|[Crowdfunding](https://rathena.org/board/crowdfunding/)|[Fork and Pull Request Q&A](https://rathena.org/board/topic/86913-pull-request-qa/)
--------|--------|--------|--------|--------|--------

### Table of Contents
1. [Prerequisites](#1-prerequisites)
2. [Installation](#2-installation)
3. [Troubleshooting](#3-troubleshooting)
4. [More Documentation](#4-more-documentation)
5. [How to Contribute](#5-how-to-contribute)
6. [License](#6-license)

## 1. Prerequisites
Before installing rAthena there are certain tools and applications you will need which
differs between the varying operating systems available.

### Hardware
Hardware Type | Minimum | Recommended
------|------|------
CPU | 1 Core | 2 Cores
RAM | 1 GB | 2 GB
Disk Space | 300 MB | 500 MB

### Operating System & Preferred Compiler
Operating System | Compiler
------|------
Linux  | [gcc-6 or newer](https://www.gnu.org/software/gcc/gcc-6/) / [Make](https://www.gnu.org/software/make/)
Windows | [MS Visual Studio 2017 or newer](https://www.visualstudio.com/downloads/)

### Required Applications
Application | Name
------|------
Database | [MySQL 5 or newer](https://www.mysql.com/downloads/) / [MariaDB 5 or newer](https://downloads.mariadb.org/)
Git | [Windows](https://gitforwindows.org/) / [Linux](https://git-scm.com/download/linux)

### Optional Applications
Application | Name
------|------
Database | [MySQL Workbench 5 or newer](http://www.mysql.com/downloads/workbench/)

## 2. Installation 

### Full Installation Instructions
  * [Windows](https://github.com/rathena/rathena/wiki/Install-on-Windows)
  * [CentOS](https://github.com/rathena/rathena/wiki/Install-on-Centos)
  * [Debian](https://github.com/rathena/rathena/wiki/Install-on-Debian)
  * [FreeBSD](https://github.com/rathena/rathena/wiki/Install-on-FreeBSD)

## 3. Troubleshooting

If you're having problems with starting your server, the first thing you should
do is check what's happening on your consoles. More often that not, all support issues
can be solved simply by looking at the error messages given. Check out the [wiki](https://github.com/rathena/rathena/wiki)
or [forums](https://rathena.org/forum) if you need more support on troubleshooting.

## 4. More Documentation
rAthena has a large collection of help files and sample NPC scripts located in the /doc/
directory. These include detailed explanations of NPC script commands, atcommands (@),
group permissions, item bonuses, and packet structures, among many other topics. We
recommend that all users take the time to look over this directory before asking for
assistance elsewhere.

## 5. How to Contribute
Details on how to contribute to rAthena can be found in [CONTRIBUTING.md](https://github.com/rathena/rathena/blob/master/.github/CONTRIBUTING.md)!

## 6. License
Copyright (c) rAthena Development Team - Licensed under [GNU General Public License v3.0](https://github.com/rathena/rathena/blob/master/LICENSE)
