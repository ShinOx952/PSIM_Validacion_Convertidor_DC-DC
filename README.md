# Validación de Hardware: Regulador Reductor (Buck Converter)

**Estado del Proyecto:** Simulación y validación experimental. Este repositorio contiene el informe técnico completo, dividido en dos partes.

---

## 1. Resumen del Proyecto

Este proyecto documenta el proceso completo de validación de un circuito de **electrónica de potencia**, comparando la **simulación teórica** contra la **medición en hardware**.

El circuito analizado es un **Regulador Reductor (Buck Converter)**. El estudio se enfocó en:
1.  **Principios de Operación:** Análisis de la topología Buck y los circuitos auxiliares clave (opto driver, fuente aislada) necesarios para un control confiable.
2.  **Validación de Potencia:** Implementación y comprobación de la conmutación de un **MOSFET de potencia** de alto voltaje (IRFP460A) utilizando una señal de control PWM y verificando la consistencia de los resultados con instrumentación de laboratorio.

El objetivo es demostrar la capacidad de transicionar del diseño conceptual al prototipado y la medición de señales de conmutación de potencia.

### ➡️ Informes Técnicos Completos (Parte 1 y Parte 2)

El proyecto está documentado en dos reportes que cubren la teoría, la implementación y los resultados experimentales:

* **Parte 1: Principio de operación del regulador reductor (parte 1)**
    * [Ver Reporte Parte 1](./250324_341838_JARH_T07.pdf)
* **Parte 2: Principio de operación del regulador reductor (parte 2)**
    * [Ver Reporte Parte 2](./250330_341838_JARH_T08.pdf)

---

## 2. Herramientas y Metodología

* **Software de Simulación:** PSIM
* **Hardware e Instrumentación:**
    * MOSFET de Potencia (IRFP460A)
    * Instrumentación: **Osciloscopio**, Multímetro, Fuente de Alimentación DC.
    * Control: Señal PWM generada externamente (via DSP).

El proceso clave fue la **validación de la conmutación de alto voltaje** en el MOSFET, comprobando el funcionamiento de los circuitos auxiliares y midiendo las formas de onda críticas para asegurar la operación correcta del convertidor.

## 3. Competencias Demostradas

* **Análisis de Sistemas de Potencia:** Comprensión profunda de la topología Buck.
* **Validación de Hardware:** Experiencia práctica en el montaje de circuitos de potencia y en la medición de señales de conmutación.
* **Uso de Instrumentación:** Dominio en la configuración y uso de Osciloscopios y Multímetros para la caracterización de circuitos.
* **Análisis Documental:** Capacidad para generar documentación técnica detallada (informes en PDF) que respalden el trabajo de ingeniería.

---
