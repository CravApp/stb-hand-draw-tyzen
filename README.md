# stb-hand-draw-tyzen

Puerto a Samsung Tizen TV de [stb-hand-draw](https://github.com/CravApp/stb-hand-draw): dibujar en el aire con la yema del índice, delante de una webcam USB, sobre el televisor.

Todavía no hay aplicación. El contrato está en [docs/SRS.md](docs/SRS.md): el núcleo portable (dibujo, suavizado, ajustes y la línea `HandDrawPerf`), la capa web Tizen, los privilegios de `config.xml`, el empaquetado `.wgt`, el ensayo de `getUserMedia` y WASM, los hitos y la trazabilidad hacia la app Android.

Equipo de referencia: Samsung LH75BEFHLGGXPE, Tizen 9.0. La instalación de laboratorio es un `.wgt` firmado con el perfil de certificado `203` e instalado por `sdb` en `10.50.123.97:26101`. El detalle y la plantilla para otros equipos están en la SRS.
