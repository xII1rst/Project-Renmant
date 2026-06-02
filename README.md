# The Ancient Remnant
**Game Design Document v0.9**

> *Un Metroidvania sobre el fin del mundo y la naturaleza del alma.*

---

## Metadata

| Campo | Valor |
|---|---|
| Género | Metroidvania 2.5D |
| Motor | Godot 4 |
| Desarrollador | Solo Dev |
| Protagonista | Titus |

---

## 00 — Visión General

> *La maldad no es creada por las circunstancias. Las circunstancias solo **revelan** lo que siempre estuvo ahí.*

Un hombre criado en el mundo corrompido despierta sin memoria tras un golpe — sin saber quién es, por qué fue entrenado, ni qué se supone que debe hacer. Un conquistador cósmico lleva décadas consumiendo la vitalidad mágica del planeta, expandiendo su dominio con un ejército de discípulos y terratenientes que administran los territorios conquistados en su nombre.

El jugador explorará un mundo en distintos niveles de corrupción, aliándose con los últimos guardianes y chamanes que sobreviven en las sombras, recuperando fragmentos de un cristal ancestral sellado por Merlín — el único artefacto capaz de contener a la Entidad — y enfrentando a los terratenientes que controlan cada zona y buscan activamente abrir las cajas que los guardan.

Lo que Titus no sabe: es la única llave que existe para esas cajas. Su sangre las abre. Y usar el cristal al máximo podría costarle la vida.

**Referencias:**
- **Hollow Knight / Silksong** — Progresión de mapa, jefes con narrativa propia, mundo con historia enterrada
- **Little Nightmares / God of War clásico** — Profundidad cinematográfica, cámara controlada, escenarios amplios y verticales
- **Metro 2033** — Sistema de karma invisible que registra las acciones del jugador sin mostrarlo explícitamente
- **Avatar: The Last Airbender** — Progresión de habilidades aprendidas de distintas culturas, sin reducirlas a elementos genéricos
- **Estética visual** — Cielos pintados naranja/púrpura, nubes dramáticas, radiotelescopios oxidados, tierra post-apocalíptica con belleza residual

---

## 01 — El Mundo

La Tierra, décadas después de la llegada de la Entidad. La civilización colapsó en los primeros años. Lo que queda es un planeta interrumpido — ciudades vaciadas, bosques retorcidos, océanos que cambiaron de curso.

### Historia Cronológica

**La Primera Visita**
La Entidad no es nueva en la Tierra. Su primera visita causó la extinción de los dinosaurios. Los restos de esa visita quedaron enterrados: fragmentos de energía fosilizada, anomalías en la tierra, ecos de algo que no debería existir.

**El Origen del Cristal**
Milenios después, los primeros y más poderosos magos de la Tierra estudiaron esos restos. Documentaron la naturaleza de la Entidad: lo que era, cómo funcionaba, y que volvería. El conocimiento los dividió. Los que eligieron resistir crearon el Cristal Ancestral — fusionaron su magia y su espíritu en él. Sus consciencias viven dentro. No es un objeto inerte: tiene voluntad y criterio. Los que eligieron adorarla se organizaron en una orden que lleva siglos esperando su regreso.

**Merlín y las Cajas**
A Merlín — el más débil de su generación, y por eso el único que no tuvo que fusionarse — le fue encomendada la custodia del cristal. Custodió el cristal completo durante años. La exposición prolongada lo fue consumiendo lentamente. Sabiendo que moriría, lo fragmentó y selló cada pieza en una caja individual con su propia sangre — el sello protege el fragmento del exterior y protege al portador de la exposición. Solo la sangre de su linaje puede abrirlas. Distribuyó las cajas a magos puros de distintas naciones y murió tiempo después. El plan quedó completo.

**Año 0 — La Segunda Llegada**
La Entidad regresa. Siente la concentración de vitalidad mágica acumulada desde su primera visita y no puede ignorarla. Sus adoradores en la Tierra se ponen a su servicio inmediatamente.

**Años 1–10**
Absorción masiva de vitalidad mágica. Los de corazón oscuro transmutan — la Entidad no los corrompió, *reveló* lo que existía dentro. Los de corazón puro se esconden o resisten. Los humanos sin vitalidad mágica son invisibles para ella. Los padres de Titus — hechiceros del linaje de Merlín — mueren peleando. Dejan a su hijo con Ender, hermano de su madre y custodio de una de las cajas. Los guardianes originales de Merlín mueren defendiendo las suyas. En algunos templos, sus discípulos continúan la guardia.

**Años 10–50**
Los hechiceros adoradores, potenciados por la Entidad, toman control territorial. Se convierten en terratenientes — administradores de zonas, cazadores de supervivientes, y guardianes involuntarios de las cajas que no pueden abrir.

