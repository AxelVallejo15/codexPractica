# Práctica Temática: **Propuesta de Mini Proyecto Documentado**

## 1) Título de la práctica
**Diseño de Práctica Pequeña en Terminal (ARM64, C, Python o Bash)**

> Ejemplos de títulos que puedes usar para tu proyecto:
> - “Mini Toolkit en ARM64”
> - “Asistente de Estudio en Terminal”
> - “Reporteador de Información del Sistema”
> - “Organizador de Archivos”
> - “Juego de Aprendizaje en Línea de Comandos”

---

## 2) Descripción general
En esta actividad vas a **diseñar y documentar** una propuesta de proyecto pequeño para terminal. El objetivo es que primero pienses la idea, la justifiques técnicamente y planees su estructura antes de programar demasiado.

Tu propuesta debe elegir **un lenguaje principal**:
- ARM64 Assembly
- C
- Python
- Bash

> ⚠️ **Nota importante sobre ARM64 Assembly:** úsalo solo para programas **muy pequeños** (por ejemplo: operaciones básicas, lectura simple de argumentos, utilerías mínimas de consola), porque el enfoque de esta actividad no es construir algo grande, sino documentar una solución viable y bien planeada.

### Enfoque principal de la práctica
1. Documentación clara.
2. Planeación realista del alcance.
3. Estructura ordenada del repositorio.
4. Explicación del caso de uso.
5. Plan básico de pruebas.

### Restricciones de alcance (obligatorias)
Para mantener la práctica factible con herramientas gratuitas y límites de uso de IA:
- El proyecto debe ser **pequeño**.
- Evita frameworks pesados.
- No uses APIs pagadas.
- No uses bases de datos.
- No uses servicios en la nube.
- No uses contenedores.
- Evita dependencias complejas o difíciles de instalar.

---

## 3) Entregables del estudiante
Tu repositorio debe incluir **como mínimo** estos archivos:
- `README.md`
- `docs/propuesta.md`
- `docs/caso_de_uso.md`
- `docs/estructura_repositorio.md`
- `docs/plan_de_pruebas.md`

Archivos/carpetas **opcionales**:
- `src/`
- `scripts/`
- `tests/`

> Puedes incluir código mínimo para demostrar viabilidad, pero la calificación de esta actividad se centra en la calidad de la documentación y la planeación.

---

## 4) Estructura recomendada del repositorio
Usa como referencia esta estructura mínima:

```text
nombre-del-proyecto/
├── README.md
├── docs/
│   ├── propuesta.md
│   ├── caso_de_uso.md
│   ├── estructura_repositorio.md
│   └── plan_de_pruebas.md
├── src/
│   └── main.<ext>
├── scripts/
│   └── run.sh
└── tests/
    └── test_plan.md
```

---

## 5) Contenido esperado por archivo

### `README.md`
Incluye:
- Nombre del proyecto.
- Problema que resuelve (1 párrafo).
- Lenguaje principal elegido y justificación breve.
- Instrucciones mínimas para ejecutar (si ya hay prototipo).
- Estado del proyecto: “propuesta” o “prototipo inicial”.

### `docs/propuesta.md`
Incluye al menos:
1. **Objetivo general** (qué quieres lograr).
2. **Alcance** (qué sí incluye y qué no incluye).
3. **Usuario objetivo** (quién lo usaría).
4. **Requisitos funcionales mínimos** (3 a 5 puntos).
5. **Requisitos no funcionales básicos** (simplicidad, portabilidad, facilidad de uso, etc.).
6. **Cronograma breve** (por fases pequeñas).

### `docs/caso_de_uso.md`
Incluye:
- Contexto del problema.
- Escenario principal de uso (paso a paso).
- Entrada esperada del usuario.
- Salida esperada del sistema.
- Un ejemplo concreto (con datos simples).

### `docs/estructura_repositorio.md`
Incluye:
- Árbol de carpetas y archivos propuestos.
- Responsabilidad de cada carpeta.
- Convención de nombres (archivos, scripts, módulos).
- Estrategia para mantener el proyecto pequeño y ordenado.

### `docs/plan_de_pruebas.md`
Incluye:
- Objetivo de pruebas.
- Casos de prueba funcionales mínimos (al menos 5).
- Casos de error o borde (al menos 2).
- Criterios de aceptación/rechazo.
- Evidencia esperada (capturas, logs o salidas de terminal).

---

## 6) Criterios de evaluación sugeridos (rúbrica)

| Criterio | Excelente (100) | Suficiente (80) | Insuficiente (60 o menos) |
|---|---|---|---|
| Claridad de la propuesta | Objetivo, alcance y usuario muy bien definidos | Hay objetivo y alcance, pero con ambigüedades | No queda claro qué se quiere construir |
| Calidad del caso de uso | Flujo completo, entradas/salidas claras y ejemplo útil | Flujo parcial o ejemplo poco claro | Caso de uso incompleto o confuso |
| Estructura del repositorio | Organización limpia, coherente y mantenible | Estructura aceptable con detalles por mejorar | Estructura desordenada o incompleta |
| Plan de pruebas | Casos suficientes, relevantes y medibles | Casos básicos pero limitados | Pruebas mínimas ausentes o irrelevantes |
| Viabilidad técnica | Proyecto pequeño, realista y alineado al lenguaje | Proyecto parcialmente viable | Proyecto sobredimensionado o inviable |

---

## 7) Recomendaciones por lenguaje

### Si eliges ARM64 Assembly
- Limita el alcance a utilerías mínimas.
- Evita parsing complejo.
- Prioriza demostrar comprensión de registros, llamadas al sistema y flujo básico.

### Si eliges C
- Enfócate en modularidad mínima (`main.c` + 1 o 2 archivos auxiliares).
- Evita librerías externas innecesarias.

### Si eliges Python
- Usa biblioteca estándar.
- Evita frameworks.
- Prioriza scripts claros y ejecutables desde terminal.

### Si eliges Bash
- Define bien entradas/salidas.
- Cuida validaciones básicas y mensajes de error legibles.
- Mantén scripts cortos y comentados.

---

## 8) Entrega final en GitHub Classroom
Sube tu repositorio con la documentación completa. Si agregas código, que sea solo el mínimo para respaldar la viabilidad de la propuesta.

### Checklist de entrega
- [ ] `README.md` completo.
- [ ] `docs/propuesta.md` completo.
- [ ] `docs/caso_de_uso.md` completo.
- [ ] `docs/estructura_repositorio.md` completo.
- [ ] `docs/plan_de_pruebas.md` completo.
- [ ] Estructura del repositorio clara y navegable.
- [ ] Alcance pequeño y realista.
- [ ] Lenguaje principal claramente justificado.

---

## 9) Formato recomendado para nombrar el proyecto
`practica-tematica-<lenguaje>-<tema-corto>`

Ejemplos:
- `practica-tematica-python-organizador`
- `practica-tematica-c-reporte-sistema`
- `practica-tematica-bash-asistente-terminal`
- `practica-tematica-arm64-mini-toolkit`

---

## 10) Mensaje final para el estudiante
Piensa como ingeniera o ingeniero de sistemas: **primero diseña, después implementa**. Una propuesta bien documentada reduce errores, mejora decisiones técnicas y permite construir proyectos pequeños, útiles y mantenibles.
