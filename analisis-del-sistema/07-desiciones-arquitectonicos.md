# 07. Decisiones arquitectónicas

Las siguientes decisiones responden a los problemas planteados
por los drivers arquitectónicos del sistema.

| Driver arquitectónico | Problema que plantea | Decisión que responde |
|---|---|---|
| DA01 - Escalabilidad | Aumentarán los usuarios durante las campañas. | Monolito modular con posibilidad de escalamiento horizontal. |
| DA02 - Rendimiento | Habrá alta concurrencia. | Incorporar caché y optimizar la comunicación y el procesamiento. |
| DA03 - Seguridad | Hay datos sensibles. | Implementar autenticación y autorización. |
| DA04 - Pago externo | Hay que comunicarse con una pasarela de pago. | Integración mediante API y adaptadores. |
| DA05 - API REST | El frontend y el backend deben comunicarse mediante REST. | Separar la interfaz y el backend mediante una API REST. |
| DA06 - Mantenibilidad | Los cambios no deben afectar innecesariamente otros módulos. | Modularidad y Clean Architecture. |