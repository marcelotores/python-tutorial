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

Também podemos utilizar a função list do próprio Python (built-in function):
```
lista = list([3, 5, 7, 8])
# colchetes obrigatórios
``
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

**Duas formas:**

`del()` : remove qualquer elemento pelo índice

`pop(indice)` : remove qualquer elemento pelo índice, no entanto retorna o valor removido. 

> O método `pop()` quando não especificado o índice, remove o último elemento da lista
> 
`remove()`: o método remove, remove pelo valor.

**Exemplos:**
```
del numeros[1]
# remove o valor de índice 1

numeros.pop(3)
# remove o valor de índice 3

numeros.remove(30)
# remove o valor 30 da lista
```

### Ordenar lista

`sort()`: ordena a lista **permanentemente**
> Pode ser passado um parâmentro para ordenar de forma reversa

`sorted()`: ordena a lista **temporariamente**
> Pode ser passado um parâmentro para ordenar de forma reversa

```
numeros.sort()
# ordena a lista

numeros.sort(reverse=True)
# ordena a lista na ordem reversa

print(sorted(numeros))
# apenas exibe de forma ordenada, mas preserva a lista original
```
### Inverter a Lista
`reverse()`: inverte uma lista. (não ordena em ordem alfabética inversa). Inverte de fato a lista (Permanentente)

```
numeros.inverse()
```

### Tamanho da Lista
`len()`: devolve o tamanho da lista
```
print(len(numeros))
```
## Funções Interessantes

`Range()`: A função range() de Python facilita gerar uma série de números
```
for i in range(1, 5):
  print(i)
  # imprime de 1 a 4
```
Criando uma lista diretamente usando a função `list()`:

```
lista = list(range(1,10))
# não precisa de colchete
```



