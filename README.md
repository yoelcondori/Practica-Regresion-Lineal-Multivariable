# Practica-Regresion-Lineal-Multivariable
La venta de carros es en Juliaca es uno de los mercados más sólidos y extensos, donde existe la necesidad, como en toda venta de artículos de segunda mano, de hacer una estimación del carro para poder comprarlo o venderlo. Sin embargo, ésta no es directa y es efectuada mayormente por personas conocedoras del negocio y con experiencia en el rubro. Dada esta problemática, en este laboratorio se busca una forma de poder automatizar el proceso, utilizando ejemplos del mercado para poder predecir cómo el precio de un carro se comporta a través de los años, de manera que un usuario pueda obtener una buena estimación del carro que quiere comprar o vender.
1.	Descripción del Problema
La venta de carros es en Juliaca es uno de los mercados más sólidos y extensos, donde existe la necesidad, como en toda venta de artículos de segunda mano, de hacer una estimación del carro para poder comprarlo o venderlo. Sin embargo, ésta no es directa y es efectuada mayormente por personas conocedoras del negocio y con experiencia en el rubro. Dada esta problemática, en este laboratorio se busca una forma de poder automatizar el proceso, utilizando ejemplos del mercado para poder predecir cómo el precio de un carro se comporta a través de los años, de manera que un usuario pueda obtener una buena estimación del carro que quiere comprar o vender.
Los ejemplos del mercado se han consolidado en un conjunto de datos de carros usados, por lo que se le solicita construir un modelo de regresión lineal utilizando los valores de estos ejemplos para poder predecir el precio de un carro usado que cuenta ciertas características para que un usuario pueda adquirir o vender un carro acertadamente.
2.	Descripción de los Datos 
Para el presente laboratorio utilizará el conjunto de datos cars_dataset.csv que contiene la siguiente información de carros usados:
Características 	Descripción
Name 	Nombre del carro
Year 	Año de fabricación de carro
km_driven 	Kilómetros recorridos
fuel	Tipo de combustible que usa el carro
seller_type	Tipo de vendedor
transmission	Tipo de transmisión
Owner	Propietario del carro
mileage	Kilometraje
engine	motor
max_power	Máxima potencia
torque	Potencia de tracción
seats	Número de asientos
Variable objetivo	Descripción
selling_price 	precio de venta, variable a ser predecida
