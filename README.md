# 💪 Coach · Ivan

App personal de entrenamiento + plan de fuerza y masa magra (6 días/semana).

**App en vivo:** https://ivan-2026-v.github.io/fitness-app/

## Contenido

- **[index.html](index.html)** — La app. Un solo archivo, funciona offline, guarda los datos en el navegador (localStorage).
- **[rutina.md](rutina.md)** — El plan documentado: diagnóstico, split de 6 días, reglas de progresión y pilares de seguridad.
- **[trainings.md](trainings.md)** — Historial de entrenamientos (registro base del grupo QGDFitness).

## Funciones de la app

- **Registro por serie** (peso × reps) con el **detalle serie por serie de la última vez** para saber qué superar.
- **Metcons** con resultado + RPE; **sensación y notas** por sesión.
- **"👁 Ver técnica"**: fotos de cada ejercicio y de cada movimiento del metcon.
- **Volumen / tonelaje** (Σ peso × reps): en vivo, en el historial y como gráfico de evolución en Progreso.
- **Autoguardado** continuo + **una sesión por día que se sobrescribe** (no duplica) + **auto-cierre a las 2 h** sin cambios.
- **Progreso** (evolución por ejercicio + volumen) e **Historial** (diario por fecha).
- **Respaldo**: exportar/importar JSON desde Ajustes.

## Cómo usar la app

**En el teléfono (recomendado):** abrí la URL de arriba y usá **Compartir → Agregar a inicio**. Queda como ícono y funciona offline.

**En la Mac (local):**
```bash
open index.html
```

**En el teléfono por WiFi local (para probar sin hosting):**
```bash
python3 -m http.server 8080
```
Después abrí `http://IP-DE-LA-MAC:8080/index.html` en el celular.

## Datos y respaldo

Los registros viven en el navegador del dispositivo (localStorage), son privados y no se suben a ningún lado. Desde **Ajustes → Exportar respaldo** guardás un JSON; para restaurar, **Importar respaldo**.

## Desarrollo

Editar los archivos y publicar los cambios a la app en vivo (GitHub Pages):
```bash
git add -A && git commit -m "..." && git push
```

## Estructura del plan

| Día | Foco | Bloque 1 (Fuerza) |
|-----|------|-------------------|
| 1 · Lun | Sentadilla | Back Squat 5×5 |
| 2 · Mar | Empuje | Bench Press 5×5 |
| 3 · Mié | Tracción | Strict Press 5×5 + Row |
| 4 · Jue | Bisagra | RDL 4×6 (con cuidado) |
| 5 · Vie | Full body | Front Squat 4×6 |
| 6 · Sáb | Zona 2 | Máquinas + movilidad |

Objetivo: **fuerza y masa magra**. Filosofía: constancia > picos, técnica > número.
