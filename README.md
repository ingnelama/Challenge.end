# Challenge.end
Reto 12- Diccionarios
1. Desarrollar un algoritmo que imprima de manera ascendente los valores (todos del mismo tipo) de un diccionario.

Solución:

```pseudocode
diccionario = {5:"abc", 6:"def", 7:"ghi"}

while 1 < 2:
    if max(diccionario) == max(diccionario):
        print(min(diccionario))
        del diccionario[min(diccionario)]
        if max(diccionario) == min(diccionario):
            print(max(diccionario))
            break
```

2. Desarrollar una función que reciba dos diccionarios como parámetros y los mezcle, es decir, que se construya un nuevo diccionario con las llaves de los dos diccionarios; si hay una clave repetida en ambos diccionarios, se debe asignar el valor que tenga la clave en el primer diccionario.

solución

```pseudocde
def sumar_diccionarios(diccionario_1 : dict, diccionario_2 : dict) -> dict:
    for key() in diccionario_1:
        for key in diccionario_2:
            if key in diccionario_1 == key in diccionario_2:
                diccionarios_sumados = diccionario_2.update(diccionario_1)
                break
            else:
                diccionarios_sumados = diccionario_1.update(diccionario_2)
    return diccionarios_sumados
if __name__ == "__main__":
    diccionario_1 = {5: "a", 6: "b", 7: "c"}
    diccionario_2 = {5: "d", 8: "e", 7: "f"}
    update_diccionarios = sumar_diccionarios(diccionario_1, diccionario_2)
    print(update_diccionarios)    
```
