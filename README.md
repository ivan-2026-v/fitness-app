# 💪 Coach · Ivan

App personal de entrenamiento + plan de fuerza y masa magra (6 días/semana).

## Contenido

- **[index.html](index.html)** — La app. Un solo archivo, funciona offline, guarda los datos en el navegador (localStorage). Registra pesos/reps, tiempos de metcon y muestra el progreso en gráficos.
- **[rutina.md](rutina.md)** — El plan documentado: diagnóstico, split de 6 días, reglas de progresión y pilares de seguridad.
- **[trainings.md](trainings.md)** — Historial de entrenamientos (registro base del grupo QGDFitness).

## Cómo usar la app

**En la Mac:**
```bash
open index.html
```

**En el teléfono (misma WiFi, para probar):**
```bash
python3 -m http.server 8080
```
Después abrí `http://IP-DE-LA-MAC:8080/index.html` en el celular.

**En el teléfono (offline, para el gym):** abrí la app una vez (por AirDrop o desde una URL hosteada) y usá **Compartir → Agregar a inicio**. Queda como ícono y funciona sin conexión.

## Respaldo de datos

Los registros viven en el navegador del dispositivo. Desde **Ajustes → Exportar respaldo** guardás un JSON. Para restaurar, **Importar respaldo**.

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
