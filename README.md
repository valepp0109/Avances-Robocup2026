RoboCup@Home — Video de Calificación

Team Andesbot · Robot: Martha · Ciudad/País · Fecha

Resumen

Video de una sola toma que demuestra: ASR/NLU, navegación y SLAM, detección de objetos, reconocimiento/seguimiento de persona, y recuperación ante fallos.

Requisitos de grabación
	•	Idioma: inglés o subtítulos en inglés.
	•	Overlays mínimos: mapa/pose, “object detected”, “person-ID”, “following”, “replanning”.
	•	Entorno: apartamento con cocina, sala y pasillo. Props: mug azul, bandeja móvil y obstáculo.

Guion paso a paso
	1.	Inicio
Cartel en pantalla: Team, robot, ciudad, fecha.
	2.	Presentación rápida
Robot: “Hello. I am Martha from Team Andesbot. I will execute a home service task showing speech, navigation, object detection, person recognition, and failure recovery.”
	3.	Comando en lenguaje natural
Operador: “Martha, bring the blue mug from the kitchen to Alice in the living room.”
Robot: “I understood. I will go to the kitchen, find the blue mug, and deliver it to Alice.”
	4.	Navegación a cocina con mapa
Robot se mueve.
Robot: “Navigating to the kitchen. Avoiding obstacles.”
	5.	Búsqueda y detección de objeto
Robot frente a la mesa.
Robot: “I am looking for a blue mug.”
Overlay: “Object detected: mug, confidence 0.92.”
Robot: “I found a blue mug.”
	6.	Manipulación o alternativa asistida
Opción A: el robot toma el mug y lo pone en una bandeja móvil.
Opción B:
Robot: “I cannot grasp safely. Please place the mug on my tray.”
Humano coloca el mug.
Robot: “Confirmed. I will deliver it to Alice.”
	7.	Navegación a sala y reconocimiento de persona
Robot: “I will find Alice.”
Overlay: “Person-ID: Alice”
Robot: “Hello, Alice. Here is your mug.”
	8.	Entrega
Si hay bandeja: humano toma el mug.
Robot: “Task part one complete. Do you need anything else, Alice?”
Alice: “Please guide me to the door.”
	9.	Seguimiento de persona y guía a la puerta
Robot: “I will follow you at a safe distance.”
Overlay: “Person-following active.”
	10.	Obstáculo y recuperación
Colocar obstáculo en el pasillo.
Robot: “Path blocked. Replanning.”
Robot rodea el obstáculo.
Robot: “Path cleared.”
	11.	Cartel final
Texto: Repositorio, email de contacto, ciudad/país.
