# Clover Desktop · versiones

Aquí se publican los instaladores de **Clover Desktop**, la caja de Clover, y el
`latest.json` que la app instalada lee para actualizarse sola. El código está en un repo
privado; este repo solo guarda versiones.

Las versiones las publica automáticamente GitHub Actions del repo `clover-desktop` al
etiquetar una versión (`vX.Y.Z`). **No subas archivos a mano.**

## Instalar en una caja nueva

Baja el instalador de la [última versión](../../releases/latest):

| Sistema | Archivo |
|---|---|
| Windows | `clover-desktop_X.Y.Z_x64-setup.exe` |
| macOS (Apple Silicon: M1, M2…) | `clover-desktop_X.Y.Z_aarch64.dmg` |
| macOS (Intel) | `clover-desktop_X.Y.Z_x64.dmg` |

- **Windows:** si aparece "Windows protegió su PC", elige *Más información → Ejecutar de
  todas formas*.
- **macOS:** la primera vez, clic derecho sobre Clover → *Abrir* → *Abrir*.

Después, la app avisa cuando hay una versión nueva ("Hay una versión nueva · Actualizar").

## Seguridad

Cada versión está firmada. La app solo instala actualizaciones firmadas con la llave de
Clover, así que un archivo cambiado o falso no se instala.
