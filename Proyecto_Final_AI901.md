# Proyecto Final AI-901
# Transformación Digital e Inteligencia Artificial para Alber Estimaciones

## Autor

Alba Nidia Ramírez Luna

---

# Resumen Ejecutivo

Alber Estimaciones es una empresa de construcción especializada en la elaboración de presupuestos de obra, números generadores y análisis de precios unitarios.

Previo al proyecto, gran parte de los procesos se realizaban manualmente, lo que generaba tiempos elevados de captura, errores humanos y dificultades para reutilizar el conocimiento técnico de la organización.

Para resolver esta problemática se planteó una estrategia de transformación digital basada en tecnologías Microsoft. En una primera fase se implementaron herramientas de Microsoft 365 y Microsoft Copilot para optimizar la gestión y revisión de información. Posteriormente, en una segunda fase utilizando Azure AI Foundry se desarrolló una aplicación web capaz de asistir a los usuarios en la redacción de conceptos para presupuestos de obra.

La solución actualmente opera desde Azure App Service y utiliza Inteligencia Artificial Generativa para agilizar la elaboración de presupuestos constructivos.

---

# 1. Descripción de la Empresa

**Alber Estimaciones** es una empresa constructora conformada por cinco colaboradores dedicados a la elaboración de:

- Presupuestos de obra.
- Números generadores.
- Catálogos de conceptos.
- Estimaciones.
- Análisis de precios unitarios.

A pesar de contar con amplia experiencia técnica, gran parte de sus procesos se realizaban manualmente, provocando una dependencia importante del conocimiento individual de cada colaborador.

---

# 2. Problema Identificado

Durante las entrevistas realizadas al personal se detectaron los siguientes problemas:

- Elaboración manual de números generadores.
- Procesos repetitivos para redactar conceptos constructivos.
- Captura manual de cantidades de obra.
- Errores frecuentes en hojas de cálculo.
- Información dispersa entre distintos usuarios.
- Tiempo excesivo empleado en la elaboración de presupuestos.
- Dificultad para localizar rendimientos de mano de obra para análisis de precios unitarios.

Estos factores afectaban directamente la productividad y la capacidad de respuesta de la empresa.

---

# 3. Objetivos del Proyecto

## Objetivo General

Implementar herramientas de Inteligencia Artificial utilizando tecnologías Microsoft para optimizar la elaboración de presupuestos de construcción.

## Objetivos Específicos

- Reducir errores en hojas de cálculo.
- Mejorar la colaboración entre usuarios.
- Estandarizar procesos internos.
- Facilitar la generación de conceptos constructivos.
- Disminuir tiempos de elaboración de presupuestos.
- Implementar una solución basada completamente en Azure.

---

# 4. Fase 1: Transformación Digital con Microsoft 365

## Diagnóstico Inicial

Se realizaron entrevistas y cuestionarios para identificar oportunidades de mejora en la gestión de información dentro de la empresa.

## Solución Implementada

### Estandarización en Excel

Se desarrollaron formatos estructurados para:

- Presupuestos.
- Números generadores.
- Catálogos de conceptos.
- Control de volúmenes de obra.

### Implementación de Microsoft Copilot

Microsoft Copilot se utilizó para:

- Validación de fórmulas complejas.
- Detección de inconsistencias.
- Revisión de cálculos.
- Apoyo en análisis de información.
- Generación de recomendaciones para optimización de documentos.

## Resultados

- Menor cantidad de errores.
- Procesos más rápidos.
- Mejor organización de información.
- Colaboración eficiente entre usuarios.

---

# 5. Agente de Consulta de Rendimientos

Uno de los principales retos era la búsqueda de rendimientos de mano de obra para la elaboración de análisis de precios unitarios.

Para resolver esta necesidad se desarrolló un agente utilizando Microsoft Copilot Empresarial.

## Capacidades

El agente puede responder consultas relacionadas con:

- Rendimientos de mano de obra.
- Cuadrillas de construcción.
- Actividades constructivas.
- Recomendaciones para análisis de precios unitarios.

## Beneficios

- Reducción del tiempo de búsqueda.
- Homologación de criterios técnicos.
- Conservación del conocimiento organizacional.

---

# 6. Fase 2: Desarrollo de Solución con Azure AI Foundry

## Problemática

