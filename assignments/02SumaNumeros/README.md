![Tec de Monterrey](../../images/logotecmty.png)
# Suma números

Modifica el programa que se encuentra en la carpeta `src` que se llama
`exercise.py` y que contiene el siguiente código:

```python
def main():
  #escribe tu código abajo de esta línea

if __name__ == '__main__':
    main()
```

La línea `#escribe tu código abajo de esta línea` es un comentario,
el programa la va a ignorar al ejecutarse.

Escribe un programa que sume los números enteros (positivos y negativos) que el usuario teclee y se detenga hasta que el usuario teclee un cero.

#### Entrada
Una secuencia de números enteros positivos o negativos. La secuencia debe terminar con un 0.

#### Salida
La suma de los números tecleados.

#### NOTA IMPORTANTE:
Tu programa NO debe incluir ningún mensaje para pedir los datos y la salida debe coincidir exactamente con el formato y/o tipo de dato que se te pide como salida.

El programa debe funcionar de la siguiente forma:

```
1
2
0
3

100
200
0
300

1
-1
0
0

1
2
3
0
6

```

**Nota:** No te preocupes por esta parte del código
`if __name__ == '__main__':` por el momento.
No la vamos a necesitar para este programa, pero es una buena práctica
incluirla y quedará más claro para que sirve en los siguientes ejercicios.

Una vez que termines tu actividad y la hayas probado con
`python -m pytest --tb=short -v`, subela a tu repositorio en GitHub,
con el proceso de commit + push.