**Presente**
La corrupción es el estado normal del mundo. Titus lleva años viviendo en él, siendo entrenado por Ender. Hasta que todo cambia.

---

## 02 — El Protagonista — Titus

Descendiente directo del linaje de Merlín por línea paterna. Creció en el mundo corrompido bajo la tutela de su tío Ender después de que sus padres murieran peleando al inicio de la invasión. Sus padres eran hechiceros — él creció con esa herencia sin entenderla completamente. No es un héroe de nacimiento. Es su corazón lo que lo distingue.

### El Prólogo — La Pelea con Ender

Titus confronta a su tío. Cree estar listo. Quiere ir por la Entidad ahora. Ender lo frena — no porque dude de su poder, sino porque teme su impulsividad en el momento decisivo. Se pelean. En el forcejeo, Titus hiere a Ender de gravedad sin saberlo. La pelea lo lanza lejos. Pierde el conocimiento.

Este prólogo funciona como tutorial — Titus actúa por instinto, el jugador aprende los controles.

### La Amnesia

Cuando despierta, no recuerda quién es. Reconoce el mundo corrompido porque lleva años en él. No recuerda su entrenamiento, su linaje, ni a Ender. Sus habilidades aparecen de forma instintiva, sin saber de dónde vienen.

### El Reencuentro con Ender

Al recuperar suficientes memorias, Titus recuerda dónde vive Ender. Lo encuentra herido de gravedad, tendido donde cayó — lleva días así. En sus últimas palabras, Ender le indica dónde está la caja que custodió — que su sangre puede abrirla, que hay más, que los fragmentos son lo que necesita para enfrentarse a la Entidad. Confiesa que temía su impulsividad, pero que nunca vio maldad en sus ojos.

Su última frase: *"No confíes en todo lo que ves."*

Titus encuentra la caja. Su sangre la abre sin entender por qué. El fragmento le entrega poder inmediato y una visión fragmentada. El mundo acaba de cambiar de tamaño. Este es el verdadero inicio del juego.

### Arco Narrativo

**Prólogo** — La pelea con Ender. Amnesia. Tutorial.

**Acto I — Desorientación** — Despierta sin identidad. Los déjà vus empiezan. Encuentra a Ender moribundo. Abre la primera caja. El viaje comienza.

**Acto II — Descubrimiento** — Recorre las zonas, enfrenta terratenientes, recupera fragmentos. Cada caja abierta activa visiones del origen del cristal. Encuentra guardianes — algunos fieles, algunos desertores, algunos heridos. Con el tercer o cuarto fragmento, la visión revela el costo: quien use el máximo poder del cristal morirá. Titus lo sabe antes del final.

**Acto III — Decisión** — Con el cristal completo, Titus elige. Lo que ocurre depende de quién es — y de quién decidió ser el jugador.

---

## 03 — Ender

Hermano de la madre de Titus. Custodio de una de las cajas de Merlín — no por linaje sino por confianza. Crió y entrenó a Titus durante años. Su filosofía: hacer el bien no como estrategia sino como naturaleza. Los símbolos que le enseñó a Titus son los mismos que aparecen en los guardianes supervivientes — cada vez que Titus los reconoce es un déjà vu, un pedazo de Ender que regresa.

---

## 04 — La Entidad

> *No llegó a destruirlos. Llegó a conquistar. Son cosas distintas — aunque el resultado sea el mismo.*

Un conquistador cósmico que lleva eones expandiendo su dominio absorbiendo la vitalidad mágica de los planetas. Su primera visita a la Tierra causó la extinción de los dinosaurios. Regresa ahora porque la vitalidad acumulada desde entonces es irresistible. Tiene discípulos — en la Tierra, llevan siglos esperando su regreso.

- **Tiene agenda.** Conquistar. Expandir. Absorber. Hay voluntad detrás, aunque sea fría e incomprensible.
- **Tiene forma.** No es una nube de polvo cósmico. Es una presencia con estructura y jerarquía. La confrontación final es contra algo real.
- **Solo afecta lo que tiene magia interior.** Los humanos sin vitalidad mágica son invisibles para él.
- **Amplifica lo existente.** No crea el mal — en quienes no eligieron servir, revela lo que ya existía dentro.
- **Puede ser sellado.** Con el cristal completo y la sangre del linaje de Merlín.
- **¿Tiene consciencia moral?** Queda ambiguo. Nunca se confirma.

Su influencia se siente progresivamente en el mundo — la música cambia cerca de sus zonas de mayor concentración, la física se altera en el Núcleo.

---

## 05 — El Cristal Ancestral

