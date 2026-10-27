# Historias de usuario de búsqueda

| Campo | Valor |
| --- | --- |
| Proyecto | Proyecto Simbiosis |
| Fecha | 27/10/2026 |
| Versión | Versión 1 |
| Estado | Borrador |

## Fuentes comunes

- [Acta de UC-21 Buscar recetas](../captura/acta-acuerdos-uc-21-buscar-recetas.md), v1.1, Vigente.
- [Catálogo de requisitos](catalogo-requisitos.md), UR-08 y FR pertinentes.
- [Modelo de casos de uso](../modelos/modelo-casos-de-uso.md), UC-21.

## Épica de búsqueda

Como [rol], quiero [capacidad amplia], para [beneficio].

**Estado:** descompuesta en US-01, US-02 y US-03. Conserva la necesidad conjunta.

## Justificación de la división

[Justificación de los resultados útiles que separa la división.]

## US-01

**Título:** Buscar mediante una palabra o frase.

Como cliente, quiero poder buscar mediante una palabra o frase una receta, para encontrarla más rápido.

**Fuentes:** UR-08; UC-21; FR-085; acta, criterios de búsqueda.

### Criterios de aceptación

- **CA-01.** Dado que existen las recetas "Tomate con queso fresco" y "Cazuela de bacalao", cuando el usuario busca "Tomate con queso fresco", entonces el sistema muestra exclusivamente la receta "Tomate con queso fresco".
- **CA-02.** Dado que existen las recetas "Sopa de pescado" y "Pescado al horno", cuando el usuario busca "Pescado", entonces el sistema ignora las tildes y mayúsculas y muestra las recetas "Sopa de pescado" y "Pescado al horno". 
- **CA-03.**

## US-02

**Título:** Buscar por ingredientes incluidos

Como usuario, quiero buscar los ingredientes incluidos en una receta, para filtrar los resultados acorde a mis preferencias.

**Fuentes:** UR-08; UC-21; FR-086; acta, criterios de búsqueda.

### Criterios de aceptación

- **CA-01.** Dado que existen los ingredientes "Tomate" y "Lechuga", cuando el usuario busca "Tomate" y "Lechuga", entonces el sistema muestra exclusivamente las recetas que incluyan ambos "Tomate" y "Lechuga".
- **CA-02.** Dado [situación], cuando [acción], entonces [resultado observable].
- **CA-03.** Dado [situación], cuando [acción], entonces [resultado observable].

## US-03

**Título:** Excluir ingredientes

Como usuario, quiero poder excluir ingredientes de las recetas, para facilitar la búsqueda acorde a mis preferencias.

**Fuentes:** UR-08; UC-21; FR-087; acta, criterios de búsqueda.

### Criterios de aceptación

- **CA-01.** Dado que existe el ingrediente "Atún" , cuando el usuario elige excluir el ingrediente "Atún", entonces el sistema muestra exclusivamente las recetas que no contengan el ingrediente "Atún".
- **CA-02.** Dado [situación], cuando [acción], entonces [resultado observable].
- **CA-03.** Dado [situación], cuando [acción], entonces [resultado observable].

## Revisión INVEST

La revisión abarca US-01, US-02 y US-03. «Aplicado» indica si se ha realizado la comprobación. «Cumple» indica si todas las historias cumplen el criterio. Si alguna no lo cumple, indicar «No» e identificar la historia y el motivo en la justificación. Si no se ha realizado la comprobación o faltan datos, indicar «Pendiente» en «Cumple».

| Criterio | Pregunta de revisión | Aplicado | Cumple | Justificación |
| --- | --- | --- | --- | --- |
| Independiente | ¿Puede implementarse cada historia y ofrecer un resultado útil sin implementar antes las otras historias del conjunto? Puede compartir infraestructura con ellas. |No| [Sí/No/Pendiente] | [Historias y motivo] |
| Negociable | ¿Cada historia explica qué necesita la persona y deja margen para discutir los detalles de la solución, respetando los acuerdos confirmados? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Valiosa | ¿La parte «para…» de cada historia explica el beneficio que obtiene la persona al usar esa capacidad? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Estimable | ¿Están claros el alcance y los datos necesarios para estimar el trabajo de cada historia? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Pequeña | ¿Se centra cada historia en una única capacidad de alcance manejable? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |
| Comprobable | ¿Los criterios de aceptación de cada historia describen acciones y resultados observables que permiten distinguir un comportamiento correcto de uno incorrecto? | [Sí/No] | [Sí/No/Pendiente] | [Historias y motivo] |

## Dudas pendientes

[Cuestiones pendientes de aclaración. Si no quedan cuestiones, indicar «Ninguna».]
