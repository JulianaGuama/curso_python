# Instalação

Instale Python 3.x. Você ouvirá falar de Python 2.x mas em janeiro de 2020 parou de receber suporte. É o que chamamos de [end of life](https://www.python.org/doc/sunset-python-2/).

## Instalando no Windows

Atualmente Python está na versão 3.9.0 e você pode encontrar o executável da instalação [neste link](https://www.python.org/downloads/).

Para ~~facilitar~~ configurar corretamente, você ~~pode~~ **DEVE** marcar para add Python no PATH.

![img](images\python_install.png)

* Fique atenta se seu computador está executando a versão 64bit ou 32bit e baixe o instalador compatível (arquivo executável).

A instalação é bastante simples, sendo necessário, basicamente, ~~seguir os passos do wizard até a finalização~~ clicar para instalar. Esse processo irá configurar na máquina o interpretador, as bibliotecas padrão da linguagem e a documentação.

Finalize abrindo o `cmd` do windows e executando:

```shell
python --version
```

Não sabe onde está o `cmd` do windows? Abre o menu e digite `cmd`.

## Instalando no Linux

Abra o Terminal e verifique se o python 3 já está instalado com:

```shell
$ which python3
```

Se o python estiver instalado, o caminho da localização será printado, caso contrário, instale ulizando o apt-get:

```shell
$ sudo apt-get install python3
```

Para mais informações [clique aqui](https://python.org.br/instalacao-linux/)

Para instalar o Python em **MAC**, abra o Terminal e verifique se o python 3 já está instalado com:

```shell
$ which python3
```

Se o python estiver instalado, o caminho da localização será printado, caso contrário, instale baixando o instalador [aqui](https://www.python.org/downloads/) ou utilizando HomeBrew:

1. instala o XCode
2. instala o HomeBrew
3. instala o python:

```shell
$ xcode-select --install
$ /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
$ brew install python3
```

Para mais informações [clique aqui](https://python.org.br/instalacao-mac/)

Finalize executando no terminal:

```shell
$ python --version
```