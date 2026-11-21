# Ciudad Volumen 🏗️📐

RPG educativo de navegador para **Razonamiento Matemático III** (Preparatoria Xochicalco, Parcial 3).
El estudiante es aprendiz de constructor: reconstruye Ciudad Volumen calculando **volúmenes** y abre el Barrio de los Patrones descifrando **sucesiones**.

**Jugar:** https://thuerta2398.github.io/calculo-volumenes-razo/

## Misiones (≈ 40 min)

| # | Misión | Tema | Retos | Tiempo |
|---|---|---|---|---|
| 1 | La bodega | Prisma rectangular, prisma triangular, conversión cm → m | 3 | ~5 min |
| 2 | La torre de agua | Cilindro (radio y diámetro), semicilindro | 3 | ~5 min |
| 3 | El observatorio | Pirámide, esfera, semiesfera | 3 | ~5 min |
| 4 | El taller | Compuestas por suma: casa (prisma + techo), silo (cilindro + semiesfera), techo con Pitágoras | 3 | ~6 min |
| 5 | La pieza hueca | Compuestas por resta: bloque perforado, escalón (con verificación cara × profundidad), tubo | 3 | ~5 min |
| 6 | La puerta de los símbolos | Secuencias lógicas visuales (lados, giros, cantidades, color) | 3 | ~4 min |
| 7 | El puente aritmético | Término siguiente, término general aₙ = a₁ + (n − 1)·d, posición de un término | 3 | ~4 min |
| 8 | La escalera final | Geométricas aₙ = a₁·rⁿ⁻¹, suma Sₙ y notación Σ | 4 | ~5 min |

Las misiones se desbloquean en orden. Cada NPC da una mini lección con las fórmulas antes del reto. Los valores se generan al azar, así que cada alumno ve números distintos.

## Cómo funciona

- **Retos**: cada respuesta correcta quita un corazón al rival; cada error resta energía y muestra la **solución paso a paso**. Si la energía llega a 0, se repite la misión.
- **Pistas** (2 por reto): la 1.ª muestra la fórmula y la 2.ª la fórmula con los valores sustituidos.
- **Calculadora común de botones** (botón 🧮): dígitos, + − × ÷, paréntesis, π, x², x³, xʸ, √ e =. Se escribe como en una calculadora normal, por ejemplo `π × 3 x² × 8 =`, y el botón **Usar el resultado como mi respuesta** pasa el número al campo de respuesta. En computadora también funciona con el teclado.
- Tolerancia: ±0.6 % en volúmenes (se acepta π ≈ 3.14 o 3.1416); valores exactos en sucesiones.
- **Progreso guardado** en el navegador (botones Continuar / Reiniciar) y lista de misiones "X de 8".
- Al terminar aparece un **certificado** con nombre, aciertos, precisión, pistas y tiempo para enviar como captura.

## Computadora, celular y tablet

- Computadora: flechas / WASD y Espacio / Enter.
- Celular o tablet: cruceta y botón **A**, teclado numérico propio (con π, ², ³ y √ en la calculadora) y opciones con figuras para las secuencias lógicas.

## Ajustes para docentes

Al inicio del `<script>` en `index.html`: `HP_MAX` (energía) y `DANO` (energía que se pierde por error). Los textos de las lecciones están en `TXT.lessons`, y el orden de los retos de cada misión en `GEN`.

Todo el juego es un solo archivo (`index.html`) sin dependencias.
