https://www.deeplearning.ai/short-courses/multi-ai-agent-systems-with-crewai/

Flujos de trabajo son el motor del progreso a corto plazo
El desgloce de tareas en subtareas pueden ser ejecutadas por agentes cada uno de los cuales juega un rol definido en particular.

CREACION DE BLOQUES PARA SISTEMAS AGENTIVOS CON ENFASIS EN SISTEMAS MULTIAGENTE

Bloques de conocimiento Incluyen: 
  interpretacion - uso de herramientas - memoria - barreras de seguridad y colaboracion

Podemos crear un agente manager que delege en varios agentes trabajadores el flujo de trabajo, teniendo la opcion que sea un trabajo simultaneo o jerarquico entre los agentes.

# Resumen

ROLE PLAYING 
FOCUS
TOOLS
COOPERATION
GUARDRAILS (limites)
MEMORY

Multi agent colaborations

<img width="369" height="254" alt="multileng" src="https://github.com/user-attachments/assets/3447b7ea-61a7-45c9-800c-d580de7a7099" />

########################################################
La cobertura del curso 
Overview
  Research & write a technical article
  
Multi Agent core concepts
  Customer support AI Agents

Using Tools at Scale
  Customer outreach campaign

Tasks and Processes
  Event planning

Agentic Collaboration
  Financial analysis

Build a complete Crew
  Tailor-made resumes

########################################################

Al final del curso podremos crear un sistema multiagentes aprovechando 4 agentes diferentes

<img width="634" height="165" alt="image" src="https://github.com/user-attachments/assets/90e228e8-241e-4e6e-afd3-822201e80421" />

Las tareas que tendran seran:
  Search the internet
  Read websites
  Read resume
  Perform RAG on the resume (Retrieval Aumented Generation)


La utilizacion de Agentic Automation

<img width="626" height="318" alt="image" src="https://github.com/user-attachments/assets/8ca79a6a-6942-428d-93eb-bac30ead3974" />

Data Collection and Analisis

En un caso tipico donde tenemos datos de un sitio web que luego al analisarlo deberia ser enviado al equipo de ventas mediante la categorizacion de prioridades ya sea por cantidad de empleados o por metricas de locacion.

<img width="454" height="238" alt="image" src="https://github.com/user-attachments/assets/9be126e3-8b7e-4d34-b38c-cbc194fb40cb" />


Con un equipo de agentes podemos hacer que busquen informacion de las empresas, comparen con otras empresas, crear un scoring y hablar sobre esos puntos.
Y luego si enviarlos al equipo de ventas

<img width="591" height="259" alt="image" src="https://github.com/user-attachments/assets/e72d51e0-ea33-4e6c-a4cb-c32238ca1f52" />


# Que son los agentes

Los LLMs (Large Language Models, o Modelos de Lenguaje Grandes) son sistemas avanzados de Inteligencia Artificial (IA) entrenados con cantidades masivas de texto para entender, generar y manipular lenguaje humano natural.

<img width="386" height="186" alt="image" src="https://github.com/user-attachments/assets/455eeecb-5f1d-4291-9ca2-62a58ce87234" />

Con los llms tienes que darle feedback a travez de interacciones para asegurarte de los resultados entre el LLM y el usuario.

LLMS - FEEDBACK - USUARIO   dependiendo la cantidad de feedback generamos mejor experiencia para el usuario 

<img width="396" height="235" alt="image" src="https://github.com/user-attachments/assets/d89b7462-40e2-4371-9c62-76edf7df796a" />

La forma que funcionan los agentes es desarmar el feedback en partes resolviendo problemas pequeños y dejar que el LLM trabaje de forma autonoma.

Por lo que un agenete "nace" cuando el LLM entra en su proceso de pensamiento a lo largo del procedo de hacer preguntas y responderlas por el mismo hasta el punto de que puede seguir adelante y mejorar por si solo.

<img width="235" height="296" alt="image" src="https://github.com/user-attachments/assets/3eb4e2b1-c34e-474e-8eff-b7056f8e048d" />

El agente no te dara la primer respuesta sino que evaluara y optimizara el pensamiento que tenga para luego darte la respuesta. 
Tambien tiene la capacidad de utilizar herramientas, que otros marcos llaman SKY o Capabilities pero lo que hara esto poderoso es que permite a tu agente interactuar con el mundo exterior. Como utilizar una API, postear algo o recopilar un dato clave.

## Estructura Multi agente
En vez de tener un solo agente, ahora podemos tener un agente que asigne a otro agente una tarea. Teniendo una respuesta final.

<img width="246" height="266" alt="image" src="https://github.com/user-attachments/assets/97ca458a-446c-48fe-bb12-717d13ad1a27" />

Como primer beneficio podemos ver que podemos customizar a los agentes teniendo una sola tarea.
Como un agente Researcher que envie la informacion obtenida en busquedas a otro agente Escritor que genere un reporte. Tambien lo bueno es que podemos utilizar varios modelos para optimizar la respuesta.

<img width="254" height="194" alt="image" src="https://github.com/user-attachments/assets/9d3a765c-86f5-49a2-8849-5bdc3c31867f" />

## Que es Crew.Ai
- Es un framework y una Plataforma
- Rompe todos estos conceptos en simples estructuras
- Provee un patron para juntar estos sistemas
- Provee herramientas y skills listos para usar en agentes
- Brinda un modelo para crear herramientas para personalizar agentes.
- Ofrece una plataforma para brindar estos agentes en produccion.

### Initial Building Blocks

   AGENTES
   TAREAS
   CREWS
















  