Uno de los procesos más repetitivos dentro de la elaboración de presupuestos consiste en la redacción de conceptos constructivos.

Cada concepto requiere:

- Procedimiento constructivo.
- Materiales.
- Mano de obra.
- Herramienta y equipo.
- Alcances específicos.

La elaboración manual consume tiempo y genera diferencias en el estilo de redacción.

---

# 7. Solución Desarrollada

## Asistente Foundry para Desarrollo de Conceptos

Se desarrolló una aplicación web basada en Inteligencia Artificial Generativa para asistir a los usuarios en la creación de conceptos constructivos.

La aplicación permite generar conceptos técnicos a partir de instrucciones escritas en lenguaje natural.

### Ejemplo

Usuario:

> Desarrolla un concepto de pintura.

La aplicación solicita información adicional y posteriormente genera un concepto técnico completo listo para incorporarse al presupuesto.

---

# 8. Arquitectura Tecnológica

```text
Usuario
   │
   ▼
Aplicación Web
(Visual Studio)
   │
   ▼
Azure App Service
   │
   ▼
Azure AI Foundry
   │
   ▼
Modelo de IA Generativa
   │
   ▼
Respuesta al usuario
```

## Tecnologías Utilizadas

- Microsoft Azure
- Azure AI Foundry
- Azure App Service
- Visual Studio
- GitHub Copilot
- Microsoft 365
- Microsoft Excel
- Copilot Empresarial

---

# 9. Desarrollo de la Aplicación

La solución fue desarrollada utilizando Visual Studio con apoyo de GitHub Copilot para la generación de código y la aceleración del desarrollo.

Posteriormente fue publicada en Azure App Service para proporcionar acceso mediante navegador web.

## Flujo de Uso

1. El usuario describe la actividad constructiva.
2. El sistema envía la solicitud al modelo en Azure AI Foundry.
3. El modelo interpreta la solicitud.
4. Se genera una respuesta estructurada.
5. El usuario incorpora el resultado al presupuesto.

---

# 10. Principios de IA Responsable

## Transparencia

La aplicación informa al usuario que interactúa con un sistema de Inteligencia Artificial.

## Confiabilidad

La IA funciona como herramienta de apoyo y no sustituye la revisión profesional del estimador.

## Seguridad

Toda la infraestructura opera dentro del ecosistema Microsoft Azure.

## Supervisión Humana

Los conceptos generados deben ser validados por personal especializado antes de su utilización en proyectos reales.

---

# 11. Evidencia de la Solución

## Pantalla Principal del Asistente

La figura muestra la interfaz principal de la aplicación desplegada en Azure App Service.

![Pantalla Principal](Pantalla%20Principal.png)

---

## Ejemplo de Interacción con el Asistente

La siguiente imagen muestra una conversación donde el sistema inicia la recopilación de información necesaria para elaborar un concepto constructivo.

![Conversación con IA](Conversación%20con%20IA.png)

---

## Despliegue en Azure App Service

La aplicación fue publicada exitosamente en Azure App Service permitiendo su acceso mediante navegador web.

![Azure App Service](Azure%20App%20Service.png)

---

# 12. Resultados Obtenidos

| Indicador | Antes | Después |
|------------|---------|---------|
| Elaboración de conceptos | Manual | Asistida por IA |
| Búsqueda de rendimientos | Manual | Asistente IA |
| Revisión de fórmulas | Manual | Microsoft Copilot |
| Compartición de información | Limitada | Centralizada |
| Tiempo de elaboración de presupuestos | Alto | Reducido |

---

# 13. Enlace al prototipo funcional
Aplicación desplegada:

https://chatbot-foundry-proy-bany.azurewebsites.net

---

#14. Conclusiones

La implementación de soluciones basadas en Microsoft Copilot, Azure AI Foundry y Azure App Service permitió iniciar un proceso de transformación digital en Alber Estimaciones.

La aplicación desarrollada demuestra que incluso una empresa pequeña puede beneficiarse de la Inteligencia Artificial para automatizar tareas repetitivas y mejorar la productividad.

La solución desarrollada reduce tiempos de elaboración de presupuestos, mejora la calidad de los conceptos constructivos y facilita la reutilización del conocimiento técnico acumulado por la organización.

Asimismo, el proyecto permitió aplicar de manera práctica los conocimientos adquiridos durante el curso AI-901 utilizando servicios reales de Microsoft Azure.
