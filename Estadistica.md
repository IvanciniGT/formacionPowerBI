# PowerBI

Business Intelligence
    Datos -> Información -> Decisiones (experiencia)
        Estadística descriptiva/inferencial

Data mining

Machine Learning

# Estadística

Ciencia (no tiene nada que ver con las matemáticas) que se dedica al estudio de poblaciones.

- **Fenómenos no deterministas:** A aquel experimento cuyo resultado NO es conocido a priori.
  - Predicción: Bola de cristal, posos del café, estadística (capacidad de conocer a priori la probabilidad de equivocarnos al tomar una decisión).
  - Experimentos aleatorios: 
    - No conozco su resultado a priori
    - Pero conozco los posibles resultados
    - Conozco la probabilidad de cada posible resultado
- Fenómenos deterministas: A aquel experimento cuyo resultado es conocido a priori.

A mi no me importa equivocarme con una decisión, lo asumo, es INEVITABLE.
El éxito no será si acierto o me equivoco con una decisión, ni con dos, ni con tres.
Con que porcentaje de decisiones me equivoco.

# Estadística descriptiva

Conjunto de herramientas y técnicas que nos ayudan a entender un conjunto de datos.

RRHH -> Nóminas de los empleados de la empresa: 2000 nóminas

Después de leer 2000 nóminas... qué se yo del salario de la empresa? NPI

Necesito resumir esa información... de forma que pueda llegar a entenderla.
En ese resumen PIERDO INFORMACIÓN.... pero la información importante florece!
Aprendizaje ... es descartar información en favor de otra.

- Tabla de Frecuencias < Tabla de resumen
    Frecuencia? Cuantas veces ocurre algo
- Indicadores / Estadísticos: Min, Max, Media, Mediana, Moda, Desv. Típica
- Gráficos
    - Barras
    - Sectores
    - área
    - boxplot (caja y bigote)
    - Dispersión
    - Histogramas
# Seguros

Aseguro una vivienda.
60% de las viviendas no tiene problema.
40% de las viviendas que si.

Azar, probabilidades: Tirar un dado
Azar, probabilidades: Me retraso en un proyecto

# Individuos

Población es un conjunto de individuos (casos) que comparten unas características que me interesa estudiar, observar, medir.

Habitantes de Ciudad de Madrid:
- Lugar de procedencia  90% no será Madrid... 
- Ciudad de residencia   Madrid                 Que necesito estudiar? NADA     CONSTANTE
- Barrio de residencia: Chamberí, Iglesia...                                    VARIABLE
- Calendario de festivos                                                        CONSTANTE
- Nivel de estudios: ESO, Primaria, Grado, FP, Master                           VARIABLE
- Color de ojos: Azul, verde, marrón, negro
- ~~Número de ruedas~~

La variabilidad de los datos no es mala... es buena.

# Datos

## Estadístico / Forma en la que se han medido

Es una medición una característica.

Hay distintas formas de medir una información. En algunas ocasiones, incluso puedo elegir cómo medir.

Hijos que tiene una pareja? Pregunta en un cuestionario
Tienes hijos(as)?                SI              NO
Cuantos hijos(as) tienen?        Ninguno         Pocos       Algunos     Muchos      Demasiados
                                 _________ hijos(as)

### Escala cualitativa

#### Escala Nominal

Cuanto los distintos valores de una característica los asocio con distintos NOMBRES (etiquetas)

Ejemplos: 
    Tiene hijos: SI / NO
    Color de ojos : azul, verde, marrón, Rojo

Qué me permite esto?
    Clasificar los individuos: Segmentar, Grupos

#### Escala Ordinal ( A su vez es una escala nominal)

Cuanto los distintos valores de una característica los asocio con distintos NOMBRES (etiquetas)
que presentan una relación de orden entre sí

Ejemplos: 
    Tiene hijos: Ninguno   <   Pocos   <  Algunos  <   Muchos  <   Demasiados

Qué me permite esto?
    Clasificar los individuos: Segmentar, Grupos
    Ordenar a los individuos en base a la característica

### Escalas cuantitativas (ORDINAL)

Cuanto los distintos valores de una característica los asocio con distintas CANTIDADES

Ejemplos: 
    Tiene hijos: 0 hijos, 1 hijo, 2, 3 hijos, 4, 18

Qué me permite esto?
    Clasificar los individuos: Segmentar, Grupos
    Ordenar a los individuos en base a la característica
    Operaciones matemáticas con los valores: Sumar (Totalizar), Buscar diferencias (Restas), Multiplicaciones y Divisiones

Qué o cómo sé si estoy usando una escala cuantitativa?
Columna17 del Excel -> Cuantitativo? Numéricos NO...
                                     Necesito CANTIDADES.
¿ Qué convierte un dato en una cantidad ? 
    Qué sea un número? NO... esto es condición necesaria, pero no suficiente
    Que tenga una Unidad de Medida.

### Ejemplos:

