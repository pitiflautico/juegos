# El Juego del Teléfono Numérico

## Resumen
- Tipo: Comunicación / Precisión Numérica
- Jugadores: 5-8
- Duración: 15-20 minutos
- Intensidad: Media
- Temática: Números transmitidos en cadena
- **Mecánica de interconexión:** Los números se transmiten en cadena donde cada jugador recibe un número, debe realizar una operación matemática y pasar el resultado al siguiente. El Iniciador conoce el número original. El Receptor Final debe deducir cuál era el número inicial. Los Alteradores cambian operaciones para desviar el resultado. La información numérica se transforma en cada paso.

## Material
- Móviles con: calculadora, notas privadas, mensajería
- Objetos necesarios: Ninguno

## Roles
- **Iniciador Numérico**
  - Función: Elegir el número inicial y primera operación
  - Objetivo: Que el número final permita deducir el inicial
  - Información que posee: El número original (ej: 42)
  - Información que oculta: El número original hasta el final
  - Cómo se conecta con los otros roles: Inicia la cadena de transformaciones
  - Acciones especiales: Puede dar 1 pista sobre el número original al final

- **Transmisores (mayoría)**
  - Función: Recibir número, aplicar operación asignada, pasar resultado
  - Objetivo: Que la cadena llegue correctamente al final
  - Información que posee: Solo el número que reciben y la operación que deben aplicar
  - Información que oculta: El resultado hasta pasarlo al siguiente
  - Cómo se conecta con los otros roles: Son eslabones en la transformación numérica
  - Acciones especiales: Pueden verificar su cálculo 1 vez

- **Alteradores (2)**
  - Función: Aplicar operaciones incorrectas para desviar el resultado
  - Objetivo: Que el número final sea muy diferente del correcto
  - Información que posee: Saben quién es el otro Alterador
  - Información que oculta: Qué operación incorrecta aplicaron
  - Cómo se conecta con los otros roles: Fingen calcular correctamente pero alteran
  - Acciones especiales: Pueden cambiar su operación 2 veces durante la cadena

- **Receptor Final**
  - Función: Recibir el número final y deducir el número original
  - Objetivo: Adivinar el número inicial con margen de ±5
  - Información que posee: El número final y qué operaciones se supone que se aplicaron
  - Información que oculta: Su deducción hasta declararla
  - Cómo se conecta con los otros roles: Depende de toda la cadena anterior
  - Acciones especiales: Puede solicitar revisión de cálculos de 1 jugador

## Cómo se interconectan los jugadores
- **Quién sabe la identidad de quién:** Los Alteradores se conocen entre sí. El Iniciador y Receptor son públicos.
- **Quién puede mentir:** Los Alteradores sobre sus cálculos.
- **Quién debe cooperar:** Iniciador, Transmisores y Receptor cooperan para cadena correcta.
- **Quién tiene misiones secretas:** Los Alteradores desvían resultados.
- **Cómo se transmite la información:** Números se pasan por mensaje privado. Las operaciones son conocidas públicamente.
- **Qué rol bloquea o habilita a otros:** Los Alteradores bloquean precisión. El Receptor puede detectar errores pidiendo revisión.
- **Qué consecuencias tiene la interacción:** Alteraciones acumulan error. Si el Receptor deduce correctamente a pesar de alteraciones, gana el equipo.

## Cómo se usa el móvil en el juego
- **Calculadora:** Para realizar operaciones.
- **Mensajería:** Para pasar números al siguiente en la cadena.
- **Notas:** Para registrar qué operación aplicaron y qué resultado obtuvieron.

## Cómo se juega
1. El Iniciador elige un número secreto (ej: 42).
2. Se establece la cadena de jugadores (orden fijo).
3. Cada jugador en la cadena recibe una operación asignada (ej: "multiplica por 2", "suma 10", "divide por 3", "resta 5").
4. El Iniciador aplica su operación al número secreto y pasa el resultado al siguiente.
5. Cada jugador recibe el número del anterior, aplica su operación, pasa el resultado.
6. Los Alteradores aplican operaciones diferentes (ej: si les tocó "×2", hacen "×3").
7. El número va transformándose en la cadena.
8. El Receptor Final recibe el número final.
9. Conociendo qué operaciones se supone que se aplicaron, intenta deducir el número original.
10. Si adivina con margen de ±5, el equipo gana.

## Fases
### Preparación
- Asignar roles secretamente.
- Los Alteradores se identifican entre sí.
- El Iniciador elige el número secreto (entre 1-100).
- Se asignan operaciones a cada jugador en la cadena:
  - Ejemplo con 6 jugadores:
    - Iniciador: ×2
    - Jugador 2: +15
    - Jugador 3: ÷3
    - Jugador 4: -8
    - Jugador 5: ×4
    - Receptor: recibe resultado final
- Las operaciones son públicas (todos saben quién debe hacer qué).

### Acción principal
- **Transmisión de números:**
  1. Iniciador calcula: número secreto + su operación
     - Ej: 42 × 2 = 84
  2. Envía "84" al siguiente jugador por mensaje privado
  3. Jugador 2 recibe 84, aplica su operación: 84 + 15 = 99
  4. Envía "99" al siguiente
  5. Continúa la cadena
  6. Los Alteradores aplican operaciones incorrectas:
     - Si les tocó +15, hacen +20 (alteración de +5)
     - Si les tocó ×4, hacen ×5 (alteración)
  7. El número llega al Receptor Final transformado

- **Deducción:**
  - El Receptor Final recibe el número final (ej: 485)
  - Conoce la cadena de operaciones supuestas
  - Debe hacer ingeniería inversa:
    - Si la última operación fue ×4, entonces antes del último paso era: 485÷4 = 121.25
    - Si antes fue -8, entonces antes de eso era: 121.25+8 = 129.25
    - etc.
  - Intenta deducir el número original

### Conflicto / Sabotaje / Votación
- El Receptor puede solicitar revisión de cálculos de 1 jugador sospechoso.
- Ese jugador debe mostrar: qué número recibió, qué operación aplicó, qué resultado obtuvo.
- Si hay error (Alterador), se identifica.
- Si se identifica a un Alterador: se pueden recalcular los números desde ese punto.
- Si acusan a un Transmisor honesto: pierden la oportunidad de revisión.

### Final
- El Receptor declara: "Creo que el número original era [X]".
- El Iniciador revela el número original real.
- **Victoria del Equipo (Iniciador, Transmisores, Receptor):** El Receptor adivina con margen de ±5.
- **Victoria de Alteradores:** El número deducido está fuera del margen (error de más de 5).

## Cómo se gana
- **Equipo Honesto:** El Receptor deduce el número original con margen de error de ±5.
- **Alteradores:** El error final es mayor a 5 puntos.

## Variantes
- **Para pocos jugadores (5):** 1 Alterador, operaciones más simples, margen de ±10.
- **Para muchos (10+):** 3 Alteradores, cadena larga, operaciones complejas.
- **Modo difícil:** Operaciones con decimales y raíces cuadradas.
- **Modo rápido:** Operaciones mentales simples, sin calculadora.
- **Modo múltiple:** 2 números en paralelo transformándose simultáneamente.
- **Modo cooperativo puro:** Sin Alteradores, operaciones muy complejas, margen de ±2.
