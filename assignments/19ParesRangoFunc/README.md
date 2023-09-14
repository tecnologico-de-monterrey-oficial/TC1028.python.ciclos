![Tec de Monterrey](../../images/logotecmty.png)
# Pares dentro de un rango
Ciclos - Pares dentro de un rango


Escribe un programa que contenga una función en Python que reciba dos números enteros positivos diferentes a cero que representan los límites de un rango y despliegue los números pares que se encuentran en el rango de menor a mayor (se incluyen los dos límites)

Si no hay pares en el rango dado, se manda el mensaje "No hay pares"



Modifica el programa que se encuentra en la carpeta `src` que se llama
`exercise.py` y que contiene el siguiente código:

```python
def main():
    num = int(input("Valor 1: "))    
    #escribe tu código abajo de esta línea
    pass

if __name__ == '__main__':
    main()
```

La línea `#escribe tu código abajo de esta línea` es un comentario,
el programa la va a ignorar al ejecutarse.

La salida del programa debe de ser solamente el resultado, sin leyendas ni mensajes, debe ser de la siguiente forma:

```
Valor 1: 4
Valor 2: 9
4
6
8
```

```
Valor 1: 3
Valor 2: 3
No hay pares
```

```
Valor 1: 9
Valor 2: 2
2
4
6
8
```

**Nota:** No te preocupes por esta parte del código
`if __name__ == '__main__':` por el momento.
No la vamos a necesitar para este programa, pero es una buena práctica
incluirla y quedará más claro para que sirve en los siguientes ejercicios.

Una vez que termines tu actividad y la hayas probado con
`python -m pytest --tb=short -v`,
subela a tu repositorio en GitHub, con el proceso de commit + push.