Creado por los primeros magos mediante la fusión de su magia y espíritu. Sus consciencias viven dentro — tiene voluntad y criterio. Merlín lo fragmentó, selló cada pieza en una caja con su sangre, y distribuyó las cajas antes de morir.

Cada caja abierta por Titus activa una visión del origen del cristal. Las primeras muestran la creación. Con el tercer o cuarto fragmento se revela la maldición: quien use el máximo poder del cristal morirá.

Cuando Titus usa el cristal para sellar a la Entidad, el cristal reconoce el sacrificio — que se lanzó sabiendo el costo es exactamente lo que los primeros magos esperaban. El cristal atrapa su vitalidad antes de que se pierda y se destruye liberando la energía del sello. Titus sobrevive, pero lleva dentro la vitalidad de los primeros magos de la Tierra.

---

## 06 — Facciones

### Los Guardianes de Merlín

La orden que quedó después de que los guardianes originales murieron. Llevan generaciones protegiendo cajas cuyo propósito completo conocen solo en parte. El tiempo los fracturó en tres grupos:

**Los que se quedaron** — Fieles hasta el presente. Agotados y reducidos. Son los que más saben pero los que menos quedan. Reconocen a Titus — o reconocen su sangre — antes de que él se recuerde a sí mismo.

**Los desertores** — Se fueron porque esperar algo imposible durante generaciones destruye a cualquiera. No por cobardía — por ser humanos. Cuando ocurre lo que esperaban, sienten culpa y la obligación de ayudar con lo que les queda. Algunos son más útiles que los que se quedaron, precisamente porque sobrevivieron adaptándose al mundo corrompido.

**Los heridos** — Físicamente, emocionalmente, mágicamente. Cada uno es un registro vivo de lo que costó proteger las cajas.

Los hechiceros adoradores conocen la tradición lo suficiente como para imitarla. La advertencia de Ender aplica en todo momento.

### Los Chamanes Puros

Magos cuya integridad de corazón fue su escudo. No forman parte de la orden de Merlín pero comparten sus valores. Algunos reconocen a Titus antes de que él se recuerde a sí mismo. Proveen habilidades, lore, y orientación — cada uno con su tradición específica a su región.

### Los Humanos Sin Magia

Invisibles para la Entidad. Llevan décadas construyendo comunidades adaptadas al mundo corrompido. Su existencia plantea preguntas incómodas: si el mundo se restaura, ¿todos lo quieren?

### Los Hechiceros Adoradores — Mini-Jefes

Descendientes de los estudiosos que conocieron los restos de la primera visita y eligieron adorar en vez de resistir. Llevan generaciones organizados. Con la llegada de la Entidad recibieron poder directo. Ahora operan junto a los terratenientes — cazan supervivientes, patrullan territorios, y buscan formas de abrir las cajas. Son pocos pero notables. Cada encuentro tiene peso narrativo propio. No fueron corrompidos — eligieron esto. Llevan siglos eligiéndolo.

### Los Terratenientes — Jefes Principales

Hechiceros que eligieron servir a la Entidad cuando llegó — vieron poder donde otros vieron destrucción. Recibieron territorios a cambio: administran zonas, cazan supervivientes, y llevan años intentando abrir las cajas sin éxito. La sangre no es la correcta.

Derrotarlos no los mata — los *confronta*. Lo que ocurre después depende de quiénes eran y de cuánto queda de eso.

> *"No los corrompió la Entidad. Les ofreció lo que ya querían. Eso es diferente."*

---

## 07 — Jefes

Entre 5 y 6 terratenientes en total, uno por zona. Cada uno controla el territorio donde está la caja. Cuando Titus llega, él tiene lo que ellos necesitan y ellos tienen lo que él necesita.

**Jefes 1–2** — Corrupción media. El poder de la Entidad en ellos es visible pero no total. El primero lleva años sabiendo que alguien con la sangre correcta vendría eventualmente.

**Jefes 3–4** — Corrupción alta. Más integrados, más lejos de lo que eran. En este tramo Titus recibe las visiones que revelan el costo del sello.

**Jefe final** — El más poderoso y el más cercano a la Entidad. Pelea multi-fase. Su derrota abre el camino a la confrontación final.

Los hechiceros adoradores aparecen como mini-jefes entre los terratenientes. Cada encuentro revela algo sobre su orden, su historia, o la zona que habitan.

---

## 08 — Zonas del Mundo

Progresión lineal entre zonas, con libertad de exploración dentro de cada una. Cada zona tiene un terrateniente, una caja sellada, y un centro narrativo. Los guardianes y chamanes están dispersos dentro de cada región.

