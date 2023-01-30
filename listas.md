# Listas em Python

Uma lista é uma coleção de itens em uma ordem em particular.

### Criar lista
Para criar uma lista basta definir o nome da lista e conlchetes logo após:

```
numeros = [2, 4, 5]
```
Pode-se também definir uma lista vazia.
```
letras = []
```
### Acessar ítens da lista

Acesse os intens da lista pelo índice:

```
valor = numeros[2]
print(valor)
## imprime 5
```
### Alterar elementos da lista
Altere simplesmente atribuindo um novo valor:
```
numeros[1] = 300
```
### Acrescentar elementos na lista

**Duas formas:**

`append(elemento)` : acrescenta o elemento ao final da lista

`insert(indice, elemento)` : acrescenta em qualquer posição

**Exemplos:**

```
numeros.append(4) 
# acrescenta o valor 4 ao final da lista

numeros.insert(2, 30)
# acrescenta o valor 30 na posição 2 da lista
```
### Remover valores da lista
Duas formas:
del() : remove qualquer elemento pelo índice
pop(indice) : remove qualquer elemento pelo índice, no entanto retorna o valor removido. 
> O método `pop()` quando não especificado o índice, remove o último elemento da lista
remove(): o método remove, remove pelo valor.

Exemplos:
```
del numeros[1]
# remove o valor de índice 1

numeros.pop(3)
# remove o valor de índice 3

numeros.remove(30)
# remove o valor 30 da lista
```
