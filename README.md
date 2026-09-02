# Pokémon Yuuki

> Fan game de Pokémon desarrollado sobre Pokémon Essentials, con una región original, historia propia, nuevos personajes, Fakemon, gimnasios, eventos y sistemas personalizados.

## Descripción

**Pokémon Yuuki** es un fangame de Pokémon construido sobre **Pokémon Essentials** y el entorno de **RPG Maker XP/RGSS**.

El proyecto combina la estructura clásica de un juego de Pokémon con contenido original: una nueva aventura, ciudades y rutas propias, personajes y rivales, un equipo antagonista, Fakemon, gimnasios con desafíos temáticos, combates contra el Alto Mando y contenido de postgame.

Además de la aventura principal, el proyecto incluye una gran cantidad de recursos gráficos y sonoros, datos de Pokémon, movimientos, habilidades, entrenadores, encuentros y mapas, junto con scripts y plugins Ruby para extender y personalizar el funcionamiento del motor.

---

## Características

- Región y mundo propios con múltiples ciudades, rutas, cuevas e interiores.
- Sistema de combates Pokémon basado en Pokémon Essentials.
- **8 gimnasios** con tipos y desafíos diferenciados.
- **Alto Mando y Campeón**.
- Rivales, entrenadores y personajes propios.
- **Team Yuuki**, organización antagonista con una línea argumental propia.
- Pokémon y **Fakemon** originales.
- Sistema de objetos, movimientos, habilidades y encuentros.
- Gran cantidad de mapas y eventos RPG.
- Música, efectos de sonido y recursos audiovisuales integrados.
- Scripts Ruby y plugins para ampliar las funcionalidades de Pokémon Essentials.

---

## Historia

La aventura sigue a **Alex**, protagonista que comienza su recorrido Pokémon en una región marcada por la actividad del misterioso **Team Yuuki**.

A medida que avanza por la región, el jugador deberá conseguir las ocho medallas mientras descubre qué está ocurriendo detrás de los acontecimientos que afectan a distintas ciudades y pueblos.

La historia combina la estructura clásica de exploración, gimnasios y Liga Pokémon con una trama progresiva alrededor de Team Yuuki, experimentos, tecnología y Pokémon legendarios.

Durante la aventura aparecen diferentes situaciones y desafíos, entre ellos:

- Un gimnasio con una prueba basada en **listening de inglés y andaluz**.
- Una ciudad contaminada donde el jugador debe ayudar a recuperar Pokémon.
- Una zona subterránea conectada mediante un túnel.
- Un pueblo abandonado con Pokémon capaces de hablar.
- Un pueblo afectado por el comportamiento extraño de sus habitantes.
- Un laboratorio relacionado con Team Yuuki.
- Un tren y una confrontación directa con la organización.
- Una zona montañosa nevada donde tiene lugar una de las partes importantes de la historia.
- Un enfrentamiento final por la captura de un Pokémon legendario.

---

## Gimnasios

La aventura está estructurada alrededor de ocho gimnasios, cada uno con una temática y una prueba propia.

| Gimnasio | Tipo | Concepto |
|---|---|---|
| 1 | Normal | Desafío de listening en inglés y andaluz |
| 2 | Planta | Ciudad en un bosque y contaminación |
| 3 | Roca | Ciudad subterránea y resolución mediante Golpe Roca |
| 4 | Fantasma | Pueblo abandonado y laberinto a oscuras |
| 5 | Agua | Isla y desafío basado en una carrera |
| 6 | Psíquico | Preguntas inversas y combates |
| 7 | Hielo | Montañas nevadas y puzzle de hielo |
| 8 | Acero | Montañas y desafío de memoria |

Los gimnasios están planteados para que la progresión no dependa únicamente del combate, sino que cada líder esté acompañado por una prueba o mecánica temática.

---

## Alto Mando y Campeón

Después de conseguir las ocho medallas, el jugador se enfrenta a la Liga Pokémon.

### Alto Mando

1. Fuego
2. Lucha
3. Hada
4. Dragón

El enfrentamiento final corresponde al **Campeón**, vinculado directamente con la historia de Team Yuuki.

---

## Fakemon

El proyecto incluye criaturas originales diseñadas específicamente para complementar la región y sus gimnasios.

Entre ellas aparecen:

| Pokémon | Tipo |
|---|---|
| Ferocuerno | Normal / Fuego |
| Bayleef | Planta / Dragón |
| Omeon | Fantasma |
| Orcabyss | Agua |
| Glacieros | Hielo / Tierra |
| Ludicolo | Fuego / Acero |
| Typhlosion | Fuego / Eléctrico |
| Champeon | Lucha |
| Lukagon | Hada / Dragón |
| Dragoyle | Roca / Dragón |

Estos Pokémon y otros no mencionados se integran dentro de los equipos de líderes, rivales y personajes de la historia.

