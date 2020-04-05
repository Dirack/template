
# TEMPLATE
> <RESUMO>.

<BADGES><TRAVIS CI>[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)

IMAGEM?

DESCRIÇÃO EM DOIS PARÁGRAFOS

[Para mais informações visite o nosso wiki!](https://github.com/Dirack/template/wiki)

## Instalação

Para instalar a Shellinclude basta fornecer permissão de execução aos scripts com _chmod_, assim:

```shell
~$ chmod u+x script.sh
```

E você poderá chamar os scripts como qualquer outro Shell Script, fornecendo o caminho para o script ao
terminal do bash. Exemplo, executando um script do shell em um diretório qualquer:

```śhell
~$ /diretorio/script.sh # Se o script estiver na pasta diretório
~$ ./script # Se o script estiver na pasta atual em que foi aberto o terminal do bash
```

Você também pode chamar os scripts da Shellinclude como se fosse um comando nativo do _bash_. Basta adicionar os scripts
a um diretório listado na sua variável de ambiente $PATH ou adicionar a seguinte linha ao final do seu arquivo _.bashrc_:

```shell
PATH="$PATH:/caminhoParaShellinclude/Shellinclude"
```

## Dependências: 

* **sendemail**: Possibilita enviar emails pelo terminal. Utilizado pelo programa _morse_.

* **Madagascar**: Pacote de processamento símico open source. Roda através de scripts SConstruct baixados e formatados
pelo programa _getscons_ e instalados pelo programa _comp_.

* **lynx**: Permite baixar dados da internet pelo terminal. Utilizado por _getscons_ para baixar os scripts do Madagascar.

## Instalação das dependências

```shell
~$ sudo apt-get install sendemail # Instalar sendemail
~$ sudo apt-get install lynx # instalar lynx
```

A instalação do pacote Madagascar pode ser realizada através do script de instalação [madagainstall](https://github.com/Dirack/Shellinclude/blob/master/madagainstall) disponível a partir da versão 1.2 desta biblioteca.

Para mais detalhes sobre a instalação do pacote Madagascar, consulte a página oficial do pacote em [ahay.org](http://www.ahay.org/wiki/Installation).

Baixe os nossos containers do docker com a [Shellinclude pré-configurada](https://github.com/Dirack/Shellinclude/packages/162773)

## Testes automatizados

<testes>

<docker>

## Lista de Programas

* **suinstall**: Instalar o pacote de processamento sísmico Seismic Unix (SU).
* **lipsum**: Programa para gerar texto aleatório (dummy text) no terminal.
* **madagainstall**: Instalar o pacote de processamento sísmico Madagascar.
* **backup**: Fazer o backup de um arquivo ou de uma lista de arquivos em um arquivo zipado na pasta atual.
* **cabecalho**: Gerar o cabeçalho para um arquivo de programa de uma determinada linguagem de programação com objetivo, nome do programa, programador e etc.
* **comp**: Compilar e adicionar programas escritos em linguagem C a versão local do pacote de processamento sísmico MADAGASCAR.
* **getscons**: Baixar arquivos SConstruct da página do MADAGASCAR para a pasta atual no formato correto do SConstruct.
* **img**: Converter arquivos .vpl (arquivos de imagem do MADAGASCAR) em imagens .jpeg
* **jonas**: Criar atalhos para pastas e aliases permanentes. Os aliases ficarão armazenados em um arquivo $HOME/.aliases.sh.  
* **lembrete**: Armazenar lembretes e idéias no arquivo $HOME/.post
* **morse**: Enviar email pelo terminal.

## Exemplos de uso

Alguns exemplos interessantes e úteis sobre como este projeto pode ser utilizado estão disponíveis em nosso
_[Wiki](https://github.com/Dirack/Shellinclude/wiki)._ 

## Histórico de lançamentos

* [v1.2.2](https://github.com/Dirack/Shellinclude/releases/tag/v1.2.2-beta.1)
    * Versão Beta - Novo programa _suinstall_
* [v1.2.1](https://github.com/Dirack/Shellinclude/releases/tag/v1.2.1-beta.1)
    * Versão Beta - Novo programa _lipsum_
* [v1.2](https://github.com/Dirack/Shellinclude/releases/tag/v1.2-beta.1)
    * Versão Beta - Novo programa _madagainstall_
* [v1.1.2](https://github.com/Dirack/Shellinclude/releases/tag/v1.1.2)
    * Versão Estável - Correção de bugs no programa cabecalho
* [v1.1.1](https://github.com/Dirack/Shellinclude/releases/tag/v1.1.1)
    * Versão Estável - Correção de bugs do prgrama jonas
* [v1.1](https://github.com/Dirack/Shellinclude/releases/tag/v1.1)
    * Versão Estável
* [v1.0](https://github.com/Dirack/Shellinclude/releases/tag/v1.0-beta.1)
    * Versão Beta com os principais scripts

[Visualize o histórico de modificações detalhado](https://github.com/Dirack/Shellinclude/wiki/Hist%C3%B3rico-de-vers%C3%B5es)

## Sobre

Rodolfo Dirack – [@dirack](https://github.com/Dirack) – rodolfo_profissional@hotmail.com

Distribuído sob a licença GPL3. Veja `LICENSE` para mais informações.

[Shellinclude main page](https://github.com/Dirack/Shellinclude)

## Contribuição

1. Faça o _fork_ do projeto (<https://github.com/Dirack/Shellinclude/fork>)
2. Crie uma _branch_ para sua modificação (`git checkout -b feature/suaFeature`)
3. Faça o _commit_ (`git commit -am 'Add some fooBar'`)
4. _Push_ (`git push origin feature/fooBar`)
5. Crie um novo _Pull Request_

#### Importante: O histórico de suas modificações deve ser claro, com mensagens de commit de um a dois parágrafos descrevendo cada modificação. _Pull Requests_ com histórico de commits insuficiente serão rejeitados.
