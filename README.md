# Vehicle Rental - Object Oriented Analysis (OOA)

Este repositório foi criado com o objetivo de armazenar e versionar o diagrama de classes desenvolvido para o desafio proposto na disciplina de Análise Orientada a Objetos do terceiro semestre do curso de Análise e Desenvolvimento de Sistemas.

## Problema Proposto

O desafio consiste na criação de um diagrama de classes para um sistema de locação de veículos. O diagrama representa as entidades principais do sistema, seus atributos e relacionamentos, fornecendo uma visão geral da estrutura e das interações entre os elementos do sistema.

- A empresa tem muitos automóveis. Cada automóvel tem atributos como número da placa, cor, ano, tipo de combustível, número de portas, quilometragem, RENAVAM, chassi, valor de locação etc.

- Cada carro tem um modelo e uma marca, mas um modelo pode relacionar-se a muitos carros e uma marca pode referir-se a muitos modelos, embora cada modelo só tenha uma marca específica.

- Um carro pode ser alugado por muitos clientes, em momentos diferentes, e um cliente pode alugar muitos carros. É preciso saber quais carros estão locados ou não. Sempre que um carro for locado é preciso armazenar a data e hora de sua locação e, quando for devolvido, a data e hora de devolução.

### Objetivos

- [x] Desenvolver um diagrama de classes para um sistema de locação de veículos.

## Tecnologias Utilizadas

Para a criação do diagrama de classes, foram utilizadas ferramentas de modelagem UML, como o PlantUML, juntamente com um editor de texto ou IDE para escrever o código do diagrama.

- [PlantUML - Getting Started](https://plantuml.com/)

## Estrutura do Diagrama de Classes

O diagrama de classes está organizado da seguinte forma:

- Classes representando as entidades principais do sistema, como Cliente, Veículo, Locação, etc.
- Atributos associados a cada classe, representando as características ou propriedades das entidades.
- Relacionamentos entre as classes, indicando as associações entre as entidades e o tipo de relação (agregação, composição, associação simples).

![Diagrama de classes simples de um sistema de locação de veículos](/assets/img/diagrama_locacao_veiculos.png)

## Instruções de Uso

1. Abra o arquivo [diagrama_locacao_veiculos.puml](/diagrama_locacao_veiculos.puml) do diagrama de classes em uma ferramenta de modelagem UML compatível, como o PlantUML ou uma IDE que suporte visualização de diagramas UML.
2. Analise a estrutura do diagrama, observando as classes, atributos e relacionamentos representados.
3. Utilize o diagrama como referência durante o desenvolvimento do sistema, garantindo que a implementação siga a estrutura e as relações definidas.
