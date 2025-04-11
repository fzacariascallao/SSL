# Trabajo 00 - "Hello, World!" en C

Trabajo resuelto de manera individual por Facundo Zacarías Callao.

## Enunciado
[Trabajo 00-"Hello,World!" en C](https://josemariasola.github.io/ssl/assignments/Ssl%20Assignments.pdf#page=23)

## Hipótesis
1. El programa "hello.c" servirá para probar el compilador y el entorno de desarrollo.
2. GitHub facilitará la gestión de versiones a lo largo del curso.
3. El compilador deberá ser compatible con C23.
4. La redirección de la salida a un archivo .txt servirá para verificar que el programa genera la salida esperada.

## Compilador

- **Compilador seleccionado**: gcc 
- **Versión del compilador**: gcc (GCC) 14.2.1 20250207
- **Versión de C soportada**: C23

Para verificar la versión del compilador se usó el siguiente comando:

```bash
gcc --version
```

Luego para verificar que el compilador soporta C23 se probó con los siguientes comandos:

```bash
gcc -std=c23 hello.c
./a.out
```

Al compilar y ejecutarse correctamente se corroboró que la versión del compilador instalada soporta C23.

## Resultados

El programa funcionó correctamente y se pudo ver la salida del programa tanto en la terminal como en el archivo output.txt (el cual es la salida redireccionada del programa).

Por otra parte, también se logró crear un buen flujo de trabajo usando las herramientas git y GitHub teniendo un seguimiento de las versiones del T.P.

En conclusión, se lograron los objetivos del trabajo y se pudo establecer un buen entorno de desarrollo propio para futuros trabajos.
