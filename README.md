# CURSO DE GEOLOGÍA MARINA, GEOFÍSICA Y PROCESOS OCEANOGRÁFICOS ASOCIADOS - OTGA - 02 al 06 de NOVIEMBRE 2026

### Día: 3 de noviembre de 2026
### Horario: 8:30 a 13:00 hs
### Lugar: Escuela de Ciencias del Mar,  Antártida Argentina 425, C1104 CABA
### GRATUITO con inscripción previa vía OTGA

Material, datos, recursos y productos correspondientes a la jornada del
martes del curso de **Geología y Geofísica Marina y procesos oceanográficos
asociados**, organizado en el marco de la Intergovernmental Oceanographic Commission (UNESCO), OceanTeacher Global Academy, Specialized Training Centre, en Argentina en noviembre de 2026 en la Escuela de
Ciencias del Mar, Buenos Aires.

La jornada estará a cargo de:

- **Lic. Eva Noli**
- **Geof. Guillermo A. Nicora**

---

# 🌊 DEL DATO GEOFÍSICO AL MAPA CIENTÍFICO

La propuesta de trabajo para esta jornada es integrar los conceptos de
**geofísica marina y geomática** mediante un flujo de trabajo completo que
permita pasar desde un dato geofísico disponible públicamente hasta la
elaboración de un producto cartográfico.

El objetivo no es solamente aprender a utilizar un determinado programa,
sino comprender el recorrido que realiza un dato desde su adquisición,
procesamiento y georreferenciación hasta su representación cartográfica,
interpretación y publicación.

El flujo general de trabajo será:

```text
DATOS GEOFÍSICOS
       ↓
ADQUISICIÓN
       ↓
POSICIONAMIENTO Y REFERENCIACIÓN
       ↓
CONTROL Y PROCESAMIENTO
       ↓
DATOS GEOESPACIALES
       ↓
GRILLA / RASTER
       ↓
ANÁLISIS ESPACIAL
       ↓
VISUALIZACIÓN
       ↓
MAPA BATIMÉTRICO / GEOMORFOLÓGICO
       ↓
PUBLICACIÓN
       ↓
REPRODUCIBILIDAD
```
---

# 📚 ORGANIZACIÓN DE LA JORNADA

La jornada del martes estará organizada en dos módulos complementarios que convergen en una actividad práctica integradora.

| Horario     | Actividad                                                                                                       | Responsable                               |
| ----------- | --------------------------------------------------------------------------------------------------------------- | ----------------------------------------- |
| 08:30–10:30 | Módulo 3 – Conceptos básicos de geofísica marina y sus aplicaciones                                             | Geof. Guillermo A. Nicora                 |
| 10:30–10:45 | Pausa                                                                                                           |                                           |
| 10:45–11:45 | Módulo 4 – Introducción a la geomática y uso de software para confeccionar mapas batimétricos y geomorfológicos | Lic. Eva Noli                             |
| 11:45–13:00 | Actividad práctica integradora                                                                                  | Lic. Eva Noli / Geof. Guillermo A. Nicora |

La actividad práctica buscará integrar los contenidos de ambos módulos mediante el procesamiento y visualización de datos geoespaciales marinos.

---

# 🌐 MÓDULO 3 — CONCEPTOS BÁSICOS DE GEOFÍSICA MARINA Y SUS APLICACIONES

**Responsable:** Geof. Guillermo A. Nicora

## Objetivos

El módulo tiene como objetivo introducir los principales conceptos relacionados con la adquisición e interpretación de datos geofísicos marinos y comprender qué información del medio marino puede obtenerse a partir de diferentes métodos de exploración.

Se trabajará sobre la relación:

```text
MEDIO MARINO
      ↓
MÉTODO GEOFÍSICO
      ↓
SENSOR / INSTRUMENTO
      ↓
MEDICIÓN
      ↓
DATOS
      ↓
PROCESAMIENTO
      ↓
PRODUCTO GEOFÍSICO
      ↓
INTERPRETACIÓN


## ¿Qué mide la geofísica marina?

La geofísica marina permite obtener información sobre el fondo y subsuelo marino mediante diferentes métodos de adquisición.

Entre ellos se encuentran:

| Método                   | Variable / información          | Producto                        |
| ------------------------ | ------------------------------- | ------------------------------- |
| Batimetría multihaz      | Profundidad y relieve           | Modelo batimétrico / DTM        |
| Sonar de barrido lateral | Reflectividad acústica          | Mosaico de backscatter          |
| Sísmica de reflexión     | Estructura del subsuelo         | Perfiles sísmicos               |
| Magnetometría            | Campo magnético / anomalías     | Mapa de anomalías magnéticas    |
| Gravimetría              | Campo gravitacional / anomalías | Mapa de anomalías gravimétricas |

## De la medición al dato georreferenciado

En una adquisición geofísica marina, la medición realizada por el instrumento no constituye por sí misma un producto cartográfico.

Para obtener un dato geoespacial es necesario considerar, entre otros aspectos:

* posicionamiento GNSS;
* navegación;
* movimiento de la embarcación;
* rumbo y orientación;
* velocidad;
* velocidad del sonido en el agua;
* mareas y referencia vertical;
* datum geodésico;
* control de calidad;
* procesamiento;
* interpolación o generación de una grilla.

De esta manera:

```text
MEDICIÓN GEOFÍSICA
       +
