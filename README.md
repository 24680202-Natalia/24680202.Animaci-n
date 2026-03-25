# Instituto Tecnológico Nacional de México
# Instituto Tecnológico de Cuautla
# 24680202 Natalia Reyes Baños Semestre:4 Grupo:3
# Animación 2D de Pac-Man en Blender (Grease Pencil)

Este repositorio es una guía paso a paso para recrear una escena de animación 2D utilizando la herramienta **Grease Pencil** en Blender.
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/c2329d89-796d-4e9a-89d6-262b0e9b314e" />


## 🛠️ Paso 1: Configuración del Proyecto
1. Abre Blender y selecciona **File > New > 2D Animation**.
2. En el panel de la derecha (Scene Properties), asegúrate de que la resolución sea la adecuada (ej. 1920x1080).
3. Asegúrate de estar en el modo **Front Orthographic** (tecla `1` del teclado numérico) para trabajar en un plano plano.
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/6ae7b732-4668-431a-8027-cd7d7d85f387" />

## 🎨 Paso 2: Dibujando a Pac-Man y los Fantasmas
1. **Capas (Layers):** En el panel de propiedades del Grease Pencil, crea capas separadas para "Pacman" y "Fantasmas". Esto te permite editarlos de forma independiente.
<img width="322" height="440" alt="image" src="https://github.com/user-attachments/assets/8383bf06-d967-4006-8c4f-6c540e7ecefc" />

2. **Materiales:** Crea materiales con "Stroke" (contorno) y "Fill" (relleno). 
   - Pac-Man: Amarillo sólido.
   - Fantasmas: Azul, Verde y Morado.
     <img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/fb9af72c-e2a2-4c78-bf0a-eb7a8186494c" />

3. **Herramientas:** Usa la herramienta **Circle** para el cuerpo de Pac-Man y el **Draw tool** para las formas irregulares de los fantasmas.

## 🎞️ Paso 3: Animación (Timeline y Keyframes)
Para que Pac-Man "coma" a los fantasmas:
1. **Keyframes:** En la línea de tiempo inferior, inserta un fotograma clave en el Frame 1.
<img width="1584" height="272" alt="image" src="https://github.com/user-attachments/assets/ccaf708d-94f5-4d7a-947a-dfb146eb82fa" />

2. **Transformación:** Cambia al modo **Object Mode** o **Edit Mode** para mover los personajes.
<img width="325" height="253" alt="image" src="https://github.com/user-attachments/assets/27e209e3-484f-4c83-a2d6-2409bdab5432" />

3. **Interpolación:** - Mueve el marcador de tiempo al Frame 10.
   - Desplaza a Pac-Man hacia adelante.
   - Blender creará automáticamente la transición si tienes activado el **Auto Keying** (el botón del círculo rojo).
<img width="925" height="191" alt="image" src="https://github.com/user-attachments/assets/5f67f0f1-beaf-440a-9d63-67df3653987e" />


## 💡 Consejos Visuales
* **Opacidad:** Si quieres que la boca de Pac-Man tenga ese efecto sombreado (como se ve en la imagen original), ajusta la opacidad de la capa de relleno en el material.
* **Cámara:** Asegúrate de que tus dibujos estén dentro del marco de la cámara (el rectángulo gris oscuro) para que aparezcan en el render final.
  

---

## 📦 Cómo exportar
1. Ve a **Output Properties** (icono de la impresora).
2. Elige el formato de archivo (FFmpeg Video es ideal para clips rápidos).
3. Presiona `Ctrl + F12` para renderizar la animación.

### Resultado final
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/4ad1662d-5eae-4536-95ce-02400d04bdf6" />
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/d7564afe-97e1-41e6-aa22-0c9cae955cf1" />
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/ed31d7ac-c440-4884-bf5c-0ce01a33880f" />
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/8fb7c85d-a3c1-4be6-8f6a-03032ac8b04e" />
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/d3da6cac-bbfc-441a-b381-8559dfc70d62" />
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/120c2d53-258d-4440-a90c-27f280a63129" />





