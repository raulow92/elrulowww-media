# elrulowww-media

Almacenamiento temporal de videos para publicar en TikTok, Instagram Reels y YouTube Shorts vía Buffer.

Cada video se sube como *release*. El release se borra automáticamente:
- inmediatamente después de publicarse (lo hace el script local), o
- por el workflow `cleanup` (diario), 48 h después de su `publish_at`, o 7 días después de creado si no tiene fecha.