Encuesta:
    Indique el grado de satisfacción con nuestros servicios: 0=Nada 5=Mucha
        0       1       2       3       4           5
        nada    poco    algo    mucho   muchísimo

Tipo de dato? Escala de Medición?   Ordinal
    Media de satisfacción *** 

## Informático

Cómo los computadores guardan los datos? 0,1 ... binario
                                    _
Mínima unidad de información: BIT: |_| (un 0 o un 1)

    Significado (yo lo defino como ser humano)
0 = Llueve          Gano        Retraso
1 = No llueve       Pierdo      No me retraso

000
001
010
011
100
101
110
111

Ninguno   <   Pocos   <  Algunos  <   Muchos  <   Demasiados
 000           001         010          011        100

0       1       2       3       4       5       6       7       8       9
0000    0001    0010    0011    0100    0101    0110    0111    1000    1001

0000 -> SIGNIFICADO -> NÚMERO
                       Ninguno
                       CP 28760

El conjunto de todos los significados que doy a una secuencia de bits: Tipo de datos
|          |     Número     Texto   Lógico      Fecha       Fecha + Hora
 0000000000      0          A       Verdadero
 0000000001      1          B       False
 0000000010      2          C


            Estadística                                 PowerBI
 Texto ->   Nominal u Ordinal                           Nominales
 Número ->  Nominal, ordinal, cuantitativa              Cuantitativos
 Lógico ->  Nominal                                     Nominales
 Fecha o Fecha+Hora -> Cuantitativo                     Cuantitativos


---

ESTADISTICA         POWERBI             PERMITEN
------------------------------------------------------------
Cualitativos        Texto, Lógico       Clasificar/Segmentar/Filtrar
Cuantitativos       Número, Fechas      Operar: 
                                            Totalizaciones
                                            Estadísticos
                                                Min
                                                Max
                                                Media
                                                Mediana
                                                Desv. Tipica


Tabla dinámica:
- 1 dato Cualitativo

Productos -> Cualitativo


En mi conjunto de datos, cada linea representa 1 venta individual de producto
PRODUCTO       OPERACIÓN DE VENTA     
Producto1      1
Producto1      1
Producto1      1
Producto1      1
Producto1      CL-179/2021
Producto2      CL-179/2021
Producto2      CL-179/2021

--- TABLAS DE FRECUENCIAS(Cuantas veces ocurre algo)

Tabla               Ventas
Producto 1          Número de lineas de mi Excel cuyo producto es Producto 1
Producto 2          Número de lineas de mi Excel cuyo producto es Producto 2
Producto 3          Número de lineas de mi Excel cuyo producto es Producto 3
Producto 4          Número de lineas de mi Excel cuyo producto es Producto 4

OPERACION DE VENTA      PRODUCTO            VENTAS
1                       1                   4
CL-179/2021             1                   1
CL-179/2021             2                   2

OPERACION DE VENTA      PRODUCTO1           PRODUCTO2
1                       4                   0
CL-179/2021             1                   2

Tabla               Ventas
Producto 1          5
Producto 2          3


VENTAS DE UN PRODUCTO < TABLA DE FRECUENCIAS > Grafico de BARRAS / SECTORES
Variable de estudio?     Producto   < Cualitativa(clasificación)
    En función del ? PAIS
    Tabla               Ventas=Frecuencia
                        Europa  Asia    
    Producto 1          4       1
    Producto 2          2       1

PRECIO MEDIO DE VENTA DE CADA PRODUCTO < Tabla que muestra un estadístico (MEDIA)

    Variable de estudio? Precio (Cuantitativa)
        En función del?  Producto   < Cualitativa(segmentación)

    Tabla               PRECIO MEDIO DE VENTA       DESV.TIPICA
    Producto 1          18.98                       1.17
    Producto 2          989.12                      100.87


Desv. Tipica? A partir de ahora NUNCA MAS daré una media en un informe sin poner al lado su desv. tipica.


Cuál es el objetivo de la estadística? Ayudarme a entender un conjunto de datos... resumiéndolo
    Al resumir, perdemos información... Debería tener cuidado y dar información pertinente.


Ventas mensuales de media de un producto de 2021, 2022

    España          1000 al mes
        1000 1000 1000 1000 1000 1000 1000 1000 1000 1000 1000 1000 1000 1000 1000 1000 1000 1000 1000 1000 1000 1000 1000 1000 1000 1000 1000 
    Francia          990 al mes
        1500    500 1500    500 1500    500 1500    500 1500    500 1500    500 1500    500 1500    500 1500    500 1500    500 
    Portugal        1000 al mes
        2000    0   2000    0   2000    0   2000    0   2000    0   2000    0   2000    0   2000    0   2000    0   2000    0   2000    0   

En los 3 paises se vende mas o menos lo mismo. Son clavaos.

Pais Media: 1000 unidades al mes + desv.tipica de 200 unidades
            La mayor parte de los meses vendemos entre 800 y 1200 unidades
