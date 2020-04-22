<h1 align="center">
    <img alt="moss" title="#moss" src=".github/logo.svg" width="250px" />
</h1>

<h4 align="center"> 
	moss (Modern Operating Systems Simulators)
</h4>
<p align="center">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/cicerocruz/SimuladorSistemasDEArquivos?color=%23FC943D">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/cicerocruz/SimuladorSistemasDEArquivos?color=%23FC943D">
	
  <a href="https://www.linkedin.com/in/cicerocruz/">
    <img alt="Made by Cicero Cruz" src="https://img.shields.io/badge/made%20by-C%C3%ADcero%20Cruz-%23FC943D">
  </a>

  <a href="https://github.com/cicerocruz/SimuladorSistemasDEArquivos/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/cicerocruz/SimuladorSistemasDEArquivos?color=%23FC943D">
  </a>

  <a href="https://github.com/cicerocruz/SemanaOmnistack11/issues">
    <img alt="Repository issues" src="https://img.shields.io/github/issues/cicerocruz/SimuladorSistemasDEArquivos?color=%23FC943D">
  </a>

  <img alt="License" src="https://img.shields.io/badge/license-GNU-brightgreen?color=%23FC943D">
</p>

## Índice

<p align="center">
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-requisitos">Requisitos</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-layout">Layout</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-conceitos">Lições Aprendidas</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-contato">Entre em Contato</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-license">License</a>
</p>

<br>

## 🔧 Tecnologias

Este projeto foi desenvolvido com as seguintes tecnologias:

- [Java](https://nodejs.org/en/) [💜]()

## 🔧 Requisitos

- Java JDK Instalado na Máquina

## 💻 Instalando e Executando o Simulador
Crie o diretório C:\moss\filesys>
Salve os arquivos deste repositório neste diretório

### Execute os Comandos para compilar o projeto

Abra o Prompt de comando e execute os comandos dentro da pasta C:\moss\filesys> 
set CLASSPATH=.
javac *.java

### Teste o Simulador

Abra o Prompt de comando e execute os comandos dentro da pasta C:\moss\filesys> 

#### Execute o Comando
java mkfs filesys.dat 256 16

#### Saida Esperada
block_size: 256
blocks: 16
super_blocks: 1
free_list_blocks: 1
inode_blocks: 3
data_blocks: 11
block_total: 16

#### Execute o Comando
java mkdir /root

#### Execute o Comando
java ls /

#### Saida Esperada
/:
    0         48 .
    0         48 ..
    1         32 root
total files: 3

#### Execute o Comando
echo "Olá Mundo!" | java tee /root/t.lis

#### Saida Esperada
Olá Mundo!

#### Execute o Comando
java ls /root

#### Saida Esperada
/root:
    1         48 .
    0         48 ..
    2        219 t.lis
total files: 3

#### Execute o Comando
java cat /root/t.lis

#### Saida Esperada
BitBlock.java
Block.java
DirectoryEntry.java
FileDescriptor.java
FileSystem.java

## 📌 Conceitos

Sistemas de Arquivos, Sistemas de Diretórios

## 🔖 Layout


## 💬 Contato

Obrigado por chegar até aqui! 

[*Entre em contato comigo*](https://www.linkedin.com/in/cicerocruz/)

## :memo: License Original e Copyright

©Copyright 2001, Prentice-Hall, Inc. 

Este programa é um software livre; você pode redistribuí-lo e / ou modificá-lo sob os termos da GNU General Public License, publicada pela Free Software Foundation; a versão 2 da licença ou (a seu critério) qualquer versão posterior.

Este programa é distribuído na esperança de que seja útil, mas SEM QUALQUER GARANTIA; sem sequer a garantia implícita de COMERCIALIZAÇÃO ou ADEQUAÇÃO A UM OBJETIVO ESPECÍFICO. Veja a Licença Pública Geral GNU para mais detalhes.

Você deveria ter recebido uma cópia da Licença Pública Geral GNU junto com este programa (consulte copying.txt); caso contrário, escreva para a Free Software Foundation, Inc., 59 Temple Place, Suite 330, Boston, MA 02111-1307 EUA

## :memo: License

Este projeto está sob a licença GNU, fazendo parte da Disciplina de Sistemas Operacionais

**[⬆ voltar ao topo](#Índice)**