### Zona 1 — Ruinas Urbanas
Lo que queda de una ciudad moderna. Vegetación creciendo entre el concreto. Aquí Titus despierta, abre su primera caja, y enfrenta al primer terrateniente. Cultura superviviente urbana — gente que nunca salió y aprendió a vivir entre las ruinas.
**Corrupción:** ●●○○○

### Zona 2 — El Desierto Árido
Donde hubo océanos. Arena mágica que conserva ruinas enterradas. Tradiciones mágicas ligadas a la resistencia, la conservación y el silencio.
**Corrupción:** ●●●○○

### Zona 3 — El Bosque Corrompido
Vegetación retorcida, oscuridad perpetua bajo el dosel. Una cultura que vivió en simbiosis con la naturaleza — ahora cuida lo que queda de ella. Sus tradiciones mágicas son las más antiguas después de los primeros magos.
**Corrupción:** ●●●○○

### Zona 4 — La Cordillera
Paso obligado — no hay otra ruta. Culturas aisladas que sobrevivieron por la inaccesibilidad del terreno, con tradiciones únicas desarrolladas sin contacto exterior. Aquí Titus recibe la visión que revela el costo del sello.
**Corrupción:** ●●●●○

### Zona 5 — The Great Canon
Un cañón profundo al otro lado de la cordillera. Fauna, cultura y tipo de corrupción distintos a todo lo anterior. Los enemigos ya no son reconocibles como lo que fueron. La civilización que sobrevivió aquí lo hizo adaptándose a la oscuridad.
**Corrupción:** ●●●●○

### Zona 6 — El Núcleo
Más allá del cañón. La Entidad es visible de forma permanente. La física del mundo se altera — la corrupción no es solo visual sino sensorial. El terrateniente final, la última caja, la confrontación.
**Corrupción:** ●●●●●

---

## 09 — Gameplay

### Estilo Visual

Geometría 3D con cámara fija de perspectiva lateral-cinematográfica, siguiendo el modelo de God of War clásico y Little Nightmares. Escenarios amplios y verticales con profundidad real. Las boss fights pueden tener arenas con más libertad de cámara como contraste deliberado.

### Sistema de Karma — Invisible

No hay barra visible ni indicador. El juego registra silenciosamente las acciones del jugador: proteger a los débiles, matar indiscriminadamente, usar magia oscura innecesariamente, tratar con crueldad a quienes dependen de él. El jugador actúa por instinto moral — no optimiza puntos. Al acumular suficientes acciones positivas se activa el camino al final bueno. El sistema nunca se explica en el juego.

### Sistema de Déjà Vus

Los símbolos del linaje de Merlín aparecen en objetos, guardianes y lugares. Cuando Titus los encuentra, activan fragmentos de memoria — el entrenamiento con Ender, momentos de su infancia, instrucciones recibidas sin entender en su momento. Se vuelven más frecuentes y específicos a medida que avanza el juego.

### Progresión de Habilidades

Aprendidas de chamanes y guardianes de cada región — cada tradición cultural aporta algo único. Encontradas en libros y escritos dispersos. Desbloqueadas al derrotar terratenientes. Recuperadas a través de déjà vus. Al final del juego, Titus pelea con un estilo que refleja todo lo que vivió — no hay clase fija, hay una historia en cada movimiento.

### Las Cajas

Cada zona tiene una caja sellada controlada por el terrateniente. Para obtener el fragmento, Titus derrota al terrateniente y abre la caja. La apertura activa una visión. El jugador siempre sabe cuánto le falta y por qué importa cada confrontación.

### Restauración del Mundo

Al recuperar cada fragmento, la zona se restaura visualmente — colores que vuelven, música que evoluciona, flora y fauna que recuperan su vitalidad. El progreso tiene consecuencias permanentes.

---

## 10 — Los Finales

### Final Bueno — El Sello

Titus actuó con integridad. Usa el cristal sabiendo que podría morir. El cristal lo reconoce — atrapa su vitalidad antes de que se pierda y se destruye liberando la energía del sello. La Entidad queda contenida. Titus sobrevive portando la vitalidad de los primeros magos de la Tierra.

**Cutscene final:** Titus de pie en una colina. El sello está hecho. El mundo sigue roto — corrupto, silencioso, igual que antes. El cristal está destruido. Mira sus manos. Algo brilla adentro. El mundo no se salvó. El trabajo acaba de empezar.

### Final Malo — La Ruptura

Titus se corrompió a lo largo del juego. Usa el cristal como arma, no como sello. La Entidad se fragmenta en oscuridad pura que se dispersa sin control. Lo que la Entidad absorbía ahora se derrama. El mundo no se rompe. Se pudre desde adentro.

---

*The Ancient Remnant — GDD v0.9*
