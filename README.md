# Proyecto Análisis de embudo y retención para Mercado Libre

Descripción: El director de producto de Mercado Libre necesita entender en qué etapa del proceso se pierden usuarios y cómo mejorar su retención a lo largo del tiempo. Como analista usaré SQL para mapear el embudo de conversión completo, identificar los principales puntos de fuga, analizar retención por cohortes y proponer mejoras accionables basadas en datos.

Análisis: 
- Se encontró una degradación progresiva en el embudo. Mientras que la fase de descubrimiento es muy eficiente, existe un abandono notable en la etapa siguiente: add_to_cart; sugiriendo que el principal motivo por el cual no se añade al carrito, sea el pensamiento de "el gasto no vale la pena en este momento." Ya sea porque consideran que el costo-beneficio es alto a comparación con otras plataformas o no se ofrezcan pagos a plazos sin intereses.
- Existe una fuerte disminución de la retención a medida que avanza el tiempo. Mientras que en D7 casi todos los países tienen cifras de 79 - 87, para el D28 la retención cae a niveles bajísimos de entre 1.6% y 3.2%. Lo cual significa que mercado libre es excelente generando interés de compra en una primera semana, pero falla gravemente en convertir esa visita constante a lo largo del mes.

Conclusiones:
- Implementar campañas de impulso a compra, ya sea lanzando descuentos por tiempo limitado y/o leyendas de "últimas 5 unidades" + incluir más opciones de pago donde el usuario sienta que pueda "comprar ahora, pagar después."
- Se requiere de medidas que generen al cliente una sensación de gratificación por la compra, ya sea un programa de lealtad o beneficios recurrentes para evitar la caída de usuarios en el mes.
