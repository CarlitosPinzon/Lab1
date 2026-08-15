# Taller de Python — Procesamiento de Datos a Gran Escala

Repositorio con el desarrollo del taller de introducción a Python de la asignatura
Procesamiento de Datos a Gran Escala.

## Datos del autor

| Campo | Dato |
|---|---|
| Nombre completo | Carlos Santiago Pinzón Caicedo |
| Documento de identidad | 1016833911 |
| Asignatura | Procesamiento de Datos a Gran Escala |
| Programa | Ingeniería de Sistemas, séptimo semestre |
| Universidad | Pontificia Universidad Javeriana |
| GitHub | [@CarlitosPinzon](https://github.com/CarlitosPinzon) |

**Descripción del autor:** Estudiante de Ingeniería de Sistemas de séptimo semestre en la
Pontificia Universidad Javeriana.

## Contenido del repositorio

| Archivo | Tema | Qué contiene |
|---|---|---|
| `01-Python-Cadenas.ipynb` | Cadenas | Indexación positiva y negativa, slicing, stride, concatenación, secuencias de escape y métodos `upper`, `replace` y `find`. |
| `02-Python-Tuplas.ipynb` | Tuplas | Creación, indexación, concatenación, slicing, ordenamiento con `sorted` y tuplas anidadas. |
| `03-Python-Listas.ipynb` | Listas | Indexación, anidamiento, `append` frente a `extend`, `del`, `split` y la diferencia entre copiar por referencia y clonar. |
| `04-Python-Conjuntos.ipynb` | Conjuntos | Eliminación de duplicados, `add`, `remove`, operador `in` e intersección, diferencia, unión, `issubset` e `issuperset`. |
| `05-Python-Diccionarios.ipynb` | Diccionarios | Pares llave-valor, `keys()`, `values()`, agregar y borrar entradas y verificación de llaves. |
| `06-Python-Condiciones.ipynb` | Condiciones | Operadores de comparación, `if`, `else`, `elif` y operadores lógicos `and`, `or` y `not`. |
| `07-Python-Bucles.ipynb` | Bucles | `range`, bucles `for` por índice y por elemento, `enumerate` y bucles `while`. |
| `08-Python-Funciones.ipynb` | Funciones | Definición con `def`, `return`, variables locales y globales, argumentos por defecto y ámbito. |
| `09_Python_Clases.ipynb` | Clases y objetos | Constructor `__init__`, atributos y métodos, clases `Circle` y `Rectangulo`, y la clase `Elipse` de la actividad propuesta. |
| `Practico_Bono_1.ipynb` | Práctico bono | Ocho ejercicios de funciones repartidos en calentamiento, nivel 1 y nivel 2. |

## Estructura

```
Repositorio/
├── README.md
├── 01-Python-Cadenas.ipynb
├── 02-Python-Tuplas.ipynb
├── 03-Python-Listas.ipynb
├── 04-Python-Conjuntos.ipynb
├── 05-Python-Diccionarios.ipynb
├── 06-Python-Condiciones.ipynb
├── 07-Python-Bucles.ipynb
├── 08-Python-Funciones.ipynb
├── 09_Python_Clases.ipynb
└── Practico_Bono_1.ipynb
```

## Cómo está documentado cada cuaderno

Cada cuaderno mantiene el material original del taller y agrega lo siguiente:

- **Membrete de identificación** al inicio, con los datos del autor y un resumen del contenido.
- **Notas propias** marcadas como `> Nota propia:` al comienzo de cada sección, donde explico
  con mis palabras qué se está trabajando y qué detalles hay que tener en cuenta.
- **Comentarios dentro del código** en los ejercicios resueltos, explicando la decisión tomada.
- **Conclusiones** al final del cuaderno.
- **Salidas guardadas** en todas las celdas, como evidencia de que se ejecutaron correctamente.

## Correcciones aplicadas al material original

Durante el desarrollo encontré tres celdas del taller que no podían ejecutarse tal como venían.
Las corregí y dejé anotada la razón en el cuaderno correspondiente:

- `01-Python-Cadenas.ipynb`: una celda comenzaba con una `C` suelta antes del comentario, lo que
  producía un error de sintaxis.
- `08-Python-Funciones.ipynb`: la primera función estaba definida como `sum()` pero se invocaba
  como `add()`. Se renombró a `add()`, que además evita sobrescribir la función `sum()` de Python
  usada más adelante en el mismo cuaderno.
- `09_Python_Clases.ipynb`: el objeto `FatYellowRectangle` se creaba con `Rectangle(...)` cuando
  la clase definida se llama `Rectangulo`.

También quedó anotada en `Practico_Bono_1.ipynb` una diferencia en la salida esperada del
ejercicio `paper_doll`, donde el ejemplo del enunciado omite un grupo de caracteres.


