# Vacation Bot

Proyecto de simulación de un chatbot orientado a la gestión de vacaciones de empleados.

## Objetivo
Automatizar el proceso de solicitud de vacaciones mediante un chatbot capaz de:
- Consultar saldo disponible de días
- Validar fechas solicitadas
- Gestionar aprobaciones de supervisor y RRHH
- Actualizar registros de solicitudes

## Tecnologías propuestas
- Python
- Telegram Bot API
- Pandas
- OpenPyXL
- Excel (base de datos simulada)

## Estructura del proyecto

```bash
vacation-bot/
│
├── main.py
├── requirements.txt
├── README.md
│
├── database/
│   └── empleados.xlsx
│
├── docs/
│   ├── bpmn.pdf
│   └── manual_usuario.pdf
│
└── src/
    ├── chatbot.py
    ├── estados.py
    └── validaciones.py
```

## Estado del proyecto
Proyecto desarrollado como simulación académica para el Trabajo Práctico Integrador de Organización Empresarial.
