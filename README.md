# Dashop Updates

Repositorio público de releases para actualizaciones automáticas con [Sparkle](https://sparkle-project.org/).

- **Appcast:** `appcast.xml` (feed leído por Dashop)
- **Binarios:** GitHub Releases (`.dmg` notarizados)

Feed URL configurada en Dashop:

```
https://raw.githubusercontent.com/hiyuno/Dashop-updates/main/appcast.xml
```

## Publicar una versión

Desde el repo principal `Dashop`:

```bash
NOTARY_PROFILE=YourProfile ./scripts/release.sh 1.0.1
```

Ver `scripts/release.sh` y `scripts/sparkle-generate-keys.sh` en el repo de la app.