POSICIONAMIENTO
       +
REFERENCIA ESPACIAL
       +
CONTROL DE CALIDAD
       +
PROCESAMIENTO
       ↓
DATO GEOFÍSICO GEOREFERENCIADO
```

## Ejemplo: batimetría

En el caso de una ecosonda multihaz, el sistema registra los tiempos de viaje de las señales acústicas emitidas y recibidas.

De forma simplificada:

```text
EMISIÓN DEL PULSO
       ↓
PROPAGACIÓN EN EL AGUA
       ↓
REFLEXIÓN EN EL FONDO
       ↓
RECEPCIÓN
       ↓
TIEMPO DE VIAJE
       ↓
DISTANCIA / PROFUNDIDAD
       ↓
CORRECCIONES
       ↓
SONDEOS GEOREFERENCIADOS
       ↓
MODELO BATIMÉTRICO
```

Este proceso permite comprender por qué un mapa batimétrico no es simplemente una imagen del fondo marino, sino el resultado de una cadena de adquisición, procesamiento y referencia espacial.

---

# 🗺️ MÓDULO 4 — INTRODUCCIÓN A LA GEOMÁTICA

**Responsable:** Lic. Eva Noli

## Objetivos

Introducir los principales conceptos de geomática necesarios para transformar datos geofísicos en información geoespacial y productos cartográficos.

Se trabajará especialmente sobre:

* sistemas de coordenadas;
* datum;
* CRS;
* códigos EPSG;
* coordenadas geográficas y proyectadas;
* proyecciones cartográficas;
* raster y vector;
* resolución espacial;
* tamaño de píxel;
* extensión espacial;
* NoData;
* interpolación;
* remuestreo;
* escala;
* simbología;
* composición cartográfica.

## ¿De dónde sale la profundidad que vemos en un mapa?

Una de las preguntas centrales del módulo será comprender el recorrido entre una medición geofísica y su representación cartográfica:

```text
SONDEO
   ↓
LATITUD / LONGITUD
   ↓
DATUM / CRS
   ↓
CONTROL DE CALIDAD
   ↓
INTERPOLACIÓN / GRILLADO
   ↓
RASTER BATIMÉTRICO
   ↓
ANÁLISIS ESPACIAL
   ↓
MAPA
```

## Del raster al mapa científico

A partir de un modelo batimétrico se pueden generar diferentes productos derivados:

```text
MODELO BATIMÉTRICO
        │
        ├──→ Batimetría
        │
        ├──→ Hillshade
        │
        ├──→ Curvas de nivel
        │
        ├──→ Pendiente
        │
        └──→ Interpretación geomorfológica
```

Estos productos permiten pasar de una representación numérica de la profundidad a una representación cartográfica que facilite el análisis e interpretación del relieve submarino.

---

# 🔄 INTEGRACIÓN DE LOS DOS MÓDULOS

Los contenidos de geofísica marina y geomática se integrarán mediante un único flujo de trabajo:

```text
          GEOFÍSICA MARINA
                 │
                 ↓
        ADQUISICIÓN DEL DATO
                 │
                 ↓
       POSICIONAMIENTO / GNSS
                 │
                 ↓
       CONTROL Y PROCESAMIENTO
                 │
                 ↓
          DATO GEOESPACIAL
                 │
                 ↓
              GEOMÁTICA
                 │
                 ↓
        QGIS / PYTHON / COLAB
                 │
                 ↓
          RASTER BATIMÉTRICO
                 │
          ┌──────┼──────┐
          ↓      ↓      ↓
      HILLSHADE  SLOPE  CURVAS
          │      │      │
          └──────┼──────┘
                 ↓
      INTERPRETACIÓN GEOMORFOLÓGICA
                 ↓
           MAPA CIENTÍFICO
                 ↓
             GITHUB
                 ↓
          REPRODUCIBILIDAD
