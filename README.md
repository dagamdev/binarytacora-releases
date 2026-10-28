# Binarytacora

Bitácora de trading de opciones binarias para Windows, compatible con **IQ Option**, **Exnova**, **Casa Trade** y
**Pocket Option**.

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
4. Si quieres tus operaciones de antes, usa **Configuración › Importar historial** (en Pocket Option solo trae las
   últimas 20 de cada cuenta: es todo lo que da la plataforma).

## Qué hace

- **Registro automático** — cada operación (binaria, turbo o digital) se guarda con su entrada, cierre, resultado y
  payout, con avisos al abrir y cerrar. Funciona con cuentas demo, reales y torneos (los torneos, solo en IQ Option,
  Exnova y Casa Trade: los de Pocket Option no se admiten).
- **Gráfico de cada operación** — guarda las velas de antes y después de la entrada en el momento en que operas, y
  marca la entrada, el cierre y el resultado. Puedes cambiar de temporalidad (manteniendo el rango de tiempo) y ver
  las velas en vivo mientras la operación sigue abierta. Recuerda el zoom y la posición de cada operación.
- **Diario** — al cerrar una operación aparece un registro rápido (sin interrumpirte) para anotar estrategia, patrón,
  confluencias, errores, emociones y notas. Lo que no registres queda pendiente para completarlo después.
- **Estadísticas** — winrate, PnL, expectativa, drawdown, rachas y mapa de calor por horario; también por estrategia y
  por patrón, y de disciplina (si seguiste tu plan, emociones, costo de los errores). Desde cada estadística puedes ir
  a repasar las operaciones en el gráfico.
- **Límites de operación** — arma reglas con pérdida máxima, objetivo de ganancia, monto por entrada, número de
  operaciones, pausa tras una pérdida y límites por resultado (ganadas o perdidas seguidas y en total). Cada regla
  elige sus brokers y si aplica a la cuenta real, a la demo o a ambas. Te avisa en la app y con una notificación de
  Windows; nunca toca tu cuenta.
- **Sesiones** — tus operaciones se agrupan en sesiones; al terminar una (con el botón «Terminar sesión» o tras un
  rato sin operar) ves su resumen: resultado, winrate, rachas, plan seguido, errores, cómo vas en tus límites y notas.
- **Filtros** — por cuenta, broker, activo, resultado, torneo y fechas; se recuerdan al cerrar la app. La lista se
  puede ocultar para dar más espacio al gráfico.
- **Exportar** — tus datos en CSV o JSON y respaldo completo de la base.
- **Tema oscuro y claro**, o el del sistema.

> **Pocket Option:** la plataforma solo guarda tus últimas 20 operaciones cerradas de cada cuenta, y por alrededor de
> una semana. Lo que hagas con la app cerrada se recupera al abrirla solo si sigue entre esas: ten la app abierta
> mientras operas. Sus **torneos no se admiten**: no inicies sesión en la app desde un torneo, porque se guardaría
> como tu cuenta real.

## Planes

- **Gratuito** — todo lo anterior, con velas de 1 minuto en adelante y límites por día, e importa el historial de
  los últimos 7 días. Los textos del diario tienen límite de caracteres (análisis 2 000, lección 1 000, notas de
  sesión 3 000).
- **Pro** — además:
  - guarda velas de 5 a 30 segundos;
  - importa todo el historial que tenga el broker;
  - límites por sesión, que se reinician al terminar cada sesión;
  - textos del diario sin límite de caracteres;
  - muestra el gráfico de cada operación con los colores de velas, indicadores (EMA, SMA, Bollinger, Alligator,
    Parabolic SAR, Fractales) y dibujos que tenías en la plataforma del broker.

  Para conseguirlo escríbeme por Telegram a [@dagamdev](https://t.me/dagamdev).

## Privacidad

Tus operaciones, velas, diario, sesiones y estadísticas (y, con el Pro, la copia de los colores, indicadores y dibujos
de tus gráficos) se guardan **solo en tu PC** y no se suben a ningún servidor. La sesión
del broker se guarda en el Administrador de credenciales de Windows, y la app nunca ve tu contraseña. Para saber tu
plan solo se envía tu ID de usuario del broker y la versión de la app. Sin publicidad ni analítica.

## Aviso

Binarytacora es un proyecto independiente: **no está afiliado, respaldado ni patrocinado** por Exnova, IQ Option,
Casa Trade ni Pocket Option. Sus nombres y marcas pertenecen a sus dueños y aquí solo indican con qué brokers funciona la app.

La app se conecta al broker con tu sesión mediante una conexión propia de **solo lectura**, aparte de la plataforma
que tienes abierta. Los brokers no aprueban ni respaldan herramientas de terceros: úsala bajo tu propio criterio.

---

Este repositorio solo contiene los instaladores. Dudas o problemas: [@dagamdev](https://t.me/dagamdev) en Telegram.
