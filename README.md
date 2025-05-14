# Proyecto personal de análisis de datos de la Premier League

**Autor:** Lucas Eloy Fernández

## El Proceso de Análisis de Datos

1. **Preguntar:** Desafío empresarial/objetivo/pregunta  
2. **Preparar:** Generación, recopilación, almacenamiento y administración de datos  
3. **Procesar:** Limpieza de datos/integridad de datos  
4. **Analizar:** Exploración, visualización y análisis de datos  
5. **Compartir:** Comunicación e interpretación de los resultados  
6. **Actuar:** Uso de conocimientos para resolver el problema

---

## Fuente de Datos

Los datos fueron obtenidos de:  
[Premier League Stats 2022/2023 - Kaggle](https://www.kaggle.com/datasets/thamersekhri/premier-league-stats-2022-2023)

---

## Contenido del Dataset

- Date  
- Clock  
- Stadium  
- Attendance  
- Home Team  
- Goals Home  
- Away Team  
- Away Goals  
- Home Possession  
- Away Possession  
- Home Total Shots  
- Away Total Shots  
- Home On Target Shots  
- Away On Target Shots  
- Home Off Target Shots  
- Away Off Target Shots  
- Home Blocked Shots  
- Away Blocked Shots  
- Home Passing Accuracy  
- Away Passing Accuracy  
- Home Chances  
- Away Chances  
- Home Corners  
- Away Corners  
- Home Offsides  
- Away Offsides  
- Home Tackles Won %  
- Away Tackles Won %  
- Home Aerial Duels %  
- Away Aerial Duels %  
- Home Saves  
- Away Saves  
- Home Fouls Committed  
- Away Fouls Committed  
- Home Yellow Cards  
- Away Yellow Cards  
- Home Red Cards  
- Away Red Cards

---

## 1. Preguntar: Desafíos y Preguntas

- ¿Cuántos partidos jugaron los equipos de local y visitante en la temporada?  
- ¿Cuántos goles convirtieron los equipos de local y visitante?  
- ¿Qué estadios tienen más concurrencia?  
- ¿Cuántas tarjetas amarillas y rojas se repartieron según condición (local/visitante)?  
- ¿Cuáles son los 5 equipos con más goles de local y visitante?  
- ¿Cuál es el promedio de goles por partido?  
- ¿Cuál es el promedio de posesión de balón según condición de local o visitante?

---

## 2. Preparar: Herramientas y Organización

- Herramienta: **Microsoft Excel 365**  
- Formato de datos: `.CSV`  
- Se guarda una copia original y otra para análisis  
- Primera hoja: **Raw Data**

---

## 3. Procesar: Limpieza e Integridad de Datos

Pasos realizados:

- Formateo de fechas (fecha corta)  
- Conversión de datos a tipo numérico  
- Eliminación de columnas innecesarias (como "links")  
- Formato condicional para celdas vacías o NULL  
- Reemplazo de `.` por `,` para manejar decimales  
- Creación de columnas auxiliares para conversión a % (ej. posesión, pases, tackles, duelos)  
- Redondeo de números a enteros si es necesario  

---

## 4. Analizar: Visualización en Power BI

**Herramienta usada:** Power BI Desktop

Pasos:

1. Importación de datos desde Excel  
2. Transformación de datos en Power Query (corrección de formatos)  
3. Creación de visualizaciones:

### Visualizaciones creadas:
- Título con cuadro de texto  
- Gráfico de barras apiladas en % (goles local vs visitante)  
- Gráfico de barras apiladas (asistencia a estadios ordenada de mayor a menor)  
- Tarjetas con total de partidos jugados (local/visitante)  
- Gráfico de barras en % (posesión por equipo)  
- Tarjetas de varias filas (amarillas y rojas por condición)  
- Gráficos medidor (promedio de goles local/visitante)  
- Matriz (Top 5 equipos con más goles de local/visitante)

---

## 5. Compartir: Conclusiones

Al finalizar el análisis se concluye:

- Los equipos del **Big Six** (Manchester City, Manchester United, Chelsea, Tottenham, Liverpool y Arsenal)  
  - Son los que más goles convirtieron  
  - Tienen mayor posesión de balón como locales  
  - Tienen mayor asistencia en estadios  
  - Reciben menos tarjetas que el resto  
- El título de la Premier League usualmente se disputa entre estos equipos debido a su calidad de juego y rendimiento a lo largo de la temporada.

---