```

---

# 💾 DATOS PÚBLICOS

La actividad práctica utilizará datos geofísicos y geoespaciales de acceso público.

## GEBCO

El conjunto de datos principal propuesto para la actividad será **GEBCO (General Bathymetric Chart of the Oceans)**.

GEBCO permite disponer de información batimétrica global y resulta especialmente apropiado para una actividad introductoria porque permite trabajar directamente con modelos digitales del fondo marino.

Los datos pueden utilizarse para:

* visualizar la batimetría;
* analizar el relieve submarino;
* generar sombreado;
* obtener pendientes;
* generar curvas de nivel;
* identificar estructuras geomorfológicas;
* producir mapas científicos.

### Información a documentar

Para cada conjunto de datos utilizado se deberá registrar:

| Campo             | Información                   |
| ----------------- | ----------------------------- |
| Fuente            | Organización / proyecto       |
| Producto          | Nombre del dataset            |
| Versión           | Versión utilizada             |
| Fecha de descarga | Fecha                         |
| Área              | Área de estudio               |
| Formato           | GeoTIFF / NetCDF / etc.       |
| CRS               | Sistema de referencia         |
| Resolución        | Tamaño de píxel               |
| Datum             | Referencia vertical/geodésica |
| URL               | Fuente original               |

## Otras fuentes de datos

Durante la jornada también se mostrarán recursos públicos que pueden utilizarse para obtener datos oceanográficos y geofísicos:

* GEBCO
* Global Multi-Resolution Topography (GMRT)
* EMODnet
* NOAA
* NOAA/NCEI
* otros repositorios de datos científicos abiertos

El objetivo no es trabajar exhaustivamente con todas estas fuentes, sino mostrar a los participantes dónde encontrar datos que posteriormente puedan utilizar en sus propios proyectos.

---

# 💻 SOFTWARE Y HERRAMIENTAS

## QGIS

QGIS será utilizado como herramienta principal para el procesamiento y elaboración cartográfica.

Entre las tareas previstas se encuentran:

* carga de datos raster;
* inspección de propiedades;
* recorte del área de estudio;
* reproyección;
* simbología;
* generación de hillshade;
* generación de curvas de nivel;
* cálculo de pendiente;
* creación y edición de capas vectoriales;
* digitalización geomorfológica;
* composición cartográfica;
* exportación de mapas.

## Python

Python permitirá mostrar una alternativa reproducible para el procesamiento y visualización de datos geoespaciales.

Se podrán utilizar bibliotecas como:

* `xarray`
* `rasterio`
* `numpy`
* `matplotlib`
* `geopandas`
* `folium`

según las necesidades del ejercicio.

## Google Colab

Google Colaboratory permitirá ejecutar notebooks de Python sin necesidad de instalar localmente todo el entorno de programación.

Esto permitirá que los participantes:

1. abran el notebook;
2. carguen los datos;
3. ejecuten el código;
4. modifiquen los parámetros;
5. generen sus propias visualizaciones;
6. descarguen los resultados.

## GitHub

GitHub será utilizado como espacio para:

* almacenar notebooks;
* documentar los datos;
* compartir resultados;
* publicar mapas;
* registrar las fuentes;
* facilitar la reproducibilidad.

GitHub no será abordado como un curso específico de programación o control de versiones, sino como una herramienta para documentar y compartir trabajos científicos.

---

# 🧪 ACTIVIDAD PRÁCTICA INTEGRADORA

La actividad práctica tendrá como objetivo transformar un conjunto de datos batimétricos públicos en un producto cartográfico científico.

## Etapa 1 — Selección del área

Se seleccionará un área de estudio con características geomorfológicas identificables.

La extensión deberá permitir trabajar con los datos disponibles durante la jornada sin generar tiempos de procesamiento excesivos.

## Etapa 2 — Obtención de los datos

Los participantes accederán a los datos públicos seleccionados.

Se registrarán:

* fuente;
* producto;
* versión;
* resolución;
* fecha de descarga;
* área de trabajo;
* sistema de referencia.

## Etapa 3 — Preparación

Se realizará:

* inspección del dataset;
* revisión del CRS;
* revisión de resolución;
* identificación de valores NoData;
* recorte del área de interés;
* reproyección cuando sea necesaria.

## Etapa 4 — Visualización de la batimetría

Se generará una representación de la profundidad mediante una escala de colores apropiada.

## Etapa 5 — Visualización del relieve

Se generará un modelo de sombreado:

**Hillshade**

El objetivo será resaltar la morfología del fondo marino.

## Etapa 6 — Análisis espacial

A partir del modelo batimétrico podrán obtenerse:

* pendiente;
* curvas de nivel;
* gradientes;
* unidades geomorfológicas.

## Etapa 7 — Interpretación

Los participantes identificarán, cuando sean visibles y pertinentes, estructuras o unidades geomorfológicas tales como:

* plataforma;
* talud;
* cañones;
* canales;
* depresiones;
* bancos;
* escarpes;
* otras formas del relieve submarino.

La identificación dependerá de las características del área de estudio y de la resolución de los datos.

## Etapa 8 — Elaboración del mapa final

El producto cartográfico deberá incorporar, según corresponda:

* título;
* batimetría;
* sombreado;
* curvas de nivel;
* unidades geomorfológicas;
* escala;
* orientación;
* sistema de coordenadas;
* fuente de datos;
* fecha;
* autores.

---

# 🗺️ PRODUCTOS ESPERADOS

Al finalizar la actividad se espera obtener un conjunto de productos que permitan documentar el proceso completo.

### Productos cartográficos

* mapa batimétrico;
* mapa de sombreado;
* mapa de pendiente;
* curvas de nivel;
* mapa geomorfológico;
* mapa científico final.

### Productos digitales

* proyecto QGIS;
* notebook de Python/Google Colab;
* capas vectoriales;
* raster procesado;
* metadatos;
* documentación de las fuentes.

---

# 🧭 DOS CAMINOS, UN MISMO RESULTADO

Durante la jornada se mostrarán dos alternativas de trabajo.

### Ruta QGIS

```text
GEBCO
  ↓
