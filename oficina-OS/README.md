# 🛠️ Oficina Mecânica - Esquema Conceitual  

Este repositório contém o esquema conceitual desenvolvido para o desafio de projeto do bootcamp da [DIO](https://www.dio.me/). O objetivo é modelar um **sistema de controle e gerenciamento de ordens de serviço** em uma oficina mecânica, garantindo organização e eficiência no fluxo de trabalho.  

## 📌 Contexto do Projeto  

A oficina recebe veículos para **reparos** e **revisões periódicas**. Cada serviço é registrado por meio de uma **Ordem de Serviço (OS)**, que detalha:  

- O cliente e seu veículo.  
- A equipe responsável pelo atendimento.  
- A lista de serviços a serem executados.  
- As peças utilizadas na manutenção.  
- O custo baseado na mão de obra e nas peças utilizadas.  
- O status e a previsão de conclusão.  

## 📊 Modelagem Conceitual  

O esquema conceitual foi desenvolvido com base na seguinte narrativa:  

- **Clientes** levam seus veículos à oficina para manutenção.  
- Cada **veículo** possui uma única **Ordem de Serviço (OS)** ativa por vez.  
- A OS contém **múltiplos serviços** que devem ser realizados no veículo.  
- Cada serviço pode exigir **múltiplas peças**, que também são registradas na OS.  
- O custo total da OS é calculado com base na **tabela de referência de mão de obra** e no valor das **peças** utilizadas.  
- A execução dos serviços só ocorre **mediante autorização do cliente**.  
- Os **mecânicos** possuem código, nome, endereço e especialidade.  
- Cada **OS** inclui um número, data de emissão, valor total, status e data prevista de conclusão.  

## 📌 Diagrama da Modelagem  

Neste repositório está o diagrama representando o esquema conceitual do banco de dados:  
