# Vehicle Rental - Object Oriented Analysis (OOA)

Este repositório foi criado para armazenar os materiais de estudo da disciplina de Análise Orientada a Objetos do terceiro semestre do curso de Análise e Desenvolvimento de Sistemas. Aqui você encontrará uma compilação de teoria, materiais de estudo (anotações da aula e referências) e prática (diagramas UML) desenvolvidas para absorver os conceitos abordados na disciplina.

## Índice

1. [Problema Proposto](#problema-proposto)
    1. [Objetivos](#objetivos)
2. [Teoria](#teoria)
    1. [Referências](#referências-desta-etapa)
    2. [Resumo](#resumo)
3. [Prática](#prática)

### Problema Proposto

Desenvolva um diagrama de classes para um sistema de locação de veículos, levando em consideração os seguintes requisitos:

- A empresa tem muitos automóveis. Cada automóvel tem atributos como número da placa, cor, ano, tipo de combustível, número de portas, quilometragem, RENAVAM, chassi, valor de locação etc.

- Cada carro tem um modelo e uma marca, mas um modelo pode relacionar-se a muitos carros e uma marca pode referir-se a muitos modelos, embora cada modelo só tenha uma marca específica.

- Um carro pode ser alugado por muitos clientes, em momentos diferentes, e um cliente pode alugar muitos carros. É preciso saber quais carros estão locados ou não. Sempre que um carro for locado é preciso armazenar a data e hora de sua locação e, quando for devolvido, a data e hora de devolução.

#### Objetivos

- [ ] Desenvolver um diagrama de classes para um sistema de locação de veículos.

### Teoria

#### Referências desta etapa

- [Modelo Conceitual – O que é e qual a importância?](https://ambscience.com/modelo-conceitual/#:~:text=Um%20Modelo%20Conceitual%20é%20a,distribuição%20espacial%20da%20contaminação%20e)
- [Introdução a modelagem conceitual](https://www.devmedia.com.br/introducao-a-modelagem-conceitual/10793)

#### Resumo

**Modelagem Conceitual:** É a descrição da informação que um sistema irá gerenciar, focando no domínio do problema, não na solução.

**Diferença entre Conceitual e Arquitetura de Software:** A modelagem conceitual não deve ser confundida com a arquitetura do software ou com o modelo de dados. Ela apresenta o problema a ser resolvido, não a solução.

**Gap Semântico:** Refere-se à distância entre o que o usuário solicita e o que o analista de sistemas compreende. É um desafio na análise de sistemas.

**Redução do Gap Semântico:** Com o uso de boas práticas, como a modelagem conceitual e a UML, é possível reduzir essa distância e melhorar a compreensão dos requisitos.

**Representação do Conhecimento Humano:** A modelagem conceitual busca representar o conhecimento humano para diminuir a separação entre usuário e analista.

**Independência de Tecnologia:** Não está vinculado a uma plataforma específica, linguagem de programação ou sistema de banco de dados.

O modelo conceitual descreve:

- Conceitos
  - Um conceito pode ser qualquer entidade que tenha um **significado** para o sistema e que tenha uma necessidade de armazenamento de dados.
  - Um conceito deve ser uma unidade **coesa**.
- Atributos
  - Informações alfanuméricas simples, como números, textos, datas, etc. contidas em cada conceito.
  - Notas (1FN):
    - Um atributo não pode ser multivalorado.
    - Não pode ser composto.
- Associações

### Prática

Durante a concepção do modelo, comecei por destacar os conceitos e atributos mais pertinentes, tendo como referência a visão geral do sistema. Por exemplo, identifiquei os seguintes conceitos e atributos:

![Problema proposto com os conceitos e atributos destacados em laranja](/assets/img/problema_proposto_fase_inicial_conceitos_atributos.png)

Com base nessa representação visual, é possível identificar os seguintes conceitos:

- Automóvel
- Modelo
- Marca
- Cliente
- Aluguel