QGIS
  ↓
Preparación
  ↓
Procesamiento
  ↓
Batimetría
  ↓
Hillshade / Pendiente / Curvas
  ↓
Interpretación
  ↓
Mapa final
```

### Ruta Python / Google Colab

```text
GEBCO
  ↓
Python / Colab
  ↓
Lectura del raster
  ↓
Procesamiento
  ↓
Visualización
  ↓
Análisis
  ↓
Mapa / Producto final
```

Ambas rutas parten de los mismos principios geoespaciales y buscan producir resultados comparables.

---

# 📁 ESTRUCTURA DEL REPOSITORIO

```text
OTGA-NOV-2026/
│
├── README.md
├── LICENSE
│
├── datos/
│   ├── README.md
│   ├── originales/
│   └── procesados/
│
├── qgis/
│   ├── README.md
│   ├── proyecto.qgz
│   └── estilos/
│
├── python/
│   ├── README.md
│   └── mapa_batimetrico.ipynb
│
├── mapas/
│   ├── README.md
│   ├── batimetria.png
│   ├── sombreado.png
│   ├── pendiente.png
│   └── mapa_final.png
│
├── vectores/
│   ├── README.md
│   └── geomorfologia.gpkg
│
└── metadatos/
    └── fuentes.md
```

La estructura podrá modificarse durante la preparación de los materiales.

---

# 🔬 REPRODUCIBILIDAD

Uno de los objetivos de la actividad es mostrar que un producto científico no debería limitarse al mapa final.

Siempre que sea posible, el repositorio deberá permitir reconstruir el resultado a partir de:

```text
DATOS
  +
CÓDIGO / PROCESAMIENTO
  +
PARÁMETROS
  +
METADATOS
  ↓
RESULTADO
```

Por este motivo se recomienda documentar:

* origen de los datos;
* versión utilizada;
* fecha de descarga;
* sistema de referencia;
* resolución;
* parámetros de procesamiento;
* software utilizado;
* versión del software cuando sea relevante;
* código utilizado;
* productos generados.

---

# 📋 RECOMENDACIONES PARA LOS PARTICIPANTES

Antes de la jornada se recomienda disponer de:

* cuenta de GitHub;
* acceso a Google Drive;
* cuenta de Google para utilizar Google Colab;
* QGIS instalado, si se trabajará localmente;
* navegador web actualizado.

No es indispensable disponer de una instalación local de Python si se utiliza Google Colab.

Se recomienda llevar el equipo portátil que se utilizará durante la actividad.

---

# 📚 RECURSOS

## Datos

* GEBCO
* GMRT
* EMODnet
* NOAA
* NOAA/NCEI

## Software

* QGIS
* Python
* Google Colaboratory
* Jupyter Notebook
* Visual Studio Code
* GitHub

## Documentación

En este repositorio se incorporarán progresivamente:

* notebooks;
* datos de ejemplo;
* proyectos QGIS;
* estilos;
* mapas;
* instrucciones;
* metadatos;
* referencias bibliográficas;
* enlaces a las fuentes de datos.

---

# 👥 RESPONSABLES

### Geof. Guillermo A. Nicora

**Módulo 3 — Conceptos básicos de geofísica marina y sus aplicaciones**

### Lic. Eva Noli

**Módulo 4 — Introducción a la geomática y uso de software para confeccionar mapas batimétricos y geomorfológicos**

---

# 📌 NOTA

Los materiales de este repositorio podrán actualizarse durante la preparación y desarrollo del curso.

La versión de los datos, notebooks, proyectos QGIS y productos cartográficos utilizados durante la jornada deberá quedar documentada en el repositorio.

---

**Curso de Geología Marina, Geofísica y Procesos Oceanográficos Asociados — OTGA 2026**

**Escuela de Ciencias del Mar — Buenos Aires, Argentina**

**3 de noviembre de 2026**
