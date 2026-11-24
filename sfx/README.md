# Efectos de sonido

Coloca aquí los archivos `.mp3`, `.ogg` o `.wav`.

Después configúralos en `music/registry.json` dentro de `"sfx"`:

```json
"sfx": {
  "mi_sfx": {
    "file": "puerta.mp3",
    "folder": "sfx",
    "volume": 0.7,
    "loop": true
  }
}
```

Luego usa `"sfx": "mi_sfx"` en una opción o
`"sfx_on_enter": "mi_sfx"` al entrar en una escena.