---

## Team Yuuki

**Team Yuuki** funciona como la principal organización antagonista de la aventura.

Su presencia se desarrolla progresivamente a través de diferentes ciudades y acontecimientos. La historia introduce al jugador en sus actividades mediante encuentros con sus miembros, Pokémon afectados y diferentes instalaciones relacionadas con la organización.

La trama alcanza uno de sus puntos principales en la zona de hielo, donde el jugador descubre información adicional sobre los planes del equipo y se produce una confrontación relacionada con un laboratorio, un tren y Pokémon de alto nivel.
---

## Estructura del proyecto

```text
Pokemon-Yuuki/
│
├── Audio/
│   ├── BGM/
│   ├── BGS/
│   ├── ME/
│   └── SE/
│
├── Data/
│   ├── Maps
│   ├── Actors
│   ├── Animations
│   ├── Classes
│   ├── Common Events
│   ├── Enemies
│   ├── Items
│   ├── Skills
│   ├── States
│   ├── System
│   ├── Tilesets
│   ├── Troops
│   └── Scripts
│
├── Graphics/
│   ├── Characters/
│   ├── Battlebacks/
│   ├── Pokemon/
│   ├── Trainers/
│   ├── Tilesets/
│   └── ...
│
├── PBS/
│   ├── pokemon.txt
│   ├── moves.txt
│   ├── abilities.txt
│   ├── items.txt
│   ├── encounters.txt
│   ├── trainers.txt
│   ├── types.txt
│   └── ...
│
├── Plugins/
│   ├── BW Gender Selector/
│   ├── Improved AI/
│   ├── Voltseon's Handy Tools/
│   └── v20.1 Hotfixes/
│
├── pokemon yuuki/
│   ├── Ideas.txt
│   └── backups/
│
├── Game.exe
├── Game.ini
├── mkxp.json
└── README.md
```

---

## Scripts y plugins

El proyecto amplía Pokémon Essentials mediante diferentes plugins.

### Improved AI

Incluye lógica adicional para mejorar la toma de decisiones de la IA durante los combates:

```text
Plugins/
└── Improved AI/
    ├── AI_EffectScores.rb
    ├── AI_Move.rb
    ├── AI_Move_Utilities.rb
    └── settings.rb
```

### BW Gender Selector

Plugin relacionado con la selección de género y los recursos correspondientes al protagonista.

### Voltseon's Handy Tools

Conjunto de herramientas y métodos adicionales para facilitar la extensión del proyecto.

### v20.1 Hotfixes

Conjunto de correcciones para diferentes aspectos del motor:

- Combates.
- Compilación.
- Debug.
- Overworld.
- Otros comportamientos del juego.

---

## Datos del juego

Los datos principales de Pokémon están organizados mediante archivos PBS.

El proyecto contiene información para diferentes generaciones, incluyendo:

```text
PBS/
├── Gen 5/
├── Gen 6/
├── Gen 7/
└── Gen 8/
```

Además, la carpeta principal `PBS/` contiene los datos específicos utilizados por la versión del juego:

- Pokémon.
- Formas.
- Movimientos.
- Habilidades.
- Objetos.
- Tipos.
- Entrenadores.
- Encuentros.
- Pokémon regionales.
- Battle Tower.
- Concursos.
- Metadatos de mapas.
- Conexiones entre mapas.
- Otros sistemas de Pokémon Essentials.

---

## Audio y recursos

El proyecto incluye una biblioteca audiovisual extensa.

### Música

La carpeta `Audio/BGM` contiene música para diferentes situaciones:

- Pantalla de título.
- Rutas.
- Ciudades.
- Gimnasios.
- Combates contra Pokémon salvajes.
- Combates contra entrenadores.
- Campeón.
- Elite Four.
- Evoluciones.
- Hall of Fame.
- Surf.
- Bicicleta.
- Cuevas.
- Eventos especiales.

También existen recursos de música y efectos asociados a sistemas específicos del juego.

---

## Cómo ejecutar

El proyecto está preparado como un juego ejecutable para Windows mediante:

```text
Game.exe
```

También incluye configuración para **mkxp/mkxp-z** mediante:

```text
mkxp.json
```

La configuración del proyecto establece una resolución inicial de `512 × 384`.

---

## Estado del proyecto

**En desarrollo.**

La base jugable, los sistemas y una parte importante del contenido de la aventura están implementados, pero todavía existen elementos planificados y pendientes de completar.

Entre las tareas documentadas actualmente se encuentra:

- Completar la Ruta 7.
- Añadir el bloqueo de la Ruta 7 para dirigir la progresión hacia el gimnasio correspondiente.
- Continuar el desarrollo de determinados eventos y contenidos de la aventura.
- Completar y pulir elementos del postgame.

---


