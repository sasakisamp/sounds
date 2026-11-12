# Audio de invocaciones aéreas

## Summon_TakaCall.mp3 (ID 400)

Archivo entregado por el usuario para reproducir al invocar Taka. Copia sin modificaciones; no se atribuye una licencia externa que no se haya proporcionado.

## Summon_BirdWingFlaps.ogg (ID 401)

- Obra: Large Wings Flap.
- Autor: AntumDeluge.
- Fuente: https://opengameart.org/content/large-wings-flap
- Descarga: https://opengameart.org/sites/default/files/wings_flap_large.zip
- Licencia declarada por el autor y el README del archivo: Creative Commons Zero (CC0).
- Licencia: https://creativecommons.org/publicdomain/zero/1.0/
- Origen indicado por el autor: fast simple chop 5 de dave.des, https://freesound.org/s/127197/.
- Archivo original: wings_flap_large.ogg, 44100 Hz mono, duración aproximada 2,631 s, tres aleteos.
- Cambio: renombrado a Summon_BirdWingFlaps.ogg (antes AerialWings.ogg); audio sin recortes ni conversión.

El paquete existente SG_Sounds lo distribuye por el sistema de audio integrado. El archivo de créditos no se registra como un sonido.

## Sonidos de Akamaru (IDs 402 y 403)

- Colección: Akamaru, Naruto: Clash of Ninja 2, Characters (English), GameCube; atribución del sitio de origen.
- Tablero: https://www.101soundboards.com/boards/40295-akamaru-naruto-clash-of-ninja-2-characters-english-gamecube
- ID 402, `Summon_AkamaruBark.mp3`: tecla 9 del tablero, clip 1435251 (Sound 8 channels 1 frequency). Recortado desde 0,215 s para retirar el sonido previo al ladrido; entrada suavizada durante 4 ms. Duración final: 0,464172 s.
- Fuente: https://www.101soundboards.com/sounds/1435251-sound-8-channels-1-frequency
- ID 403, `Summon_AkamaruDowned.mp3`: tecla W, clip 1435258. Recortado desde 1,600 s para conservar solo el sonido final; entrada suavizada durante 4 ms. Duración final: 0,542041 s.
- Fuente: https://www.101soundboards.com/sounds/1435258-aa
- Selección y recorte aprobados por el usuario. No se atribuye una licencia libre no proporcionada por el origen.
- Originales y trazabilidad: `miscellaneous/ninken-sounds-20261015/sources.json`.

## Akamaru adulto (IDs 404 y 405)

- Archivos elegidos y proporcionados por el usuario: `ladrido_04.mp3` y `quejido_dano_02.mp3`.
- Procedencia aportada: Naruto to Boruto: Shinobi Striker, banco `SD_Default.bnk`, eventos `Char_SUMNJ01`. El registro de extracción indica que la atribución del personaje original a Akamaru no está confirmada. Se usan como voz del Ninken adulto por elección del usuario; no se atribuye una licencia libre no proporcionada.
- ID 404: `Summon_AkamaruAdultBark.mp3`, ladrido de 0,374 segundos.
- ID 405: `Summon_AkamaruAdultDowned.mp3`, quejido de 1,322 segundos al quedar inconsciente.
- MP3 mono a 32000 Hz, copiados sin recorte, conversión ni cambio de volumen.
- Selección por skin adulta 20569; los IDs 402 y 403 conservan sus archivos anteriores.
- Trazabilidad: `miscellaneous/ninken-adult-sounds-20261016/sources.json`.


## Shintenshin: activación, impacto y finalización (IDs 406 a 408)

- Selección confirmada por el usuario: activación de la muestra del anime; impacto y finalización de Shinobi Striker.
- ID 406, Jutsu_ShintenshinActivate.mp3: pieza de activación publicada por ふらっとサウンドchannel, https://www.youtube.com/watch?v=h5VmJnKKQhg. Conserva los bytes de la muestra aprobada, estéreo a 48000 Hz y ganancia previa 0,8; no incluye preparación. El canal es la fuente publicada, sin afirmar que sea un stem oficial ni atribuir una licencia libre.
- ID 407, Jutsu_ShintenshinHit.mp3: Shinobi Striker, SD_Default.bnk, evento Play_Ninjutsu_D29NJ1_Hit, media 197523241; mono a 32000 Hz.
- ID 408, Jutsu_ShintenshinEnd.mp3: Shinobi Striker, SD_Default.bnk, evento Play_Ninjutsu_D29NJ1_End, media 935308569; mono a 32000 Hz.
- Los tres MP3 se copian sin procesamiento adicional. Fuentes, hashes y elección: miscellaneous/shintenshin-selected-audio-20261017/selection.json. Extracción SS: miscellaneous/shintenshin-sounds-20261017/procedencia.json. Muestra del anime: miscellaneous/shintenshin-anime-sound-20261017/muestra-procedencia.json.


## Bijuus: ejecuciones y transformaciones completas (447–485)

Grabaciones extraídas de los bancos originales locales de Naruto Shippuden Ultimate Ninja Storm 4 (Bandai Namco / CyberConnect2). Preparación con sus parámetros de tono, volumen, capas y tiempos de evento; variante aleatoria fija para permitir una sola reproducción por subhit. No se atribuye licencia libre. Los originales y las pruebas de procedencia quedan del lado del servidor. Véase ../../docs/cliente/bijuu-audio.md.
