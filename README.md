# Proyecto programación de computadores: Juego de ahorcado en python
## Grupo los 7 pecados de la programación:
### Steffy Geraldine Fernández González
### Andrés Felipe Sánchez Gómez
### Nilson Daniel Dueñas López

[![Logo-Blood-Small.png](https://i.postimg.cc/2ytcCvyY/Logo-Blood-Small.png)](https://postimg.cc/QKpkbFcY)

## Base de datos
#### La base de datos se creó en Excel, guardándose como archivo .csv para ser importado en python, luego, se crearon dataframes con la librería 'pandas' y por último, se creó una función para que se escoja una palabra aleatoria dentro de una categoría de palabras elegida por el usuario.
```mermaid
flowchart TD;
    A(Elección de categoría de palabras por el usuario)
    A-->B[Se crea una base de datos de 1000 palabras y de 10 categorías en Excel];
    B-->C[Se importan las categorías como archivos .csv];
    C-->D[Para importar dentro del notebook de Google colab, se usa el url de descarga del archivo];
    D-->E[Se crean los dataframes de las categorías];
    E-->F[Se crea una función para elegir una palabra aleatoria con la librería random];
    F-->G[Se caracteriza cada categoría con un número];
    G-->H;
    H{¿La categoría se define con el entero x?} -- Sí --> I[Elegir una palabra aleatoria de la categoría];
    H -- No --> J[Seguir buscando la categoría correspondiente con el entero];
    J-->H;
    I-->K(Fin)
```
