# Processamento de Sinais Biológicos

## Informações gerais do professor, disciplina e ensino:

Este repositório foi criado para o desenvolvimento de materiais que servirão de apoio para as aulas das disciplinas de **Reconhecimento de Padrões** e **Tópicos Avançados em Ciência da Computação 2** do Departamento Acadêmico de Ciência da Computação da Universidade Tecnológica Federal do Paraná, Campus Campo Mourão. O repositório funciona como um caderno interativo que serve para ilustrar exemplos de algoritmos apresentados em aula.

**Professor**: Rodrigo Hübner

**Horário de atendimento (mais conhecido como PAluno)**:
- Segunda-feira das 15:50 - 17:30;
- Terça-feira das 13:50 - 15:30.

## Usando o Jupyter Notebook localmente

### Instalação do Jupyter Notebook e pré-requisitos:

Os bons costumes de programação em `python` nos orienta a desenvolver diferentes projetos em diferentes *virtual environments*. Começamos criando um ambiente virtual python e o ativando:

> Será utilizado comandos baseados em distribuição linux DEB (Debian, Ubuntu, Linux Mint, Elementary, etc) e majoritariamente a versão `>= python 3.5`.

```
$ sudo apt install python3-pip python3-virtualenv
$ mkdir aula && cd aula/
$ virtualenv -p python3 .
$ source bin/activate
```

Com o ambiente virtual `python 3` instalado, é hora de instalar o `Jupyter Notebook`:

```
(aula) $ pip install --upgrade pip
(aula) $ pip install numpy scipy matplotlib scikit-learn jupyter mne
```

### Execução do `Jupyter Notebook`:

```
(aula) $ git clone https://github.com/rodrigohubner/PSB.git && cd PSB/
(aula) $ jupyter notebook
```

## Sequência das aulas

1. Carregamento e preparação de *datasets*;