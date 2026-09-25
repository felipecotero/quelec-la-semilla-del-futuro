# Quelec y la semilla del futuro 🎭🌱
### Cuaderno de Producción Escénica, Dirección de Arte y Recursos Técnicos

Repositorio oficial y portal online de trabajo para la coordinación de producción, dirección de arte, ingeniería y equipo creativo de la obra teatral de gran formato **"Quelec y la semilla del futuro"**.

---

## 🌐 Acceso Online
El portal de producción y el simulador escénico están disponibles en GitHub Pages:
**[https://felipecotero.github.io/quelec-la-semilla-del-futuro/](https://felipecotero.github.io/quelec-la-semilla-del-futuro/)**

---

## 📖 Sinopsis Argumental
> *En una ciudad gris y fría, donde está prohibido jugar, imaginar y soñar, vive Quelec, un niño que se resiste a aceptar una vida sin alegría. Junto a su hermano y su abuela, descubre la existencia de un portal hacia el futuro donde se encuentra una semilla capaz de devolver la felicidad al mundo.*
>
> *Mientras Los Gruñones intentan evitarlo a toda costa, Quelec emprende un viaje fantástico de juegos y desafíos. Cuando la semilla finalmente florece, los Gruñones recuperan sus memorias de infancia y la ciudad se transforma en un estallido de color, música, juego y fiesta.*

---

## 🛠️ Herramientas y Módulos Activos

### 1. Maqueta 3D Completa de la Plaza de Toros (`quelec-maqueta-3d.html`)
- **Motor**: Three.js autónomo con modelo glTF integrado.
- **Función**: Maqueta tridimensional navegable del espacio escénico completo: arena circular (40 m de diámetro), graderías de espectadores, rampa monumental (40 m), estructura del Portal hacia el futuro y niveles de solera.
- **Herramientas**: Selector de capas constructivas, 6 cámaras prefijadas (General, Público, Arena, Planta, Frontal, Lateral), modo alambre, control de intensidad y posición de luz, giro automático y lectura de cotas métricas reales.

### 2. Maqueta 3D con Simulación de Iluminación y Haces Volumétricos (`quelec-maqueta-3d-luces.html`)
- **Motor**: Three.js con simulación de iluminación escénica teatral y cálculo de haces volumétricos en tiempo real.
- **Función**: Calibración y diseño de luminarias en el recinto: fixtures teatrales individuales y grupos (elipsoidales de pasarela, frontales y contra), encendido/apagado selectivo, proyección de sombras reales, haces volumétricos visibles en sala y conmutación de luz de trabajo.

### 3. Simulador 3D de Aro de Humo Escénico (`aro-humo-escenico.html`)
- **Motor**: Three.js con simulación física interactiva.
- **Función**: Calibración en tiempo real del vórtice toroidal de niebla (tiro escénico, dispersión, turbulencia de sala, temperatura de color e iluminación escénica) y exportación de fichas técnicas (.txt).
- **Escena**: Efecto especial del *Portal hacia el futuro*.

### 4. Matriz de Producción e Ingeniería Escénica (`index.html`)
- **La Cama Aérea de la Abuela**: Estructura tubular ligera con ruedas de carreola (ring 27/29) y suspensión aérea en polipasto de 2 puntos para descenso por rampa y vuelo sobre la arena.
- **Orquídea Gigante & Flores Telescópicas**: Mecanismo de plataforma tijera central (de 2 m hasta 10 m de elevación) con despliegue de pétalos en dos niveles y 6 a 8 flores periféricas en la arena.
- **Juguetes Gigantes de la Escena del Juego**: Barco de origami (2.50 × 1.80 m), Peluche cósmico gigante y Balón inflable de 2 m con efecto de ponchadura.
- **El Portal y la Rampa (40 m)**: Rampa monumental que conecta la arena con la tribuna y solera, truss circular suspendido y pantalla circular ("Pink Floyd").
- **La Semilla Luminosa**: Objeto autónomo con iluminación interna y sistema de manillas LED mapeadas para el público.
- **Dirección de Arte y Vestuario**: Transición estética de la monocromía de la Ciudad Gris al estallido botánico de color, con estética *steampunk* de principios de siglo XX para Los Viajeros.

---

## 👥 Ficha Artística y Técnica Principal

- **Quelec**: Juan Camilo Barragán
- **La Abuela**: Patricia Tamayo
- **El Viajero / Narrador**: Rafael Zea
- **Hermano de Quelec**: José Luis Díaz
- **Los Gruñones**: Milton López Arrubla, Juliana Herrera, Mario Escobar, Mónica Giraldo
- **Coordinación de Producción**: Felipe Camacho Otero
- **Dirección de Arte y Vestuario**: Sandra
- **Ingeniería de Sonido**: Andrés Peláez
- **Diseño de Iluminación**: Software Capture / Iluminación 3D

---

## 🚀 Uso Local
Para visualizar el portal en un entorno local:
```bash
# Clonar repositorio
git clone https://github.com/felipecotero/quelec-la-semilla-del-futuro.git

# Abrir el portal
open index.html
```
O servir con cualquier servidor HTTP ligero:
```bash
npx serve .
# o
python3 -m http.server 8000
```
