# El Círculo Vicioso

## Resumen
- Tipo: Dependencias / Lógica
- Jugadores: 5-8
- Duración: 20-25 minutos
- Intensidad: Media-Alta
- Temática: Dependencias cíclicas que deben resolverse
- **Mecánica de interconexión:** Cada jugador tiene una tarea que depende de que otro jugador complete la suya primero. Se crea un círculo de dependencias (A necesita que B termine, B necesita que C termine, C necesita que A termine). El Coordinador debe encontrar el punto de ruptura. Los Saboteadores crean dependencias falsas adicionales. La información de quién depende de quién crea un grafo cíclico que debe resolverse.

## Material
- Móviles con: notas, temporizador, app de diagramas (opcional)
- Objetos necesarios: 8 tarjetas de tareas, cuerda o hilo para visualizar dependencias

## Roles
- **Coordinador**
  - Función: Mapear dependencias y encontrar el orden correcto de ejecución
  - Objetivo: Que se completen 6 tareas rompiendo el círculo vicioso
  - Información que posee: Puede preguntar a cada jugador de quién depende
  - Información que oculta: Su estrategia de resolución
  - Cómo se conecta con los otros roles: Debe entender todas las dependencias
  - Acciones especiales: Puede declarar que 1 tarea se ejecute "en paralelo" ignorando dependencia (1 vez)

- **Ejecutores (mayoría)**
  - Función: Completar su tarea cuando sus dependencias estén satisfechas
  - Objetivo: Completar su tarea y ayudar a romper el círculo
  - Información que posee: Saben de quién depende su tarea
  - Información que oculta: Pueden ocultar sus dependencias inicialmente
  - Cómo se conecta con los otros roles: No pueden empezar hasta que otro termine
  - Acciones especiales: Pueden "romper" su dependencia una vez con penalización de tiempo

- **Saboteadores de Dependencias (2)**
  - Función: Crear dependencias falsas o circulares adicionales
  - Objetivo: Que NO se completen 6 tareas en 25 minutos
  - Información que posee: Conocen las dependencias reales, saben quién es el otro Saboteador
  - Información que oculta: Que están añadiendo dependencias falsas
  - Cómo se conecta con los otros roles: Declaran dependencias extras que no son necesarias
  - Acciones especiales: Pueden añadir 2 dependencias falsas cada uno durante el juego

- **El Analista**
  - Función: Visualizar el grafo de dependencias y detectar ciclos
  - Objetivo: Identificar dependencias falsas y sugerir orden de ejecución
  - Información que posee: Puede dibujar el diagrama de dependencias
  - Información que oculta: Sus conclusiones hasta estar seguro
  - Cómo se conecta con los otros roles: Ayuda al Coordinador a entender el sistema
  - Acciones especiales: Puede cuestionar 2 dependencias declaradas (pedir evidencia)

## Cómo se interconectan los jugadores
- **Quién sabe la identidad de quién:** Los Saboteadores se conocen entre sí. Los demás roles son públicos excepto Saboteadores.
- **Quién puede mentir:** Los Saboteadores sobre dependencias adicionales.
- **Quién debe cooperar:** Coordinador, Ejecutores y Analista cooperan para resolver el círculo.
- **Quién tiene misiones secretas:** Los Saboteadores añaden complejidad con dependencias falsas.
- **Cómo se transmite la información:** Cada Ejecutor declara: "No puedo empezar mi tarea hasta que [jugador X] complete la suya". El Coordinador y Analista mapean estas dependencias.
- **Qué rol bloquea o habilita a otros:** Las dependencias bloquean ejecución. El Coordinador habilita resolución. El Analista habilita visualización. Los Saboteadores bloquean con dependencias falsas.
- **Qué consecuencias tiene la interacción:** Círculos viciosos impiden progreso. Romper el círculo correcto permite completar tareas.

## Cómo se usa el móvil en el juego
- **Notas:** Registrar dependencias de cada tarea.
- **Temporizador:** Cada tarea toma 2 minutos en completarse.
- **App de diagramas:** El Analista puede dibujar el grafo de dependencias.

