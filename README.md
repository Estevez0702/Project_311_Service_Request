# Project_311_Service_Request

# 1. Caso de Negocio

**Descripción del problema:** Imagina una ciudad enorme como Nueva York, donde la gente reporta de todo todos los días: un bache en la calle, ruido excesivo, problemas con el agua o basura acumulada. El problema es que esta información entra como una avalancha desordenada, lo que hace que los departamentos de la ciudad colapsen tratando de clasificar, priorizar y asignar recursos para resolver las quejas a tiempo. Básicamente, se enfrentan a un volumen gigantesco de datos que no están aprovechando bien, lo que genera demoras en el servicio y ciudadanos molestos.

**Objetivo del proyecto:** La meta principal de aplicar Big Data aquí es tomar todo ese caos y volverlo predecible y manejable. Queremos lograr que la ciudad entienda patrones (por ejemplo, "en este barrio siempre hay problemas de ruido los viernes en la noche" o "después de llover, aumentan los reportes de baches"). El impacto esperado es que los tiempos de respuesta sean más rápidos, que la plata y la gente de los equipos de mantenimiento se usen donde más se necesitan, y al final del día, mejorar la calidad de vida en la ciudad tomando decisiones basadas en datos reales y no en suposiciones

# 2. Relación Beneficio/Coste (Análisis Económico)

**Análisis Económico (Ahorros):** Piensa en la cantidad de horas que gastan los empleados públicos hoy en día leyendo reportes, tratando de entender a qué departamento corresponde cada uno y organizando las rutas de trabajo. Al tener un sistema automatizado que procesa y clasifica esta información casi al instante, te vas a ahorrar miles de "horas-hombre" de trabajo manual y tedioso. Además, los especialistas y cuadrillas de reparación ya no darán vueltas innecesarias; irán directo a los problemas reales, optimizando el tiempo de todo el equipo.

**Retorno de Inversión (ROI):** Aunque implementar una plataforma de datos en la nube (con servidores, almacenamiento y herramientas analíticas) tiene un costo inicial importante, los ahorros operativos a largo plazo lo superan con creces. Imagina que el sistema cueste 100 y nos ahorre 300 al año en horas de trabajo, gasolina de los camiones de reparación y multas o demandas por negligencia; ese retorno hace que la inversión valga la pena rápidamente.

**Mayores Ingresos:** En un contexto público, "ingresos" no siempre significa vender más, sino gastar mejor el presupuesto. Si evitamos que un daño pequeño (como una fuga de agua) se convierta en un desastre gigante porque no lo detectamos a tiempo, estamos ahorrando dinero de los impuestos. El "ingreso" real es la optimización brutal de los recursos públicos; hacemos mucho más con la misma plata de siempre porque ahora somos eficientes.

# 3. Arquitectura

**Diagrama de Arquitectura:** (Nota: En esta sección de tu entrega, deberás pegar la imagen del diagrama de arquitectura que hayas diseñado para el proyecto, el cual probablemente incluya herramientas de ingestión, almacenamiento y visualización).

**Explicación Técnica:** Básicamente, el flujo funciona así: primero recolectamos los datos de los reportes del "NYC Service Request" a través de un canal o tubería que los lleva hacia nuestro almacenamiento principal (como un gran lago de datos en la nube, donde cabe de todo sin importar su formato). Una vez ahí, usamos herramientas de procesamiento potente (pensemos en motores de Big Data) que se encargan de limpiar la información, organizarla y cruzarla. Finalmente, esos datos ya procesados y limpios se conectan a un tablero visual (como Power BI) que los gerentes de la ciudad pueden mirar fácilmente para ver gráficos, tendencias y mapas de calor, entendiendo qué pasa en las calles en tiempo real sin tener que ver ni una sola línea de código.

4. # PIPELINE - Ingesta de Datos

**Estrategia Medallion**

<img width="380" height="434" alt="image" src="https://github.com/user-attachments/assets/825f0475-e54e-4ff9-8b57-bf9eb7c362bf" />

**Elaboración de PIPELINES y Workflows:** Automatización de la
ingesta de datos

**Databricks**

<img width="950" height="406" alt="image" src="https://github.com/user-attachments/assets/b2806630-6585-40ac-8b7f-aacbac21acd2" />

## 5. Modelos
Análisis Descriptivo: Resumen estadístico de la información
presentada.
Modelado: Descripción de los modelos que ayudan a sacar
provecho de los datos

## 6. APP o Visualización

**Dashboard PowerBI**

<img width="1549" height="841" alt="image" src="https://github.com/user-attachments/assets/164071ac-8328-4016-abcb-cf279d3a4e28" />



