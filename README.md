# Classificador de Nível de Herói

## Descrição do Projeto
Este projeto consiste em um programa simples em Python que solicita ao usuário o nome e a quantidade de experiência (XP) de um herói. Com base na quantidade de XP inserida, o programa determina o nível do herói e exibe uma mensagem indicando o nível alcançado.

## Como Usar
1. Clone o repositório para o seu ambiente local:

git clone https://github.com/rfonseca1985/DesafioClassificadorDeNivelDeHeroi
cd classificador-de-heroi

Execute o programa usando um interpretador Python:
python classificador_heroi.py


Insira o nome do herói e a quantidade de XP quando solicitado.

O programa exibirá uma mensagem indicando o nível do herói com base na quantidade de XP inserida.

Critérios de Classificação
Se XP for menor do que 1.000: Ferro
Se XP for entre 1.001 e 2.000: Bronze
Se XP for entre 2.001 e 5.000: Prata
Se XP for entre 5.001 e 7.000: Ouro
Se XP for entre 7.001 e 8.000: Platina
Se XP for entre 8.001 e 9.000: Ascendente
Se XP for entre 9.001 e 10.000: Imortal
Se XP for maior ou igual a 10.001: Radiante

Exemplo de Saída:

Digite o nome do herói: Super Herói
Digite a quantidade de experiência do herói: 6000
O Herói de nome Super Herói está no nível de Ouro