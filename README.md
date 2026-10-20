# Veyra — descargas

Instaladores y actualizaciones de **Veyra** (antes Interframe Rec), el grabador de partidas hecho por CodigoF sobre la base de [Segra](https://github.com/Segergren/Segra) (GPL-2.0). Funciona 100 % en tu PC: no pide cuenta ni inicio de sesión.

## Instalar en una PC nueva

1. Entrá a [Releases](../../releases/latest) y bajá `Veyra-Instalador.exe`.
2. Abrilo y seguí el asistente: aceptás los términos de uso, elegís la carpeta (o dejás la de siempre) y si querés un acceso directo en el escritorio. No pide permisos de administrador y trae todo lo necesario: .NET, OBS y la interfaz. Si a la PC le faltan WebView2 o Visual C++ 2015-2022, los instala también.
3. Windows puede mostrar «Windows protegió su PC» porque el instalador no está firmado con un certificado comercial: tocá **Más información → Ejecutar de todas formas**.

Requisitos: Windows 10 u 11 de 64 bits.

`InterframeRec-win-Setup.exe` sigue disponible: instala directo en la carpeta de siempre, sin asistente.

## Si ya tenías Interframe Rec

No hace falta hacer nada: la app se actualiza sola a Veyra. Tus grabaciones, clips y ajustes quedan donde estaban, y los accesos directos pasan a llamarse Veyra.

## Actualizaciones

La app instalada revisa este repositorio al abrirse y cada 4 horas, y se actualiza sola. Cada paquete se verifica con su hash SHA-256 antes de aplicarse, y solo se aceptan paquetes de Veyra.

## Código fuente

Veyra es una obra derivada de Segra y se distribuye bajo la GPL-2.0. Si querés el código fuente completo de cualquier versión, pedilo abriendo una [consulta](../../issues).
