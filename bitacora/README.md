# Bitácora semanal

Un archivo por semana: `YYYY-WNN.md`.

## Uso
- **Lunes mañana:** abro la bitácora de la semana, rellenó objetivo + bloques planificados.
- **Cada noche (30s):** marco checkboxes del día antes de cerrar el laptop.
- **Viernes (5 min):** completo la revisión semanal.
- **Viernes/sábado:** escribo el draft del post y lo guardo en `posts/`.

## Convención de nombres de semana

Uso ISO week numbering (lunes como primer día de la semana):

| Semana | Fecha inicio | Archivo |
|--------|:------------:|:-------:|
| 17 | 2026-04-20 | `2026-W17.md` |
| 18 | 2026-04-27 | `2026-W18.md` |
| 19 | 2026-05-04 | `2026-W19.md` |

Para calcular rápido: `date` o `python -c "import datetime; print(datetime.date.today().isocalendar())"`.
