# jaime.github.io
MVP (Minimum Viable Portfolio)

# Acerca de mí 
Ingeniero en Transporte y Logística con un MBA en el ramo Logístico, en proceso de certificación en análisis
de datos con experiencia en extracción, limpieza y modelado de datos para la toma de decisiones estratégica. 

## Habilidades técnologicas
- Análisis de datos utilizando **Excel/SQL/Python**
- Visualización de datos con **Google Sheets Table**
- Uso de plataformas CRM **IA Tables Cianiao System**

## Habilidades blandas
Pensamiento análitico | Pensamiento estratégico | Atención al detalle | Comunicación Efectiva | Negociación 
Presentaciones en público | Trabajo en Equipo | Liderazgo | Gestion de Equipos | Empatía | Mentoria
Gestion del Tiempo | Priorización de Tareas | Orientación a Resultados | Gestion de Proyectos | Resilencia
Compromiso | Honestidad

# Proyectos Seleccionado

**Proyecto 1: 
Análisis de embudo y retención para Mercado Libre**

- **Situación:** Identificar la tase de conversión entre cada etapa del embudo del sistema de compra de Mercado
  Libre por país, asì como también conocer la retención de usuarios en los distintos cohortes de tiempo.
- **¿Qué hice?** Explore el esquema del modelo para comprender el comportamiento de los datos y el flujo de usuarios
  dentro de la plataforma "first_visit" hasta la compra "purchase". Con lo anterior empece a construir el embudo de la
  conversion, creando CTEs por etapa en un rango de periodo del 2025-01-01 al 2025-08-31. Donde cálcule la conversión
  entre etapas, para posteriormente segmentar el Embudo General por país. Habiendo identificado los puntos anteriores,
  se solicito calcular la cantidad de usuarios activos acumulados por pais por cohorte de días, el primer periodo
  hasta los 7 días, segundo periodo hasta los 14 dìas, luego 21 días y finalmente 28 días. Con la información previa,
  se obtuvo el porcentaje de retención por país para entender el impacto de la situaciones identificadas conforme a lo
  solicitado.
  
- **Resultado:** Se observaron varios escenarios de los cuales destacamos que la mayor pérdida en el funnel del proceso,
  lo tenemos de seleccionar el producto a agregarlo al carrito con un 65.8% de impacto. Por el otro lado identificamos
  que la mayor cantidad de usuarios cae drásicamente después del 21 dìa.
  
- **Tablas de Resultados**

  **Embudo General**

   <br>
   <img src="https://bjames93.github.io/Embudo_General_Mercado_Libre.png" width="900" alt="Embudo Mercado Libre">

