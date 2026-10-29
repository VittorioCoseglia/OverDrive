# Pedal Overdrive TL071 🎛️

Un pedal de efectos para guitarra basado en el clásico circuito **[Ibanez Tube Screamer](https://es.wikipedia.org/wiki/Ibanez_Tube_Screamer)**. Permite controlar y variar el nivel de saturación de la señal de audio mediante el potenciómetro de *Drive*.

![Vista 3D del Pedal](img/3D.png)

---

## 📋 Tabla de Contenidos
- [Características Principales](#-características-principales)
- [Lista de Materiales (BOM)](#-lista-de-materiales-bom)
- [Esquemático y PCB](#-esquemático-y-pcb)
- [Carcasa / Enclosure](#-carcasa--enclosure)
- [Software Utilizado](#-software-utilizado)

---

## 🚀 Características Principales

- **Controles:** Potenciómetro de *Drive* para ajustar el nivel de recortes/saturación.
- **Diseño de PCB:** Monocapa (*single-layer*) con tecnología de inserción **[THT](control-board/readme.md)**.
- **Carcasa:** Estructura modular apta para **impresión 3D** utilizando tornillería **M3**.

> [!WARNING]
> **Alimentación Eléctrica:** Este circuito requiere una fuente de alimentación de **9V DC con polaridad de centro negativo** ($\text{9V DC, Center-Negative}$), el estándar de pedales de efecto. Conectar una polaridad invertida puede dañar los componentes.

---

## 📦 Lista de Materiales (BOM)

Consulta la lista completa de componentes electrónicos y de hardware necesarios para el ensamblaje en el siguiente enlace:

📄 **[Ver Lista de Materiales (BOM)](docs/bom.md)**

---

## 📐 Esquemático y PCB

### Esquema Electrónico
![Esquema Electrónico](img/Circuito.png)

### Diseño de la PCB
Diseñado en una sola capa (*Single Layer*) para facilitar el ruteado y el grabado casero o fabricación de bajo costo.

![Diseño de PCB](img/PCB.png)

---

## 🧷 Carcasa (Case)

El chasis o carcasa está optimizado para su **impresión 3D** y diseñado para ensamblarse mediante tornillos roscados **M3**.

![Diseño de la Carcasa](img/Case.png)

---

## 🛠️ Software Utilizado

| Herramienta | Uso / Función | Enlace |
| :--- | :--- | :--- |
| **KiCad 9.0** | Diseño del esquemático y PCB | [Sitio Oficial](https://www.kicad.org/) |
| **SolidWorks 2022** | Modelado 3D de la carcasa | [Sitio Oficial](https://www.solidworks.com/) |
| **NI Multisim 14.1** | Simulación de la respuesta del circuito | [Información](https://en.wikipedia.org/wiki/NI_Multisim) |