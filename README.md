# CSGBD-Indices
Especificação da API para implementação do trabalho da disciplina de CSGB sobre índices.

## 1. Título
Implementação de Estruturas de Indexação: Hash Extensível e Árvore B+
## 2. Objetivo
O objetivo deste trabalho é implementar, em Python ou Java, duas estruturas de dados amplamente utilizadas em sistemas gerenciadores de banco de dados (SGBDs): Hash Extensível e Árvore B+. O foco é compreender o funcionamento interno dessas estruturas, incluindo operações de inserção, busca e remoção, bem como o gerenciamento de páginas/buckets e divisão (split) de blocos.
## 3. Descrição Geral
Os alunos deverão desenvolver uma biblioteca (API) que permita a criação e manipulação de índices utilizando ambas as técnicas citadas. Cada estrutura deve possuir sua própria classe principal e oferecer métodos de interface bem definidos. A implementação deve simular as operações típicas de indexação, mantendo os dados em estruturas de memória (não é necessário persistir em disco, embora seja permitido).
## 4. Requisitos Técnicos
Linguagem: Python 3.x ou Java 17+
Estruturas a implementar: Hash Extensível e Árvore B+
Cada estrutura deve permitir as operações: inserção, busca, remoção e exibição.

## 5. API
Este repositório traz um exemplo de interface em Python e Java. A implementação deve seguir essa estrutura básica.

## 6. Requisitos de Entrega
Prazo final: 12/11/2025.
O trabalho pode ser desenvolvido individualmente ou em duplas.
A equipe deve criar um repositório público no GitHub com o nome sugerido: trabalho-csgbd-indexacao-equipeXX.
Todos os integrantes devem ser colaboradores e os commits devem refletir o progresso real do desenvolvimento.
## 7. Critérios de Avaliação
Funcionamento correto das operações : 3,0
Implementação conforme o modelo teórico: 2,0
Clareza e organização do código: 1,5
Demonstração e exemplos de uso: 1,0
Relatório e documentação: 1,0
Participação e histórico de commits no GitHub: 1,5

## 8. Sugestão de Testes
Os alunos devem testar suas implementações com chaves inteiras (ex: 1 a 50) em ordens aleatórias, incluindo inserções e remoções, mostrando o comportamento de splits e merges.

## 9. Entrega
Os arquivos devem ser enviados em formato .zip contendo: código-fonte, README, prints de execução e o link do repositório GitHub (obrigatório).

## 10. Apresentação do Trabalho
Além da entrega no formato digital e do repositório no GitHub, o trabalho deverá ser apresentado para a professora da disciplina. Durante a apresentação, os alunos deverão demonstrar o funcionamento das estruturas implementadas (Hash Extensível e Árvore B+), explicando o código, as principais decisões de projeto e os resultados obtidos. A apresentação servirá para validar a autoria do trabalho e complementar a avaliação prática. As apresentações ocorrerão nos dias 13 e (se necessário) 14 de novembro. 


