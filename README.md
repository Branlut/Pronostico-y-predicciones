# Pronóstico y predicción gimnasio Model Fitness

## Descripción
Model Fitness seta desarrollando una estrategia de interacción con clientes basada en datos analíticos.
Para esto la empresa nos proporciono información sobre perfiles de usuarios de lo cual tenemos que identificar

## Objetivos
- La probabilidad que el cliente no regrese 
- Definir los tipos de usuarios tipicos
- Identificar factores que lleven a la perdida del cliente
- Definir estrategias para aumentar la retención de los clientes

## Tecnologias
- Python
- Vs code
- pandas
- scipy
- numpy
- sklearn
- seaborn
- matplotlib

## Resultados
- Mediante el uso de los modelos de clustering podemos ver que se pueden consideran 5 grandes agrupasiones como se ve reflejado
en el dendrograma el cual tiene 5 diferentes colores
- Con el paso anterior podemos definir la cantidad de clusteres para nuestro modelo de clustering k-means que en este caso serian 5
- Los graficos muestran las caracteristicas que tenian una fuerte correlacion como se puede ver las caracteristicas de periodo de contrato con los meses en los el contrato termina se pueden diferenciar claramente en contraste con los la cantidad total de veces que van al gimnasio y la frecuencia mensual en la cual se cuesta diferenciar las categorias (clusteres) siendo estas caracteristas no son buenas para separar los clusteres
- Al agrupar los datos mediante las categorias creadas por el modelo podemos fijarnos primeramente en los grupos tienen un alto promedio de abandono y ver las caracteristicas que contemplan estos grupos

## Conclusiones
- Tomando en consideracion una gran tasa de abandono podemos crear un sistema de recompensas dependiendo de una cantidad en concreto de vences al mes que las personas vayan al gimnasio al completarla dar un descuento por logros o poder asistir a una clase gratis.
- Los grupos que tienen poca participacion en sesiones grupales se podria enviar informacion sobre entrenadores personales o clases que esten de acuerdo a los gustos de estos o bien promocionar una clase gratis al mes para que las personas puedan ver como es.
- Los grupos que gastan menos se podria incentivar implementando diferentes formas de pago, pagos por semana o cantidad sesiones 
por mes o entre mas meses pagodos aplicar una rebaja
- Para los grupos con bajo abandono informar mediante carteles y correos de la implementacion de equipos nuevos y clases avanzadas ya que son los que utilizan mas los servicios mostrar una aptitud para mejorar lo que se tiene permitira que estos tengan una aptitud positiva con el gimnasio.
