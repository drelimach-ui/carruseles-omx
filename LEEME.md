# Publicador automático · Oriéntate MX

72 carruseles (2026-10-28 → 2027-01-19). Lunes a viernes 19:00 y sábados 09:00 (CDMX). Domingo sin post.
El programa corre dos veces al día (09:00 y 19:00) y publica el post del día cuya hora ya llegó y que aún no se ha publicado.

- `posts/semana-XX/<fecha>_<dia>_<institucion>_<materia>/`: 4 JPG 1080×1350 + caption.txt.
- `calendario.json`: fecha, hora, carpeta y caption de cada post.
- Secretos (Settings → Secrets and variables → Actions): `IG_TOKEN` e `IG_USER_ID` de OMX.
- Prueba: Actions → "Publicar carrusel OMX del día" → Run workflow (orden = 1, dry_run = 1).
- Token: dura 60 días; renovarlo en Meta y actualizar `IG_TOKEN`.
