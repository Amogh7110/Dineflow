# Socket.IO Events

| Event           | Direction       | Payload              |
|-----------------|-----------------|----------------------|
| order:placed    | client → server | `{ orderId, items }` |
| table:updated   | server → client | `{ tableId, status }`|
| chat:message    | bidirectional   | `{ sessionId, text }` |
