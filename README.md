# Programação Avançada

Atividade padrão de projeto sobre o padrão de projeto **Composite**.

## Conteúdos

1. [Classificação](https://github.com/igorgodoy/cco-programacao-avancada-composite#classifica%C3%A7%C3%A3o)
2. [Intenção](https://github.com/igorgodoy/cco-programacao-avancada-composite#inten%C3%A7%C3%A3o)
3. [Motivação](https://github.com/igorgodoy/cco-programacao-avancada-composite#motiva%C3%A7%C3%A3o)
4. [Aplicação](https://github.com/igorgodoy/cco-programacao-avancada-composite#aplica%C3%A7%C3%A3o)
5. [Estrutura](https://github.com/igorgodoy/cco-programacao-avancada-composite#estrutura)
6. [Implementação](https://github.com/igorgodoy/cco-programacao-avancada-composite#implementa%C3%A7%C3%A3o)

## Composite

### Classificação

- O padrão de projeto **Composite** é definido por sua característica de composição hierarquica (semelhante a uma árvore) onde é possível reprensentar um objeto através da composição de outros objetos similares. Além do mais, é possível trabalhar com todos estes objetos como um único objeto, singular.

### Intenção

- Compor objetos em estruturas de árvore para representarem hierarquias parte-todo.

### Motivação

- O padrão **Composite** descreve como usar a composição recursiva de maneira que os clientes não tenham que fazer a distinção de como tratar objetos primitivos e objetos recipientes. A chave para isso está na utilização de uma classe abstrata que representa estes objetos.

### Aplicação

- Este padrão é comumente utilizado para representar hierarquias de componentes em *User Interfaces*. Um cadastro de usuário que deve conter componentes/objetos filhos como um endereço, por exemplo, pode ser desenhado utilizando este padrão de projeto.

### Estrutura

- A estrutura de um **Composite** é, de forma geral, a composição de um objeto por várias "partes", ou seja, outros objetos. Este [diagrama](https://sparxsystems.com/images/screenshots/uml2_tutorial/CP01.GIF) representa um componente desenhado utilizando este padrão de projeto.

### Implementação

- [Example](https://github.com/igorgodoy/cco-programacao-avancada-composite/tree/master/example).
