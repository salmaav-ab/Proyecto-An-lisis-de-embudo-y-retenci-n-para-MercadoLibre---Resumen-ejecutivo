# Proyecto Análisis de embudo y retención para Mercado Libre

 - Contexto: El director de producto de MercadoLibre necesita entender en qué etapa del proceso se pierden usuarios y cómo mejorar su retención a lo largo del
   tiempo. Como analista del equipo de Crecimiento y Retención, usaré SQL para mapear el embudo de conversión completo, identificar los principales puntos de fuga,
   analizar retención por cohortes y proponer mejoras accionables basadas en datos.
   
 - Dataset utilizado:
   
   > mercadolibre_funnel — registra eventos de usuarios durante el proceso de compra: visitas, clics en productos, agregados al carrito, inicio de checkout,
     información de envío y pago, y compra final.
   > mercadolibre_retention — mide la actividad recurrente por usuario con indicadores de retención por días desde el registro (D7, D14, D21, D28).
   
 - Herramientas:
   > SQL (CTEs, tasas de conversión, análisis de cohortes).

 - Insights principales:
   > Se encontró una degradación progresiva en el embudo. Mientras que la fase de descubrimiento es muy eficiente, existe un abandono notable en la etapa siguiente:
     add_to_cart, sugiriendo que el principal motivo por el cual no se añade al carrito sea el pensamiento de "el gasto no vale la pena en este momento", ya sea
     porque consideran que el costo-beneficio es alto en comparación con otras plataformas, o porque no se ofrecen pagos a plazos sin intereses.
     Existe también una fuerte disminución de la retención a medida que avanza el tiempo. Mientras que en D7 casi todos los países tienen cifras de entre 79 y 87,
     para D28 la retención cae a niveles bajísimos de entre 1.6% y 3.2%. Lo cual significa que MercadoLibre es excelente generando interés de compra en la primera
     semana, pero falla gravemente en convertir esa visita constante a lo largo del mes.

 - Conclusion y recomendaciones:
   > Implementar campañas de impulso a la compra, ya sea lanzando descuentos por tiempo limitado y/o leyendas de "últimas 5 unidades", además de incluir más
     opciones de pago donde el usuario sienta que puede "comprar ahora, pagar después."
     Se requieren medidas que generen en el cliente una sensación de gratificación por la compra, ya sea un programa de lealtad o beneficios recurrentes, para
     evitar la caída de usuarios a lo largo del mes.

