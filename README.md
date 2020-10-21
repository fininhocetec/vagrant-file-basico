![vagrant-2.2.10](https://img.shields.io/badge/vagrant-2.2.10-blue?style=flat-square)

Vagrantfile - Básico
========================

![Capa](virtualbox-plus-vagrant.png "Capa")

## Lab inicial

Um Vagrantfile básico com duas maquinas.


Requisitos
------------

Instalação do VirtualBox como provisor e Vagrant.


Dependências
------------

Não se aplica.

Rodando o Ambiente
-------------------

Tenha certeza de star na pasta onde encontra o Vagrantfile 

    $ vagrant up

Entrando via SSH nos servers:

    $ vagrant ssh server1
      exit

    $ vagrant ssh server2
      exit 

Verificando o status:

    $ vagrante status

    $ vagrant global-status

Desligando e removendo o ambiente:

    $ vagrant halt

    $ vagrant destroy


Informações do Autor
------------------

- Este projeto foi criado por Willdimark Ragazzi Ventura, DevOps Engineer. (<fininho.cetec@gmail.com>)
- Linkedin [Perfil](https://www.linkedin.com/in/willdymark-ragazzi-ventura-ccna-devnetsecops-membro-anppd%C2%AE-a4422617//).
