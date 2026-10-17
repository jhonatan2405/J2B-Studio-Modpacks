# MultiSafío 1.0.12 para exaroton

Paquete completo corregido: `exaroton-multisafio-1.0.12-subir-corregido-v2.zip`

Parche para una instalación 1.0.12 ya subida: `exaroton-multisafio-1.0.12-datapacks-corregidos.zip`

SHA-256 del parche: `E32A8B272BA6E80ABEC524C8EC5D14A9ADDD7346BC8AC265B2C18AF0D392CF7D`

SHA-256 del paquete completo: `481A7F8CA54A51FF079ED919BE15C85A52EC155D855D6558AEEEE4EBCD2F5F85`

## Contenido validado

- Minecraft 1.20.1
- Forge 47.4.20
- 258 mods para servidor
- 57 mods exclusivos del cliente excluidos
- Mundo final incluido en la carpeta `world`
- Datapacks de MultiSafío, Dedsafío y compatibilidad incluidos en `world/datapacks`
- Spawn, estructuras, configuraciones, misiones, claims y waypoints incluidos
- Datos personales de las pruebas locales eliminados

## Instalación

1. Detén el servidor y crea una copia de seguridad desde exaroton.
2. Selecciona **Forge 1.20.1 - 47.4.20** como software del servidor.
3. Sustituye los archivos del servidor por el contenido del ZIP, respetando las carpetas.
4. Comprueba que la carpeta del mundo se llame `world`.
5. Inicia el servidor y espera a que la consola indique `Done`.
6. Entra usando el cliente MultiSafío 1.0.12.

### Si ya subiste el paquete anterior

1. Detén el servidor.
2. Sube y combina el contenido de `exaroton-multisafio-1.0.12-datapacks-corregidos.zip` en la raíz del servidor.
3. Comprueba que existan `world/datapacks/multisafio_core` y `world/datapacks/Dedsafio 3 Vanilla 1.18 - 1.20.4 - Club Pala`.
4. Inicia el servidor y ejecuta `datapack list` en la consola. Ambos deben figurar habilitados.

Si exaroton no permite subir todos los mods juntos, usa `MODS_SERVIDOR.txt` como lista exacta para instalarlos y después sube las carpetas `config`, `defaultconfigs`, `kubejs` y el mundo `world`.

## Comprobación rápida

- Aparecer en el spawn preparado.
- Verificar que la zona segura y sus claims estén presentes.
- Abrir las misiones y confirmar que conservan su estructura.
- Probar una ruleta y un anuncio como operador.
- Confirmar que Prefab, las herramientas administrativas y los objetos de casino estén disponibles únicamente como fueron configurados.

El arranque dedicado fue validado localmente con Forge 47.4.20. La librería gráfica `gml` quedó excluida del servidor porque es exclusiva del cliente y provocaba el cierre durante el inicio dedicado.
