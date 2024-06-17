# FiltradodeDestinosVacacionales

Clasificación de destinos vacacionales según criterios del consumidor

1. Objetivo
2. Resumen de desarrollo
3. Fuentes de datos
4. Ficheros y carpetas
5. Librerías

## Objetivo
Para mejorar la experiencia a la hora de buscar viajes y con el objetivo de que se puedan hacer filtraciones más personalizadas, he decidido hacer una primera clasificación de las 50 ciudades más visitadas del mundo (ampliación a posteriori en caso de que sea viable) según ciertos criterios que puedan interesar a los viajantes. <br>
Con estos filtros podrán encontrar las ciudades en las que coincidan esas características y elegir cuál será su próximo destino.<br>
Airbnb es la página de alojamientos más completa y eficaz, muchos de sus filtros sirven para mi propósito. Lo que no hace esta página es poder aplicar varios de los filtros principales, es decir, se puede filtrar por destino, pero no por preferencias que indiquen los destinos que las cumplen, por ello yo quiero recopilar todos los datos y que se pueda realizar ese múltiple filtrado en mi proyecto.

## Resumen de desarrollo
Las preguntas que he sacado para el filtrado por el momento y que debo ir averiguando si se pueden sacar datos que las respondan son:<br>
Tipo de alojamiento
+ Hotel
+ Bed&Breakfast
+ Casas particulares
+ Casa rural
+ Minicasa
+ Cabaña
+ Granja
+ Frente al lago
+ Casa domo
+ Casas del árbol
+ Camping
+ Castillos
+ Mansiones
+ Casas naturales
+ A pie de playa
+ Cabañas triangulares
+ Diseño
+ Alojamiento de lujo
+ Casa flotante
+ Cueva
+ Caravana
+ Experiencia inmersiva
+ Adaptados
+ Singulares

## Ocio
+ Si la ciudad tiene playa
+ Si tiene montaña
+ Si dispone de oferta de actividades acuáticas
+ Actividades al aire libre
+ Parques nacionales
+ Viñedos
+ Desiertos
+ Cosmopolita
+ Oferta gastronómica
+ Turismo cultural
+ Fiestas
+ Auroras boreales
+ Monumentos relevantes
+ Teatros
+ Museos
+ Historia
+ Lujo
+ Casinos
+ Puertos
+ Atracciones

Clima
+ Tropical
+ Ártico

Otros filtros
+ Precio medio por intervalos
+ Temperatura media
+ Estancia media
+ Población

El proceso se basa en scrapear la web de Airbnb y buscar los criterios que coinciden con los elegidos, cuáles son las ciudades de la lista realizada que cuentan con ellos.<br>
Los que no se puedan buscar en la página de alojamientos, se buscaran en otras páginas realizando filtros en ellas, en API´s si es que las hay o en bases de datos. En caso contrario, el filtro será eliminado.

## Fuentes de datos 

He creado un dataset con los datos de las ciudades más visitadas del mundo<br>
Web de Airbnb <br>
Otras webs con datos relevantes para la clasificación de los criterios

## Ficheros y carpetas

## Librerías
Pandas <br>
Matplotlib<br>
Selenium<br>
Beautiful Soup<br>

