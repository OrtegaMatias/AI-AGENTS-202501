# Agentica alemana | Por: Alejandro Mauro

## 🏥 Contexto Clínico
- **Área usuaria / unidad clínica o de soporte:**  Equipo de desarrollo TI
- **Problema o necesidad abordada:** Facilitar y unificar las fuentes de conocimiento de TI
- **Objetivo del agente IA:** Centralizar las fuentes de la clinica mediante una solución agil que permita consultar de forma eficiente documentacion de interes para el area de TI.

## 🤖 Descripción de la Solución
- **Nombre de la solución / sistema:** Agentica Alemana
- **Tipo de agente IA:** Sistema Multi Agente + BM25
- **Entradas del sistema:** Datos clinicos, Ficha Clinica
- **Salidas esperadas:** Respuesta personalizada segun el paciente y el tipo de información
- **Tecnologías utilizadas:** ChatGPT 3.5 | Claude
- **Interfaz con el usuario:** ChatBot desarrollado en ambiente de aplicación creada por la clinica

## 🧱 Arquitectura Técnica
- **Integraciones con sistemas clínicos (HIS, RIS, LIS, etc):** N/A
- **Fuentes de datos utilizadas:** Fichas clinicas
- **Infraestructura:** Hibrido
- **Seguridad y privacidad:** N/A

## ⚙️ Entrenamiento y Personalización
- **Origen del conocimiento (docs, fichas, historiales, etc):** Fichas clinicas
- **Método de actualización del conocimiento:** embeddings mediante BM25
- **Idioma y especialización médica:** Tiene especialización en conceptos medicos

## 📊 Métricas y Evaluación
- **Métricas de desempeño:** N/A
- **Validación clínica realizada:** Pilotos y demos en el area de desarrollo
- **Limitaciones actuales:** Faltan herramientas para ampliar sus capacidades

## 📅 Estado y Proyección
- **Estado actual del proyecto:** Piloto
- **Próximos pasos:** Ampliarlo como solucion de creacion de agentes en todo CAS
- **Participantes clave:** Alejandro Mauro
- **Proveedor / Partner (si aplica):** n/a

## 🧩 Compatibilidad con el Ecosistema CAS
- **¿Alineado con la arquitectura TI de Clínica Alemana?:** n/a
- **¿Escalable a otras áreas?:** n/a
- **¿Cumple con políticas de TI institucionales?:** n/a

## 📝 Observaciones y Recomendaciones
- Este sistema es una creacion completa del backend para la creación de sistemas de agentes o multiagentes, aterrizandolo a un aplicativo con frontend desarrollado para crear una experiencia fluida en la formulacion, creacion e implementacion de agentes IA en toda la CAS segun sean las necesidades.
