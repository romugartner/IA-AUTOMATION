Proyecto N8N - IA AUTOMATION 

Se construyo un Ecosistema de Automatización IA, donde se consolido un perfil de Arquitecto de Flujos IA integrando una base de datos dinámica, un motor de razonamiento (LLM) y una salida multicanal profesional.

1. Se eligio un caso de uso de atencion al cliente mediante la recibida de un mensaje

2. Se eligio como Estructura/"Cerebro" (Base de Datos) : 
Notion

Se incluyo campos de estado (ej: Pendiente, Procesado por IA, Aprobado por Humano)

Sincronización: Si usas múltiples fuentes, recuerda que la sincronización debe ser gestionada mediante el flujo de automatización.

3. Construye el "Corazón" (Orquestación Lógica)
Desarrolle el flujo con n8n siguiendo estos estándares de arquitectura limpia:

Trigger Inteligente: Configura disparadores específicos (Telegram Trigger)

Motor de IA (GEMINI) donde limite los Max Tokens para optimizar costos.


4. Implemente el "Human-in-the-loop"
Para evitar el "Efecto Metralleta", mi flujo se detuvo antes de una acción crítica.

Validación: Crea una ruta (mail) y espere el feedback humano antes de contactar al cliente final.


Slack/Gmail: Mapea los hilos (Thread ID) para mantener la conversación organizada.


Test de Estrés: Ejecute el flujo al menos 5 veces. 

Realice la Prueba del "Camino Infeliz" (ej. enviando datos incompletos) para verificar que tus filtros y rutas de error funcionan.

Video Demo (3 min): Muestra el Trigger, el procesamiento en el orquestador y el resultado final.

Oculte mis API Keys y credenciales sensibles en la grabación.

Entregables: Subi el PDF con el diagrama de arquitectura, el link a tu base de datos (modo lectura) y el archivo JSON/Blueprint de tu flujo.

Diagrama de Arquitectura: Documento en formato PDF.
Lógica del Flujo: Archivo técnico .json (si usás n8n) o .blueprint (si usás Make).
Enlaces Obligatorios: Link en modo lectura a la Base de Datos (Notion) y Screenshots / capturas de pantalla de evidencias del flujo creado.
63%
