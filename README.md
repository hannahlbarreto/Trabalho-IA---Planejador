# Trabalho-IA---Planejador

# Planejador de Blocos com Inteligência Artificial

Este projeto foi desenvolvido como parte da disciplina de Inteligência Artificial na Universidade Federal do Amazonas. O objetivo principal é simular um planejador automático para empilhar blocos de diferentes tamanhos, respeitando restrições de empilhamento, estabilidade e movimento.

## Descrição

A aplicação permite definir estados iniciais e finais do mundo dos blocos, e, com base em regras e restrições lógicas, gera um plano de ações viável para alcançar o objetivo. A implementação utiliza **Prolog** para raciocínio lógico e geração de planos.

## Funcionalidades

- Representação do conhecimento sobre o mundo dos blocos;
- Definição de estados válidos e inválidos;
- Aplicação de restrições como:
  - Tamanho dos blocos;
  - Estabilidade e empilhamento;
  - Impossibilidades físicas (como flutuar ou se sobrepor);
- Planejamento automático de ações utilizando lógica declarativa;
- Exemplos de execução em linguagem natural e em código Prolog.

## Tecnologias Utilizadas

- **Prolog** – para lógica de planejamento e representação de conhecimento;
- **ChatGPT** – apoio na modelagem de conceitos e estruturação do raciocínio;
- **PDF** com documentação explicativa sobre situações simuladas e planos gerados.

## Como Funciona

O planejador recebe uma configuração inicial dos blocos e um estado final desejado. A partir disso, verifica possíveis ações válidas e gera um plano passo a passo para reorganizar os blocos até atingir a meta, sempre obedecendo às regras estabelecidas.

## Execução

1. Instale um interpretador Prolog, como o [SWI-Prolog](https://www.swi-prolog.org/);
2. Abra o arquivo `.pl` com o código do planejador;
3. Carregue o arquivo no interpretador;
4. Execute as consultas definidas para gerar os planos de ação.

## Autores

- Hannah Lisboa Barreto 
- Matheus Rocha Canto  
- Paulo Vitor de Castro Freitas

---
