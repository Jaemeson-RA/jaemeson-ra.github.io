# jaemeson-ra.github.io

Raíz del dominio de GitHub Pages. Solo sirve para:

- `.well-known/assetlinks.json`: vincula la app de Android (`io.github.jaemesonra.plancomidas`) con el sitio, para que se abra a pantalla completa sin barra de direcciones. Cuando la app esté en Google Play hay que sumar la huella SHA-256 de la clave de firma de Google (Play Console → Integridad de la app).
- `index.html`: redirige a https://jaemeson-ra.github.io/plan-comidas-bsas/

`.nojekyll` hace falta para que GitHub Pages publique la carpeta `.well-known`.
