# Base de Datos Relacional para Taller Mecánico: Total Car Care Center 🚗

## 1. Resumen
Este proyecto consistió en el diseño, modelado e implementación de una base de datos relacional desde cero para gestionar la operación diaria de un taller mecánico automotriz. El objetivo fue estructurar la información para reducir inconsistencias y facilitar la toma de decisiones administrativas.

## 2. Contexto y Problema
El manejo manual y desorganizado de la información en talleres mecánicos genera pérdida de datos, duplicidad y dificultad para rastrear historiales de vehículos. Este proyecto resuelve ese problema centralizando la información de clientes, inventarios y finanzas en un sistema seguro y consultable.

## 3. Datos y Fuente
Se generaron y procesaron archivos CSV con datos ficticios realistas para poblar la base de datos[cite: 2]. En total se insertaron 715 registros distribuidos en las 6 tablas principales del sistema.

## 4. Metodología
* **Análisis y Modelado:** Identificación de procesos clave y diseño de un diagrama Entidad-Relación.
* **Estructura Relacional:** Creación de 6 tablas principales con llaves primarias y foráneas (`clientes`, `vehiculos`, `servicios`, `productos`, `ordenes_trabajo`, `pagos`).
* **Implementación:** Creación de la base de datos en MariaDB e importación masiva de datos usando el comando `LOAD DATA LOCAL INFILE`.
* **Consultas Estratégicas:** Desarrollo de consultas SQL avanzadas (uso de `INNER JOIN`, `GROUP BY`, `HAVING`) para extraer valor de negocio.

## 5. Resultados Principales
A través del análisis SQL, el sistema permite responder preguntas clave del negocio, tales como:
* **Control de Inventario:** Identificación automática de productos con stock crítico (<= 10 unidades).
* **Estimación de Costos:** Cálculo automático de presupuestos uniendo costos base de servicios y precios unitarios de refacciones.
* **Análisis Financiero:** Identificación de los clientes que generan mayores ingresos y rastreo de pagos parciales o pendientes.
## 6. Tecnologías Usadas
* **SGBD:** MariaDB
* **Lenguaje:** SQL (DDL y DML)
* **Herramientas:** HeidiSQL para administración y ejecución de consultas

## 7. Archivos en este repositorio
* 📂 [Diseño e implementación de una base de datos relacional.pdf](https://github.com/vanemendez25/base-de-datos-taller-mecanico/blob/main/Base_de_datos_relacional_Taller_Mecanico.pdf): Documentación técnica que incluye el análisis del problema, diagrama relacional detallado y evidencia de la ejecución del código SQL.
