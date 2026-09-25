# Drivers arquitectónicos

Integramos los requisitos, atributos de calidad y restricciones identificados
anteriormente, y seleccionamos los que tienen una influencia significativa en el
diseño de la arquitectura.

| ID | Driver arquitectónico | Origen | ¿Por qué influye en la arquitectura? |
|---|---|---|---|
| DA01 | El sistema debe soportar un incremento importante de usuarios durante campañas comerciales. | AC03 – Escalabilidad | Puede influir en la estrategia de escalamiento y despliegue. |
| DA02 | El sistema debe mantener tiempos de respuesta adecuados durante una alta concurrencia. | AC01 – Rendimiento | Puede influir en la comunicación entre componentes, procesamiento y almacenamiento. |
| DA03 | El sistema debe proteger los datos de usuarios y operaciones de compra. | AC04 – Seguridad | Puede influir en autenticación, autorización y protección de datos. |
| DA04 | El sistema debe integrarse con una pasarela de pago externa mediante una API. | RC04 – Pasarela de pago | Condiciona la forma de comunicación e integración con servicios externos. |
| DA05 | El sistema debe utilizar una API REST para la comunicación entre frontend y backend. | RC03 – API REST | Limita las alternativas de comunicación entre las partes del sistema. |
| DA06 | El sistema debe validar la identidad de cada usuario antes de exponer sus endpoints. | RC06 – Autenticación | Condiciona el diseño de la capa de presentación y de negocio (middleware de autenticación/autorización). |
| DA07 | El sistema debe integrarse con un servicio de facturación electrónica. | RC07 – Facturación electrónica | Condiciona la integración del módulo de Pedidos con un sistema externo adicional. |
