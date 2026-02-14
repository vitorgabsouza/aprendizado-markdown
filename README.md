Aprendizado de Markdown

Repositório para aprendizado da linguagem Markdown durante o curso de Git e GitHub ministrado pelo Prof. Gustavo Guanabara.

# Formatações

## Itálico

Para deixar um texto em itálico, utilizamos \* ou \_. Exemplo:

Eu sou o **Vitor** e este é meu perfil no _GitHub_!

## Negrito

Para deixar um texto em negrito, utilizamos \** ou \__. Exemplo:

Eu sou o **Vitor** e este é meu perfil no __GitHub__!

## Riscado (strike)

Para riscar um texto, utilizamos \~~. Exemplo:

Este ~~texto~~ está riscado.

## Formatações misturadas

Para criar formatações misturadas, utilizamos as marcas de forma hierárquica. Exemplo:

Eu sou o _**Vitor**_ e este é meu perfil no _**GitHub**_!

# Listas

## Listas numeradas

Para criar uma lista numerada, colocamos o número seguido de um ponto. Os itens seguirão a sequência. Exemplo:

1. Brasil
2. Argentina
3. Venezuela
4. Chile

## Listas com marcadores

Para criar uma lista com marcadores, utilizamos \* ou \- seguido de um espaço. Exemplo:

- Ir ao mercado
* Ir à farmácia

## Listas de tarefas

Para criar uma lista de tarefas, utilizamos \- \[] ou \- \[x] para itens marcados. Exemplo:

[ ] pão
[x] leite
[ ] manteiga

# Títulos

Para criar um título, podemos usar de uma \# até seis \# para cada nível de título. Exemplo:

# Título 1
## Título 2
### Título 3

# Linhas horizontais

Para criar linhas horizontais, utilizamos \--- ou \***. Exemplo:

Texto antes da linha
---
Texto após a linha

# Imagens

Para inserir uma imagem, utilizamos \!\[]\(), onde a descrição da imagem fica entre os colchetes e o caminho da imagem fica entre os parênteses. Exemplo:

![Calculadora](img/calculator.svg)

# Links

Para inserir um link, utilizamos \[]\(). Exemplo:

[Google](https://www.google.com)

# Trechos de código

## Trechos de código de uma linha

Para inserir trechos de código de uma linha, utilizamos \`. Exemplo:

`alert('Olá, mundo!');`

## Trechos de código com mais de uma linha

Para inserir trechos de código com mais de uma linha, utilizamos \```. Exemplo:

```
alert('Olá, mundo!');
alert('Estou aprendendo Markdown!');
```

# Citações

## Citações externas

Para citações externas, podemos usar \>. Exemplo:

Como ***Cora Coralina*** disse:

> Não lamente o que podia ter 
> e se perdeu por caminhos errados 
> e nunca mais voltou.

## Citações de usuários 

Para citar usuários, utilizamos \@. Exemplo:

Meu perfil é @vitorgabsouza

Para citar Issues, utilizamos \# seguida pelo número da Issue.

# Emojis

Para utilizar emojis, utilizamos \::. Exemplo:

Boas iniciativas merecem aplausos :clap:

# Tabelas

Para criar tabelas, utilizamos \| e \- de forma organizada. Exemplo:

Produto | 	Categoria |	Preço
:---: | :---: | ---:
Coxinha de Frango |	Aperitivo	| R$ 5,00
Macarrão ao Molho de Tomate	| Prato Principal	| R$ 15,00
Sorvete de Creme	| Sobremesa	| R$ 4,50

# Alinhamentos em tabelas

\--- Formatação padrão (esquerda)

\:--- Esquerda

\:---: Centralizado

\---: Direita