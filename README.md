# TFM_QualityUser

## Introducción
A mediados de 2017 Google Analytics lanzó una nueva métrica denominada calidad de sesión. Esta nueva métrica utiliza técnicas de machine learning similares a Smart List y Smart Goals con el fín de poder evaluar cada sesión y conocer así la probabilidad que ha tenido esta de hacer una conversión.

Disponer de esta información es de gran utilidad ya que los usuarios con sesiones de mayor calidad y que no han llegado a hacer una conversión son mucho más susceptibles de llegar a convertir si les ayudamos a dar ese último paso. Por ejemplo, los usuarios que han estudiado los detalles del producto o añadido artículos a sus carros han dado claras señales de que ya están están bastante interesados por estos productos. Un seguimiento persuasivo a través de una campaña de remarketing bien diseñada puede proporcionar el último empujón que necesitan para completar el proceso.

## Requisitos previos para disponer de esta nueva métrica
Google Analytics impone una serie de requisitos para poder calcular la métrica.
  - Tener implementado seguimiento de comercio electrónico.
  - Un mínimo de 1000 transacciones de comercio electrónico por mes.
  - Una vez alcanzado el umbral inicial de 1000 transacciones de comercio electrónico, Analytics necesita 30 días de datos para modelar.
  
## Objetivo del proyecto
Claramente esta nueva funcionalidad de Google Analytics tiene un gran potencial para cualquier empresa que tenga procesos online (tengan el objetivo de vender o no) pero aun que los requisitos no son muy exigentes, ciertas empresas seguro que no tendrán implementado el seguimiento de e-commerce y otras no lleguen a tener 1000 transacciones mensuales.

Además esta nueva métrica pese a tener un gran potencial, está claramente limitada. La gran mayoría de las empresas dispone de varios canales a traves de los cuales llegan a sus clientes y está métrica se calcula para cada uno de estos canales por separado sin tener en cuenta si el usuario ha accedido a otros canales y como ha interactuado en estos.

Por otro lado, considero que lo realmente importante para un negocio no es una sesión en concreto si no el usuario.

Por estos motivos mi objetivo es replicar estas métricas usando las técnicas de machine learning aprendidas en el máster en data science de Kschool y si es posible intentar profundizar más aun y no quedarnos únicamente en la sesión e intentar acercarnos más al usuario. Además, el poder replicar esta métrica nos dará libertad para poder hacer el seguimiento a traves de los diferentes canales si lo deseamos. En definitiva el objetivo es hacer un proyecto que facilite este trabajo a cualquier empresa 😁.

Go for it!💪
