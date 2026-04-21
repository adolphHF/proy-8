# Learning Urban Crime Representations to Map the Latent Structure of Reported Crime

**Prof. Dr. Jorge Valverde-Rebaza**

## 1. Descripción del proyecto

Se propone una investigación orientada al aprendizaje de representaciones urbanas a partir del conjunto público de carpetas de investigación de la Fiscalía General de Justicia de la Ciudad de México. A diferencia de enfoques centrados en predicción o detección de disparidades de reporte, esta versión del proyecto se enfoca en una pregunta más descriptiva e interpretativa: **cómo se organiza latentemente la ciudad cuando se la observa a través del crimen reportado**.

La propuesta parte de dos características críticas del problema. En primer lugar, las categorías delictivas presentan ruido semántico importante, debido a errores ortográficos, variantes de escritura, duplicados conceptuales y registros humanos poco consistentes. En segundo lugar, el dataset refleja crimen reportado y registrado, no necesariamente crimen real, por lo que resulta metodológicamente más sólido trabajar sobre la estructura observada del registro que sobre inferencias causales fuertes.

En este contexto, el proyecto busca aprender embeddings de zonas urbanas robustos al ruido del dato para **visualizar, interpretar y cartografiar la estructura funcional del crimen reportado en la ciudad**. La idea central es que, si cada zona se representa mediante una firma espacio-temporal suficientemente informativa, será posible identificar clústeres, gradientes, zonas intermedias y perfiles urbanos diferenciados. El resultado esperado no es solo técnico, sino analítico: producir una lectura estructural de la ciudad basada en regularidades del registro delictivo observado.

## 2. Objetivo general

Construir representaciones urbanas robustas a registros policiales ruidosos para visualizar e interpretar la estructura latente del crimen reportado en la ciudad.

### Objetivos específicos

- **O1.** Limpiar y armonizar semánticamente las categorías delictivas para reducir ruido y consolidar una taxonomía analíticamente útil.
- **O2.** Construir firmas espacio-temporales por zona que capturen composición delictiva, intensidad relativa y regularidades temporales del reporte.
- **O3.** Aprender embeddings urbanos que permitan representar similitudes y diferencias funcionales entre territorios.
- **O4.** Visualizar e interpretar el espacio latente de la ciudad mediante clústeres, gradientes y zonas atípicas o de transición.

## 3. Justificación e impacto

Aunque los datos policiales de la FGJ-CDMX han sido utilizados con frecuencia en análisis descriptivos o predictivos, existe menos trabajo orientado a estudiar la **estructura latente del fenómeno urbano** a partir de representaciones robustas del territorio. Esta propuesta se ubica en la intersección entre limpieza semántica, urban representation learning e interpretación territorial del crimen reportado.

Desde una perspectiva aplicada, el proyecto puede aportar en:

- mejorar la calidad analítica del dato policial;
- construir tipologías funcionales de zonas urbanas;
- visualizar similitudes, gradientes y discontinuidades entre territorios;
- generar una cartografía analítica de la ciudad basada en patrones observados de crimen reportado.

El impacto práctico radica en que los resultados podrían ser útiles para investigadores urbanos, analistas de seguridad y entidades públicas interesadas en comprender cómo se estructura territorialmente el registro delictivo. Además, el enfoque sería transferible a otros contextos urbanos latinoamericanos con datos administrativos ruidosos y heterogeneidad institucional.

## 4. Pregunta de investigación

¿Es posible aprender representaciones urbanas robustas a categorías delictivas ruidosas y utilizarlas para visualizar e interpretar la estructura latente del crimen reportado en la ciudad?



---

### 🔹 Nota
Como habrán notado, este proyecto sufrió ligeros ajustes para que haya un diferencial técnico mínimo comparado a la propuesta original y, asi, diferenciarse técnicamente con el otro equipo que escogió el mismo proyecto.
