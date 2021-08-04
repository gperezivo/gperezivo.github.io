---
layout: post
title:  "Accediendo a GPT-3"
date:   2021-08-05 01:25:36 +0200
tags: AI GPT-3
---

El ritmo al que avanza todo lo relacionado con __[Inteligencia Artifical](/tag/AI)__ es impresionante.
Hace cosa de un mes hablando con compañeros sobre procesado de lenguaje natural salió a la conversación (como no) el __[GPT-3](/tag/GPT-3)__

Que __[GPT-3](/tag/GPT-3)__ actualmente en su campo es el rey de la montaña creo nadie que haya visto que es capaz de hacer puede discutirlo. Para hacernos una idea, la potencia de estos modelos se mide (o suele usarse como referencia) en la cantidad de variables con las que han sido entrenados.

Para hacernos una idea de la diferencia con modelos similares veamos la cantidad de variables usadas en otros modelos: 

| Modelo | Variables de entrenamiento | 
|--------|----------------------------|
| GPT-2  | 1.5 billions               |
| Turing NLG (Microsoft) | 17 billions|
| GPT-3  | 175 billions | 



Todo lo relacionado con [Deep Learning](https://en.wikipedia.org/wiki/Deep_learning) dista mucho de ser mi especialidad, así que voy a dejar que GPT-3 os de una definición de si mismo: 

![Definición de GPT-3 por GPT-3](/assets/gpt-3-dnd/gpt-3-def.png)

¿Me ha vacilado el GPT-3? Me ha vacilado GPT-3...

El acceso que dan funciona de dos maneras, o bién vía código conectas a la API con un API Key donde envias el texto y devuelve su respuesta o bien mediante la web de 
[openai.com](https://openai.com)

En el caso de usar la web de [Open AI](https://openai.com) además de documentación tiene una pantalla donde puedes escribir y directamente que el modelo lo procese.
Este es el método que seguiremos en este artículo.

Cuando yo escribo algo, se resalta en negrita y el texto generado por GPT-3 aparece normal.

Escribiendo solo
```
Guillermo: ¿Como explicarías que es GPT-3?
GPT-3: GPT-3
```

Ya le estamos proporcionando el contexto suficiente para que genere una conversación entre _Guillermo_ y __[GPT-3](/tag/GPT-3)__

En este caso, ha contestado en Inglés ya que es "_su idioma_" por defecto. 

Pero no se ha quedado ahí, ha incorporado a un _Humano_ a la conversación y ha seguido de la siguiente manera (obviando el hecho de que considera tener mejor sentido del humor que yo...)

![Definición de GPT-3 por GPT-3](/assets/gpt-3-dnd/full_intro.png)

Inquietante... el _Humano_ interpretado por __[GPT-3](/tag/GPT-3)__ no se fía de el porque es un programa muy potente, __[GPT-3](/tag/GPT-3)__ no me cree y el _Humano_ dice que está hablando conmigo porque está seguro de que no soy un programa.

Aquí hay muchas capas de cosas que están pasando, entre ellas que __[GPT-3](/tag/GPT-3)__ asume el rol de _Humano_, conversa consigo mismo, desconfia de si mismo en su rol de _Humano_ y lo usa para hablar "bien" de __[GPT-3](/tag/GPT-3)__, ya que al final se está denominando a si mismo _"very powerful computer program"_. 

Corriendo un tupido velo sobre esta "conversación" intentamos que nos responda en Español así que introducimos lo siguiente: 
```
Guillermo: ¿Cómo explicarías que es GPT-3?
GPT-3: GPT-3 es
```

Y obtenemos la siguiente respuesta:

![Definición de GPT-3 por GPT-3 en español](/assets/gpt-3-dnd/gpt-3-def-es.png)

Con esta autodefinición de __[GPT-3](/tag/GPT-3)__ y viendo el potencial que tiene dejamos esta primera entrada relacionada con el tema.

Estad atentos que vendrán más!


---

Enlaces: 
- [Deep Learning en Wikipedia](https://en.wikipedia.org/wiki/Deep_learning)
- [GPT-3 en Wikipedia](https://es.wikipedia.org/wiki/GPT-3)
- [Open AI](https://openai.com/)
