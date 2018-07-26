# Desafio front-end Seventh

## Introdução

Esse documento descreve um desafio técnico a ser elaborado pelo candidato à vaga de desenvolvedor front-end na Seventh Ltda. O desafio consiste em desenvolver um front-end Web para uma API já existente de um sistema do tipo "carrinho de compras". 

## Duração

O desafio foi preparado para exigir do candidato um máximo de 8 horas de trabalho.

## O que será avalidado?

A capacidade do candidato em entregar um software funcional e com qualidade. 

## Overview

O s-shop é um site de compras, que possui um admin simples para cadastro de produtos
e listagens de compras.

## Desafio

O desafio consiste em criar uma aplicação front-end que o usuário possa escolher
os produtos e adicionar em uma cesta. A cesta não pode ser limpa ao fazer o reload
da página.

![home](images/home.png)

Na página da cesta, deve ser obrigatório adicionar um nome para prosseguir com a compra,
o usuário pode remover e mudar a quantidade de itens da cesta.

![home](images/cesta.png)

## Admin

Na seção administrativa devem existir duas páginas:

### A página de produtos

Deve ser possível:
adicionar, alterar e excluir produtos.

![home](images/admin_product.png)

### A página de compras

Esta página deve apenas listar as compras.

![home](images/compras.png)

## Tecnologias

### obrigátorias

- Angular.js +v1.5.x

### Desejáveis

- Angular.js Material para versão +1.x.x
- scss para processador de css.

### Opcionais

- Gulp
- Webpack

A api para o test se encontra em [https://s-shop-test.herokuapp.com/](https://s-shop-test.herokuapp.com/)
a documentação da api se encontra [aqui](https://s-shop-docs.netlify.com/).
