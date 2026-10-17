# Binarytacora

Bitácora de trading de opciones binarias para Windows, compatible con **IQ Option**, **Exnova** y **Casa Trade**.

Conectas tu cuenta y la app registra sola cada operación que haces, guarda las velas de alrededor para que
puedas repasarla después, y te ayuda a llevar un diario y medir tu operativa con estadísticas.

> La app **solo lee** tu cuenta: nunca abre, cierra ni modifica operaciones en el broker.

## Descargar

Descarga el instalador `Binarytacora_<versión>_x64-setup.exe` de la
[última versión](https://github.com/dagamdev/binarytacora-releases/releases/latest) y ejecútalo.

> Windows puede mostrar "Windows protegió su PC" la primera vez: pulsa **Más información → Ejecutar de todas formas**.

La app se actualiza sola: cuando hay una versión nueva te avisa y la instala si lo aceptas.

## Primeros pasos

1. Abre la app y acepta la nota de privacidad.
2. En **Configuración**, elige tu broker e inicia sesión en su página (se abre en una ventana aparte).
3. Opera como siempre en la plataforma del broker: las operaciones aparecen en Binarytacora al abrirse y al cerrarse.
4. Si quieres tus operaciones de antes, usa **Configuración › Importar historial**.

## Qué hace

- **Registro automático** — cada operación (binaria, turbo o digital) se guarda con su entrada, cierre, resultado y
  payout, con avisos al abrir y cerrar. Funciona con cuentas demo, reales y torneos.
- **Gráfico de cada operación** — guarda las velas de antes y después de la entrada en el momento en que operas, y
  marca la entrada, el cierre y el resultado. Puedes cambiar de temporalidad y ver las velas en vivo mientras la
  operación sigue abierta.
- **Diario** — al cerrar una operación aparece un registro rápido (sin interrumpirte) para anotar estrategia, patrón,
  confluencias, errores, emociones y notas. Lo que no registres queda pendiente para completarlo después.
- **Estadísticas** — winrate, PnL, expectativa, drawdown, rachas y mapa de calor por horario; también por estrategia y
  por patrón, y de disciplina (si seguiste tu plan, emociones, costo de los errores). Desde cada estadística puedes ir
  a repasar las operaciones en el gráfico.
- **Filtros y sesiones** — por cuenta, broker, activo, resultado, torneo y fechas; las sesiones de trading se agrupan
  solas y puedes añadirles notas.
- **Exportar** — tus datos en CSV o JSON y respaldo completo de la base.
- **Tema oscuro y claro**, o el del sistema.

## Planes

- **Gratuito** — todo lo anterior, con velas de 1 minuto en adelante.
- **Pro** — además guarda velas de 5 a 30 segundos. Para conseguirlo escríbeme por Telegram a
  [@dagamdev](https://t.me/dagamdev).

## Privacidad

Tus operaciones, velas, diario y estadísticas se guardan **solo en tu PC** y no se suben a ningún servidor. La sesión
del broker se guarda en el Administrador de credenciales de Windows, y la app nunca ve tu contraseña. Para saber tu
plan solo se envía tu ID de usuario del broker y la versión de la app. Sin publicidad ni analítica.

---

Este repositorio solo contiene los instaladores. Dudas o problemas: [@dagamdev](https://t.me/dagamdev) en Telegram.
