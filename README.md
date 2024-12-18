## Título del Proyecto
### Modelo de riesgo de corrupción en el servicio de compras públicas del Ecuador

## **Autor**
### Pablo Valverde



<h3 align="left">Lenguajes y librerias:</h3>
<p align="left"> <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://seaborn.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="40" height="40"/> </a> </p>

---
### Resumen 
Este proyecto desarrolla un modelo predictivo para identificar patrones y riesgos de corrupción en el sistema de compras públicas del Ecuador. Utilizando datos del Servicio de Compras Públicas (SERCOP), aplicamos técnicas de análisis de datos y aprendizaje automático para detectar indicadores de posible corrupción en las transacciones.

Puntos clave del análisis:

- Evaluación de patrones de adjudicación y comportamiento de proveedores
- Identificación de sectores críticos con mayor riesgo
- Análisis de variaciones entre presupuestos y valores adjudicados
- Desarrollo de indicadores de alerta temprana

Los resultados muestran concentración significativa en ciertos proveedores y sectores específicos, con variaciones sistemáticas que podrían indicar riesgos de corrupción. El modelo proporciona una herramienta objetiva para que las autoridades prioricen investigaciones y mejoren la transparencia en las compras públicas.


#### Justificación
¿Por qué debería importarle esto a alguien?

El riesgo de corrupcion es un problema muy grande en paises de bajo desarrollo especiqalemte, y nos enfocamos en detectar el riesgo de corriupcion en el servicio de compras publicas del Ecuador.

#### Pregunta de Investigación
¿Qué estamos tratando de responder?

Queremos saber bajo que criterioso ciertas compras publicas pueden preentar indicios de o riesgo de corrupcion  detectarlas a tiempo y poner a consideracion a las autoridades respectivas

#### Fuente de datos
Los datos son del Servicio de Compras Publicas del Ecuador ([SERCOP](https://portal.compraspublicas.gob.ec/sercop/))

#### Metodologia
Para responder a la pregunta de investigación, utilizamos los siguientes métodos:

1. **Análisis Exploratorio de Datos (EDA)**
   - Limpieza y preparación de datos
   - Análisis estadístico descriptivo
   - Visualización de datos

2. **Análisis de Correlaciones**
   - Matrices de correlación
   - Mapas de calor
   - Análisis de patrones

3. **Segmentación y Categorización**
   - Clasificación de proveedores por frecuencia
   - Categorización de presupuestos
   - Análisis por regiones y sectores

4. **Análisis Comparativo**
   - Comparación presupuesto vs valor adjudicado
   - Análisis por categorías de proveedores
   - Evaluación por sectores económicos

#### Resultados:
En mi análisis introductorio se encontró:

1. **Patrones de Riesgo**
   - 60% de compras tienen valor adjudicado menor al presupuesto
   - Concentración significativa en ciertos proveedores
   - Variaciones sistemáticas en sectores específicos

2. **Sectores Críticos**
   - Tecnología y equipos
   - Construcción y materiales
   - Suministros médicos
   - Servicios de consultoría

3. **Distribución Geográfica**
   - Mayor concentración en la Sierra
   - Patrones distintivos por región
   - Variaciones significativas en la Costa

4. **Comportamiento de Proveedores**
   - Correlación entre frecuencia de participación y diferencias presupuestarias
   - Patrones específicos en proveedores frecuentes
   - Concentración en categorías específicas

### Próximos pasos
Se recomienda los siguientes pasos:

1. **Desarrollo de Modelo Predictivo**
   - Implementar algoritmos de machine learning
   - Desarrollar sistema de puntuación de riesgo
   - Validar modelo con datos históricos

2. **Mejora de Datos**
   - Incorporar datos adicionales
   - Mejorar calidad de información
   - Establecer sistema de actualización continua

3. **Implementación de Sistema**
   - Desarrollar dashboard de monitoreo
   - Establecer alertas automáticas
   - Crear protocolos de seguimiento

4. **Validación y Ajuste**
   - Pruebas piloto
   - Ajuste de parámetros
   - Evaluación de efectividad

#### Esquema del proyecto#### Esquema del proyecto
- [Notebook 1: Análisis Exploratorio de Datos (EDA)](https://nbviewer.jupyter.org/github/pjvalverde/Capstone_Project_modelo_riesgo_corrupcion/blob/main/Risk_Corruption_P1_EDA.ipynb?flush_cache=true)

[![Notebook 1: Análisis Exploratorio de Datos (EDA) en Google Colab](https://colab.research.google.com/drive/1qyhVx5oGVqHLecT2Hq4oEJxEsei-VLqG?usp=sharing)](https://colab.research.google.com/drive/1qyhVx5oGVqHLecT2Hq4oEJxEsei-VLqG?usp=sharing)
- En Google Colab esta todos los graficos del analisis que posiblemente no se encuentre en el nbviewer

- [Notebook 2: Desarrollo de Modelo Predictivo](https://nbviewer.org/github/pjvalverde/Capstone_Project_modelo_riesgo_corrupcion/blob/main/Risk_Corruption_P2_Model.ipynb)
- [Notebook 3: Implementación y Validación](https://nbviewer.org/github/pjvalverde/Capstone_Project_modelo_riesgo_corrupcion/blob/main/Risk_Corruption_P3_Implementation.ipynb)

> **Nota**: Para ver los gráficos interactivos, por favor use los enlaces de nbviewer proporcionados arriba.
##### Contacto e Información Adicional
Para más información sobre este proyecto, contactar a:
- Email: [pblvalverde@gmail.com]
- GitHub: [https://github.com/pjvalverde]

