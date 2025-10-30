# 🎵 Proyecto Pure Data - Kevin Yavari - Jean karlita buitrago

**LINK EXPLICACION:** *(https://www.youtube.com/watch?v=nRGX9IvJBmY)*  
**LINK DEMO:** *(https://www.youtube.com/watch?v=wLyXERc_VWY)*  
---
## 📝 Descripción del Proyecto

Usando la app **OSC Controller (Open Sound Control)** y el lenguaje **Pure Data (PD)**, se implementó un **sistema de DJ interactivo**.  
La idea principal fue utilizar todos los widgets disponibles en la app (sliders, switches y botones) para generar una experiencia completa de mezcla musical.  
Cada interacción produce una **respuesta auditiva en PD**, permitiendo crear piezas de música electrónica al estilo de un DJ en vivo.

El sistema cuenta con **cuatro páginas** de control, cada una dedicada a un conjunto distinto de funciones musicales como control de volumen, tempo, piano, batería y efectos.

---
## 🧩 P1 - Control de Volúmenes y Ritmo (Sliders, Switches, Botones)

### 🎚️ Sliders
- **Slider 1:** Controla el volumen principal.  
- **Slider 2:** Controla el volumen de acompañamiento.  
- **Slider 3:** Controla el volumen de efectos.  
- **Slider 4 (Tempo):** Ajusta la velocidad general o tempo del proyecto.  

### 🔘 Switches (ON/OFF)
- **Switch 1:** Activa una base con tempo lento.  
- **Switch 2:** Activa una base con tempo medio.  
- **Switch 3:** Activa una base con tempo rápido.  

### 🪇 Botones
- **Botón 1:** Reproduce un platillo corto.  
- **Botón 2:** Reproduce un platillo medio.  
- **Botón 3:** Reproduce un platillo largo o sostenido.  

---

## 🎛️ P2 - Control Duplicado (Configuración Alterna)

Página de modulación avanzada mediante los ejes de frecuencia y amplitud.

- **2 Ejes de Control:**
Eje Y (Frecuencia): Ajusta la frecuencia del sonido para cambiar el tono.
Eje X (Amplitud): Modifica la amplitud del sonido para variar el volumen percibido.

---

## 🎹 P3 - Teclado de Piano (Sonidos Melódicos)

Página dedicada a la ejecución de notas y acordes de piano.

### 🎵 Controles
- 24 switches asignados a diferentes notas del piano.  
- Cada switch reproduce una nota específica, permitiendo tocar melodías o acompañamientos.  

---

## 🥁 P4 - Batería 

Página centrada en los sonidos de percusión.

### 🥁 Controles
- Varios botones asignados a las diferentes partes de una batería:  
  - Bombo  
  - Caja  
  - Hi-hat  
  - Toms  
  - Platillos  
  - Redoblante  

### 🎶 Función
Cada botón reproduce un sonido correspondiente, permitiendo armar ritmos completos de batería.  

---

**Autor:** Kevin Yavari y Jean Karlo
**Herramienta:** Pure Data  
**Objetivo:** Crear un sistema interactivo de control de audio y ritmo con múltiples páginas y configuraciones.
