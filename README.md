# Optimizacion_Cadena_de_Suministro de Bananos en Ecuador
Caso: Embarques Fincas Bananeras Ecuador

## Contexto
Ecuador, reconocido como líder mundial en la exportación de banano, enfrenta el desafío de optimizar su cadena de suministro. El país necesita gestionar de manera eficiente el transporte de banano desde las principales zonas productoras en las provincias de El Oro, Guayas y Los Ríos hasta sus puertos de exportación. Este ejercicio propone un modelo complejo que considera varias plantaciones y la demanda en los puertos, influenciada por las rutas comerciales internacionales.
Objetivo
El principal objetivo es minimizar los costos totales de transporte. Esto incluye considerar las capacidades de producción en cada plantación, las necesidades de los mercados internacionales y la disponibilidad de rutas de transporte marítimo.
Datos del Problema
Capacidad de Producción de las Plantaciones (en toneladas)
•	El Oro:
	Machala: 700 ton
	Pasaje: 650 ton
•	Guayas:
	Naranjal: 750 ton
	Milagro: 775 ton
•	Los Ríos:
	Babahoyo: 650 ton
	Quevedo: 725 ton
Demanda en los Puertos (desglosada por país y estado de EE.UU., en toneladas)
•	Guayaquil:
	España: 350 ton
	Alemania: 250 ton
	Florida, EE.UU.: 500 ton
•	Manta:
	México: 450 ton
	Italia: 200 ton
	California, EE.UU.: 300 ton
•	Puerto Bolívar:
	Estados Unidos (Texas): 400 ton
	Canadá: 300 ton
	Reino Unido: 300 ton
•	Esmeraldas:
	Francia: 250 ton
	Reino Unido: 200 ton
	Japón: 350 ton
Costos de Transporte (USD por tonelada)
Los costos de transporte se calcularán basándose en la distancia desde cada plantación hasta los distintos puertos, asumiendo un costo promedio de $0.20 USD por kilómetro por tonelada.
Planificación de resolución
•	Modelar el problema utilizando la programación lineal.
•	Definir variables de decisión para las toneladas de banano a transportar desde cada plantación a cada puerto.
•	Establecer una función objetivo para minimizar el costo total del transporte.
•	Incluir restricciones para respetar la capacidad de producción y satisfacer la demanda de cada puerto.
•	Analizar los resultados para entender la distribución óptima y el costo total del transporte.
