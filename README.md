# Sistema de Procesamiento de Pagos para un E-commerce 💳

## Descripción 📝
Este proyecto es un sistema backend para procesar pagos en una plataforma de e-commerce. El sistema soporta múltiples métodos de pago (tarjeta de crédito, PayPal, criptomonedas) y gestiona transacciones de manera segura y eficiente. Está diseñado para ser escalable y fácil de integrar con otras plataformas.

## Requisitos 🎯
### Estructuras de datos
- **Cola de prioridad (PriorityQueue)**: Para procesar transacciones según su urgencia (por ejemplo, pagos express primero).
- **Diccionario (Dictionary)**: Para almacenar el estado de cada transacción (pendiente, completada, fallida).

### Algoritmos
- **Validación de tarjeta de crédito**: Usa el algoritmo de Luhn para validar la autenticidad de una tarjeta de crédito.
- **Detección de transacciones fraudulentas**: Detecta múltiples intentos de pago en un corto período de tiempo.

### Patrones de diseño
- **Strategy**: Para manejar diferentes métodos de pago (tarjeta de crédito, PayPal, criptomonedas).
- **Singleton**: Para garantizar que solo exista una instancia del procesador de pagos.

### Lógica de programación
- **Validación de datos de pago**: Valida que los datos de pago sean correctos antes de procesar la transacción.
- **Reversión de transacciones**: Implementa una función para revertir una transacción en caso de error.

## Tecnologías utilizadas 💻
- **Lenguaje de programación**: C#
- **Framework**: .NET Core
- **Patrones de diseño**: Strategy, Singleton.
- **Herramientas**: Git, GitHub, Visual Studio.