# gloryThursday-extraBalls

Bolas extra del [Jueves de Gloria](https://sanhuaaan.github.io/gloryThursday/).

- `balls.json`: bolas extra del próximo sorteo, `{balls: {cocina: n}, stores: {slug: n}, mTo}`. Solo valen mientras el último sorteo registrado sea `mTo`.
- `key.json`: token de GitHub cifrado con la combinación de la trastienda (PBKDF2 + AES-GCM).

Este repo existe aparte para que el token de la [trastienda](https://sanhuaaan.github.io/gloryThursday/trastienda.html) solo tenga acceso a él: si alguien lo consiguiera, solo podría cambiar las bolas extra, no el bombo. Todo lo escribe la trastienda; no hace falta tocarlo a mano.
