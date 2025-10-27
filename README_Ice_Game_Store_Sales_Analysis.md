# 🎮 Ice Game Store Sales Analysis

## 🎯 Descripción del Proyecto
Este proyecto tiene como objetivo **identificar los factores clave que determinan el éxito comercial de un videojuego**, analizando datos históricos de **ventas globales**, **reseñas de usuarios y críticos**, **plataformas**, **géneros** y **clasificaciones ESRB**.  

El análisis se desarrolla para **Ice**, una tienda de videojuegos, con el fin de apoyar la toma de decisiones estratégicas en sus campañas de marketing para 2017.

---

## 🧩 Objetivos
1. Analizar el comportamiento del mercado de videojuegos por año, género y plataforma.  
2. Detectar los géneros y plataformas más rentables y populares.  
3. Estudiar la relación entre las calificaciones de usuarios/críticos y las ventas.  
4. Identificar patrones de éxito por región (NA, EU, JP y Global).  
5. Formular recomendaciones para maximizar las ventas y el posicionamiento de la tienda Ice.

---

## 📚 Datos Utilizados
El dataset incluye información sobre videojuegos publicada por distintas fuentes y regiones.

| Columna | Descripción |
|:--|:--|
| `Name` | Nombre del videojuego |
| `Platform` | Consola o dispositivo donde fue lanzado |
| `Year_of_Release` | Año de lanzamiento |
| `Genre` | Género del juego (Action, Sports, RPG, etc.) |
| `Publisher` | Empresa publicadora |
| `NA_sales`, `EU_sales`, `JP_sales`, `Other_sales` | Ventas por región (millones de copias) |
| `Critic_Score` | Calificación promedio de críticos |
| `User_Score` | Calificación promedio de usuarios |
| `Rating` | Clasificación ESRB (E, T, M, etc.) |

**Período cubierto:** 1980 – 2016  
**Total de registros:** más de 16,000 videojuegos

---

## 🔍 Metodología

### 1️⃣ Preparación y limpieza de datos
- Conversión de `Year_of_Release` a tipo numérico.  
- Sustitución de valores `'tbd'` en `User_Score` por `NaN` y conversión a `float`.  
- Eliminación de filas sin `name` o `genre`.  
- Creación de la columna `total_sales` para representar las ventas globales.

### 2️⃣ Análisis exploratorio (EDA)
- Evolución del mercado por año de lanzamiento.  
- Identificación de las plataformas más exitosas (PS, Xbox, Nintendo, etc.).  
- Evaluación de los géneros con mayor volumen de ventas.  
- Comparación entre reseñas de críticos y usuarios.

### 3️⃣ Análisis estadístico y visual
- Correlaciones entre calificaciones y ventas.  
- Comparación de ventas por región y género.  
- Detección de outliers y distribución de ventas.

### 4️⃣ Insights y conclusiones
- Determinación de los factores más influyentes en el éxito de un videojuego.  
- Identificación de tendencias clave por región.

---

## 📈 Principales Resultados

- El **pico de lanzamientos** y ventas ocurrió entre **2008 y 2011**.  
- Desde **2012**, la industria muestra una leve contracción, posiblemente por la transición generacional de consolas.  
- **Action** y **Sports** son los géneros con mayor volumen de ventas globales.  
- Las plataformas **PlayStation 2, Xbox 360 y Wii** lideran en ventas históricas.  
- Existe **correlación moderada** entre la calificación de críticos y las ventas globales.  
- La **región de América del Norte** domina el mercado, seguida por Europa y Japón.  
- Los juegos con clasificación **“M” (Mature)** suelen generar mayores ingresos, dirigidos a un público adulto con mayor poder adquisitivo.

---

## 🧠 Conclusiones y Recomendaciones
- Fomentar la presencia de géneros **Action y Sports**, con foco en plataformas dominantes.  
- Priorizar títulos con **buenas críticas** para maximizar retorno de inversión.  
- Enfocar campañas de marketing en **NA y Europa**, principales mercados.  
- Evaluar oportunidades en géneros de nicho (RPG, Adventure) con fuerte base de usuarios leales.  
- Incorporar análisis predictivo futuro para anticipar tendencias de éxito.

---

## ⚙️ Tecnologías Utilizadas
- **Python:** pandas, numpy, matplotlib, seaborn  
- **Entorno:** Jupyter Notebook  
- **Visualización:** gráficos de distribución, correlación y comparación de géneros  

---

## 📂 Estructura del Repositorio
```
📁 Ice-Game-Store-Sales-Analysis/
│
├── data/                          # Dataset de videojuegos
├── analisis de videojuegos.ipynb  # Notebook principal del análisis
├── README.md                      # Descripción del proyecto
└── images/                        # Visualizaciones y gráficos
```

---

## 👤 Autor
**Andrés Esquivel Díaz**  
📍 *Data Analyst | Python · SQL · Tableau · Power BI*  
🔗 [LinkedIn](https://www.linkedin.com/in/andres-esquivel-diaz-08691337) · [GitHub](https://github.com/aesquivel91)
