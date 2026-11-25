# Free Music & Free Video

Repositorio oficial de lanzamientos y actualizaciones automáticas OTA para **Free Music** y **Free Video**.

## Descargar APKs (Android)

- **Free Music**: [Descargar última versión](https://github.com/B4N4NO/free-media/releases/latest)
- **Free Video**: [Descargar última versión](https://github.com/B4N4NO/free-media/releases/latest)

Una vez instaladas, ambas apps buscan actualizaciones automáticamente al abrirse y te permiten descargar e instalar nuevas versiones con un toque desde dentro de la app.

## Cómo publicar una actualización

Desde PowerShell en esta carpeta (`c:\Users\fbani\claude code\free-media`):

```powershell
# Actualizar solo Free Music
.\publish-update.ps1 -App music -Version 1.0.1 -Notes "Mejoras en reproducción"

# Actualizar solo Free Video
.\publish-update.ps1 -App video -Version 1.0.1 -Notes "Mejoras en reproductor"

# Actualizar ambas apps a la vez
.\publish-update.ps1 -App both -Version 1.0.1 -Notes "Actualización general"
```

Agregá `-Install` si además querés instalar el APK en tu celular conectado por USB, o `-Desktop` para compilar e instalar también en tu PC.
