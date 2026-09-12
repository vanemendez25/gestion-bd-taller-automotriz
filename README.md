# 🚗 Sistema de Gestión de Base de Datos: Taller Automotriz
<!-- Aquí está la animación del coche lista y funcionando -->
<div align="center">
  <img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExcDFtaGZzY2lxaTIxeHF2bDRuMGZ3YzZqeWxjeTFnN2VlZGQ5YzV5aSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/LSLc236sXv4i28O95C/giphy.gif" width="180" alt="Car Animation" />
</div>
<br>

<p align="center">
  <img src="https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white" alt="MariaDB" />
  <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="SQL" />
  <img src="https://img.shields.io/badge/HeidiSQL-008000?style=for-the-badge&logo=databricks&logoColor=white" alt="HeidiSQL" />
</p>

> **El Problema:** El manejo manual de información en talleres genera pérdida de datos, duplicidad y dificultad para rastrear historiales. 
> **La Solución:** Diseño e implementación de una base de datos relacional desde cero para centralizar la información de clientes, inventarios y finanzas en un sistema seguro y consultable.

---

### 🗄️ Arquitectura y Datos

Para poblar el sistema y realizar pruebas realistas, se generaron y procesaron archivos CSV. 
*   **Volumen:** 715 registros insertados mediante el comando `LOAD DATA LOCAL INFILE`.
*   **Estructura Relacional:** 6 tablas principales con llaves primarias y foráneas (`clientes`, `vehiculos`, `servicios`, `productos`, `ordenes_trabajo`, `pagos`).
*   **Diseño:** Creación de un diagrama Entidad-Relación basado en los procesos clave del negocio.

<!-- VANE: Aquí puedes arrastrar la imagen de tu Diagrama Entidad-Relación para que se vea súper pro -->
<div align="center">
  <i>(Espacio para tu Diagrama Entidad-Relación)</i>
</div>

### 🛠️ Consultas y Extracción de Valor

Se desarrollaron consultas SQL avanzadas (usando `INNER JOIN`, `GROUP BY`, `HAVING`) para responder preguntas clave y facilitar la toma de decisiones administrativas:

*   📦 **Control de Inventario:** Identificación automática de productos con stock crítico (<= 10 unidades).
*   💰 **Estimación de Costos:** Cálculo automático de presupuestos uniendo costos base de servicios y precios unitarios de refacciones.
*   📈 **Análisis Financiero:** Identificación de los clientes que generan mayores ingresos y rastreo de pagos parciales o pendientes.

---

### 📄 Documentación Técnica

Todo el análisis detallado del problema, el diagrama relacional y la evidencia de la ejecución del código SQL se encuentran en el reporte técnico.

<div align="center">
  <a href="https://github.com/vanemendez25/base-de-datos-taller-mecanico/blob/main/Base_de_datos_relacional_Taller_Mecanico.pdf">
    <img src="https://img.shields.io/badge/📄_Ver_Reporte_Técnico-PDF-red?style=for-the-badge" alt="Ver PDF" />
  </a>
</div>

---

### 👩🏻‍💻 Autora

**Vanessa Méndez**  
*Estudiante de Ingeniería en Ciencia de Datos | Universidad Veracruzana*

[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/vanemendez25)
