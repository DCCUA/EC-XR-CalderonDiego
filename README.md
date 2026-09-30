# XR Interaction Challenge

- **Apellidos y nombres:** Calderón, Diego
- **Curso:** Laboratorio de Realidad Extendida (XR) para Videojuegos
- **Docente:** Victor Alejandro Arroyo Castro

## Descripción del proyecto

Sala de entrenamiento XR con piso, iluminación direccional, límites visuales (4 paredes) y una mesa con tres objetos manipulables. Incluye un botón que enciende/apaga una luz mediante interacción a distancia, una esfera que cambia de color al seleccionarla, y una zona con contador que registra cuántos objetos agarrables hay sobre ella.

## Funcionalidades implementadas

- Escena `EC_XR_CalderonDiego` con piso, iluminación, paredes/límites y 5 objetos 3D (cubo, esfera y cilindro agarrables; botón y esfera de interacción a distancia).
- **Manipulación de objetos:** `Cubo_Grab`, `Esfera_Grab` y `Cilindro_Grab` tienen `Rigidbody` + `XR Grab Interactable`, se pueden tomar y soltar con el controlador XR.
- **Interacción a distancia:** `Boton_Luz` (enciende/apaga `Luz_Principal`) y `Esfera_Color` (cambia de color en cada selección), ambos con `XR Simple Interactable`.
- **Reto libre:** contador en tiempo real (`Zona_Conteo` + `Texto_Contador`) que muestra cuántos objetos agarrables están sobre la zona.

## Controles / instrucciones

1. Abrir la escena `Assets/Scenes/EC_XR_CalderonDiego.unity`.
2. Dar Play. Con el visor y los controles XR (o el XR Device Simulator):
   - Apunta y agarra los objetos `_Grab` sobre la mesa.
   - Colócalos sobre la zona morada para ver el contador subir.
   - Selecciona el botón amarillo para encender/apagar la luz.
   - Selecciona la esfera para que cambie de color.

## Evidencias

- Captura 1 — Vista general del escenario: 
- Captura 2 — Configuración XR / Inspector: 
- Captura 3 — Interacción funcionando: 
- Video demostrativo (máx. 1 min): 

## Tecnologías y paquetes utilizados

- Unity (versión del proyecto)
- Universal Render Pipeline (URP)
- XR Interaction Toolkit + Starter Assets
- XR Plug-in Management
- Input System / XRI Default Input Actions
