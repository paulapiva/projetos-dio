# 🛒 E-commerce - Modelagem de Dados  

Este repositório contém o esquema conceitual do banco de dados para um sistema de **e-commerce**, desenvolvido como parte do desafio de projeto do bootcamp da [DIO](https://www.dio.me/).  

## 📌 Contexto do Projeto  

O objetivo é criar um **modelo de dados eficiente** para gerenciar pedidos, clientes, produtos e entregas dentro de uma plataforma de comércio eletrônico. O esquema foi elaborado para garantir **organização, escalabilidade e integridade dos dados**.  

## 📊 Modelagem Conceitual  

A modelagem do banco de dados foi criada para atender os seguintes requisitos:  

- **Clientes** podem ser **Pessoa Física (PF)** ou **Pessoa Jurídica (PJ)**, mas nunca ambos ao mesmo tempo.  
- Cada **pedido** está associado a um cliente e contém um ou mais produtos.  
- Um pedido pode ter **múltiplas formas de pagamento** registradas.  
- O processo de **entrega** inclui um **status** e um **código de rastreio**.  
- O estoque é atualizado conforme os pedidos são realizados.  
- Os produtos podem ser fornecidos por diferentes **fornecedores** ou **terceiros**.  

## 📌 Diagrama da Modelagem  

Neste repositório está o diagrama representando o esquema conceitual do banco de dados:  
