# MultiSafío 1.0.16

Hotfix de estabilidad para la versión 1.0.15.

- Retira **Collections Of Optimizations 5.0** porque su integración con JEI 15.20.0.112 cerraba el cliente al entrar a un mundo.
- Retira **ImmediatelyFast 1.5.5 para Minecraft 1.20.4** porque su optimización del atlas de fuentes podía cerrar Minecraft 1.20.1 durante la carga visual con el error `Image is not allocated`.
- Conserva **OhHayden's Mob Control**, **More Sticks**, las misiones, ruletas, eventos, mundo, skins y menús personalizados.
- El parche elimina automáticamente los dos mods incompatibles y sus configuraciones sin tocar mundos ni datos personales.

La revisión se hizo únicamente con los registros y la estructura del paquete. La prueba de apertura y entrada al mundo queda a cargo del usuario.
