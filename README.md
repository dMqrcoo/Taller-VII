## Taller VII 

# Chat WebSocket en ASP.NET Core

## Descripción

En este proyecto se implementa un servidor WebSocket en ASP.NET Core que permitirá comunicación en tiempo real entre múltiples clientes. Los clientes se conectan, envían mensajes y los reciben en un formato en vivo.

## Tecnologías utilizadas

- ASP.NET Core
- WebSockets
- Replit para despliegue

## Instrucciones

1. Ejecuta el servidor en Replit.
2. Ejecuta dos o más clientes localmente.
3. Observa cómo cada mensaje se retransmite a todos los clientes.

## Uso de WebSockets

Los WebSockets permiten una conexión persistente entre el cliente y servidor, ideal para comunicación bidireccional en tiempo real. Se usa `UseWebSockets()` y `AcceptWebSocketAsync()` en el servidor y `ClientWebSocket` en los clientes.