## Cómo se juega
1. Cada Ejecutor recibe una tarea secreta (ej: "Contar hasta 50", "Hacer 10 flexiones").
2. Cada tarea tiene una dependencia (ej: "No puedes empezar hasta que Juan termine su tarea").
3. Las dependencias forman un círculo: A→B→C→D→A (nadie puede empezar).
4. Los jugadores declaran sus dependencias al Coordinador.
5. Los Saboteadores añaden dependencias falsas adicionales.
6. El Coordinador y Analista mapean todas las dependencias.
7. Identifican el círculo vicioso.
8. Deben encontrar la dependencia que se puede romper o declarar "falsa".
9. Una vez roto el círculo, las tareas pueden ejecutarse en orden.
10. Cada tarea toma 2 minutos. Deben completar 6 en 25 minutos.

## Fases
### Preparación
- Asignar roles secretamente.
- Los Saboteadores se identifican entre sí.
- Cada Ejecutor recibe:
  - 1 tarea específica (diferente para cada uno)
  - 1 dependencia: "No puedes empezar hasta que [jugador X] termine"
- Las dependencias se diseñan para formar ciclos inicialmente.
- Ejemplo con 6 jugadores:
  - A depende de B
  - B depende de C
  - C depende de D
  - D depende de E
  - E depende de F
  - F depende de A
  (Círculo completo: nadie puede empezar)

### Acción principal
- **Fase de declaración:**
  1. Cada Ejecutor declara su dependencia
  2. "No puedo empezar hasta que María complete su tarea"
  3. El Coordinador y Analista registran todo
  4. Los Saboteadores añaden dependencias falsas (ej: "También necesito que Pedro termine")
  5. El Analista dibuja el grafo de dependencias
- **Fase de análisis:**
  - El Coordinador y Analista identifican los ciclos
  - Discuten qué dependencias pueden ser falsas
  - El Analista puede cuestionar dependencias sospechosas
  - Deben encontrar el punto de ruptura
- **Fase de ejecución:**
  - Una vez identificado el punto de ruptura, se declara
  - Se rompe una dependencia (se permite que alguien empiece sin esperar)
  - Las tareas se ejecutan en orden de dependencias
  - Cada tarea toma 2 minutos
  - Objetivo: completar 6 tareas en 25 minutos

### Conflicto / Sabotaje / Votación
- Los Saboteadores añaden dependencias falsas que parecen legítimas.
- Ejemplo: Si A depende de B realmente, el Saboteador dice "Yo también dependo de C" (falso).
- El Analista puede cuestionar: "¿Por qué dependes de C? ¿Qué necesitas de su tarea?"
- Si no hay justificación lógica, se puede votar para declarar la dependencia como falsa.
- Si se identifica a un Saboteador: sus dependencias falsas se eliminan.
- Si acusan a un inocente: se pierde tiempo (2 minutos de penalización).

### Final
- **Victoria del Equipo (Coordinador, Ejecutores, Analista):** Completar 6+ tareas en 25 minutos rompiendo correctamente los ciclos.
- **Victoria de Saboteadores:** Que se completen menos de 6 tareas en 25 minutos debido a confusión de dependencias.

## Cómo se gana
- **Equipo Honesto:** 6+ tareas completadas en 25 minutos.
- **Saboteadores:** Menos de 6 tareas completadas en 25 minutos.

## Variantes
- **Para pocos jugadores (5):** 1 Saboteador, ciclo más simple, 4 tareas necesarias.
- **Para muchos (10+):** 3 Saboteadores, múltiples ciclos entrelazados, 9 tareas.
- **Modo cooperativo puro:** Sin Saboteadores, ciclo muy complejo con dependencias múltiples.
- **Modo competitivo:** Cada jugador que completa su tarea gana puntos, el que más puntos tiene al final gana.
- **Modo paralelo:** Algunas tareas pueden hacerse en paralelo si no dependen directamente.
- **Modo visual:** Usar cuerdas físicas entre jugadores para visualizar dependencias físicamente.
