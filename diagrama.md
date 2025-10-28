```mermaid
flowchart LR
    A[Estudiante] -->|Reserva| B[Clase]
    B --> C{Disponible?}
    C -->|Sí| D[Confirmar]
    C -->|No| E[Notificar]
```
