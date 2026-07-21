# Linux Administration Lab for Cloud & DevOps

Este repositório documenta um laboratório prático de Linux realizado durante minha jornada de estudos em DevOps.

O objetivo foi simular tarefas comuns executadas por administradores Linux e engenheiros DevOps em um ambiente AWS, reforçando conceitos fundamentais de administração de sistemas.

---

## Objetivo

Praticar operações essenciais de administração Linux em uma instância EC2, incluindo gerenciamento de usuários, permissões, sistema de arquivos, manipulação de arquivos e gerenciamento de armazenamento com Amazon EBS.

---

## Tecnologias utilizadas

* Linux
* AWS EC2
* Amazon EBS
* Bash
* Vim

---

## Habilidades praticadas

* Gerenciamento de usuários e grupos
* Permissões e ownership (`chmod`, `chown` e `chgrp`)
* Organização do sistema de arquivos
* Manipulação de arquivos e diretórios
* Caminhos absolutos e relativos
* Busca e edição de arquivos
* Administração básica do sistema
* Criação e gerenciamento de sistemas de arquivos
* Montagem e desmontagem de volumes EBS

---

# Desafio

O laboratório consiste em executar uma sequência de atividades práticas, simulando situações reais encontradas no dia a dia de um administrador Linux.

### Parte 1 — Usuários e grupos

* Criar usuários e definir senhas.
* Criar grupos.
* Alterar grupos primários e secundários.
* Alterar proprietário e grupo de arquivos.

### Parte 2 — Sistema de arquivos

* Criar estruturas de diretórios.
* Criar arquivos.
* Mover arquivos utilizando caminhos absolutos e relativos.
* Renomear arquivos.
* Remover arquivos e diretórios.

### Parte 3 — Manipulação de texto

* Escrever conteúdo diretamente pelo terminal.
* Editar arquivos utilizando Vim.
* Buscar e substituir palavras.
* Duplicar linhas utilizando comandos do editor.

### Parte 4 — Administração do sistema

* Localizar arquivos.
* Contar arquivos do sistema.
* Consultar informações do `/etc/passwd`.
* Verificar utilização de disco.

### Parte 5 — Armazenamento na AWS

* Criar um volume Amazon EBS.
* Anexar o volume à instância EC2.
* Criar um sistema de arquivos.
* Montar o volume em `/data`.
* Validar a montagem com `df -h`.
* Criar arquivos no novo volume.
* Desmontar e remover o volume.

### Parte 6 — Limpeza do ambiente

* Remover usuários e grupos criados.
* Excluir diretórios e arquivos do laboratório.
* Desmontar o sistema de arquivos.
* Excluir o volume EBS.
* Encerrar a instância EC2.

---

## O que aprendi

Este laboratório reforçou conceitos fundamentais de Linux que fazem parte da rotina de profissionais de Cloud, Infraestrutura e DevOps.

Embora as tarefas sejam relativamente simples quando analisadas individualmente, executá-las em sequência ajuda a desenvolver familiaridade com o terminal, compreender melhor o funcionamento do sistema operacional e ganhar confiança para administrar servidores Linux.

---

## Como executar

1. Crie uma instância Linux na AWS (EC2).
2. Conecte-se como usuário `root` ou utilizando `sudo`.
3. Execute todas as etapas do desafio.
4. Ao final, realize a limpeza completa do ambiente, removendo usuários, grupos e recursos criados.

---

## Status

✅ Laboratório concluído com sucesso.
