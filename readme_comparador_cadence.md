# Comparador Iterativo de 4 bits - Diseño VLSI Full Custom 🔬

## Descripción General

Este repositorio documenta el **Diseño Eléctrico y Físico (Layout) Top-Down** de un comparador iterativo descendente de 4 bits. El proyecto abarca desde la derivación teórica de las ecuaciones lógicas hasta su implementación física lista para fabricación en silicio, utilizando **Cadence DFWII**.

![Layout del Comparador](imagenes/layout.png)
*(Nota: Asegúrate de colocar la captura de tu layout en una carpeta llamada `imagenes` y nombrarla `layout.png`)*

## Especificaciones Técnicas

El diseño ha sido optimizado estrictamente para ocupar la mínima área posible, manteniendo tiempos de propagación fiables.

* **Tecnología:** AMS CMOS 0.35 µm (1 POLY, 2 MET)
* **Tensión de Alimentación:** 3.3 V
* **Área Total de Silicio:** 2.783,67 µm² (W: 29.325 µm, L: 94.925 µm)
* **Consumo de Potencia Estático:** 11.11 nW
* **Retardo Post-Layout (Parásitos RC):** 6.60 ns

## Verificación y Validación

El diseño físico está preparado para su manufactura. Tanto la célula básica de 1 bit como la estructura final de 4 bits han superado con éxito las comprobaciones estándar de la industria:

* ✅ **DRC (Design Rule Check):** 0 errores.
* ✅ **LVS (Layout Versus Schematic):** Limpio (eléctricamente equivalente).
* ✅ **Resimulación Post-Layout:** Correspondencia funcional con las formas de onda teóricas, teniendo en cuenta los retardos por parásitos RC.

## Documentación

Para un análisis en profundidad de las ecuaciones lógicas (lógica CMOS Dual), las estructuras esquemáticas, las gráficas de simulación y las decisiones de diseño, por favor revisa la **Memoria del Proyecto (PDF)** adjunta en el repositorio.