## **1. Autómatas de pila (PDA, Pushdown Automata)**
### **¿Qué es?**
- Un autómata de pila extiende a las FSM añadiendo una estructura de pila que permite manejar contextos y estructuras jerárquicas.
- Son útiles para modelar lenguajes que requieren un seguimiento de estado más complejo, como lenguajes que tienen emparejamiento de paréntesis o estructuras anidadas.

### **Aplicaciones**
- Análisis sintáctico en compiladores.
- Procesamiento de lenguajes contextuales, como XML o JSON.

---

## **2. Autómatas celulares**
### **¿Qué es?**
- Un sistema discreto que evoluciona en pasos, donde cada celda en una rejilla (2D o 3D) cambia de estado según reglas que dependen de los estados de sus vecinos.
- Más orientado a simulaciones dinámicas que a procesamiento lineal.

### **Aplicaciones**
- Simulación de fenómenos físicos (fluidos, incendios).
- Modelado de comportamientos biológicos (crecimiento de células).
- Juego de la Vida de Conway.

---

## **3. Árboles de decisión**
### **¿Qué es?**
- Un modelo de decisiones que utiliza un enfoque jerárquico para determinar acciones o clasificaciones.
- Cada nodo representa una condición, y las ramas indican posibles decisiones basadas en los resultados de la evaluación.

### **Aplicaciones**
- Clasificación y regresión en aprendizaje automático.
- Sistemas expertos.
- Modelado de flujos de trabajo de decisiones.

---

## **4. Redes de Petri**
### **¿Qué es?**
- Una herramienta gráfica que combina conceptos de FSM y flujos concurrentes. Los estados (plazas) y transiciones están conectados por arcos, y los "tokens" fluyen entre ellos.
- Representa procesos concurrentes o distribuidos con sincronización.

### **Aplicaciones**
- Sistemas distribuidos y paralelos.
- Modelado de procesos empresariales.
- Simulación de sistemas en tiempo real.

---

## **5. Sistemas de reglas de producción**
### **¿Qué es?**
- Conjunto de reglas "si-entonces" que se aplican iterativamente hasta que no se cumplen más condiciones.
- No tienen estados explícitos como las FSM, pero logran resultados similares con reglas.

### **Aplicaciones**
- Sistemas expertos.
- Procesamiento de lenguajes naturales.
- Automatización de procesos empresariales.

---

## **6. Grafos dirigidos acíclicos (DAGs)**
### **¿Qué es?**
- Representan procesos o flujos de trabajo donde las tareas tienen dependencias explícitas pero no ciclos.
- Cada nodo es una operación y las aristas indican dependencias entre tareas.

### **Aplicaciones**
- Compiladores (análisis de dependencias entre instrucciones).
- Flujos de trabajo en sistemas distribuidos (como Apache Airflow).
- Procesos de renderizado en gráficos por computadora.

---

## **7. Diagramas de flujo de datos (DFD)**
### **¿Qué es?**
- Representan el flujo de información a través de un sistema. Los procesos, datos almacenados y flujos de datos se representan como nodos y aristas.
- Más abstractos que una FSM, pero útiles para modelar transformaciones de datos.

### **Aplicaciones**
- Análisis y diseño de sistemas.
- Modelado de arquitecturas de software.

---

## **8. Modelos basados en agentes**
### **¿Qué es?**
- Cada "agente" tiene su propio estado y reglas de comportamiento, interactuando con otros agentes y el entorno para resolver problemas más complejos.
- Menos determinista que una FSM y más adecuado para sistemas adaptativos.

### **Aplicaciones**
- Simulación de economías o mercados.
- Sistemas multiagente (como enjambres de robots).
- Juegos y simulación social.

---

## **9. Gramáticas libres de contexto (CFG)**
### **¿Qué es?**
- Describen lenguajes basados en reglas de producción que generan estructuras jerárquicas como árboles.
- A diferencia de FSM, pueden procesar estructuras anidadas.

### **Aplicaciones**
- Diseño de lenguajes de programación.
- Compiladores y parsers.
- Procesamiento de documentos (como HTML o XML).

---

## **10. Algoritmos de búsqueda en grafos**
### **¿Qué es?**
- Representan sistemas o procesos como grafos y utilizan algoritmos de búsqueda (DFS, BFS, A*) para encontrar caminos o soluciones óptimas.
- Más generales que FSM, y aplicables a problemas que no requieren estados estrictamente finitos.

### **Aplicaciones**
- Planificación de rutas.
- Resolución de rompecabezas.
- Modelado de interacciones en sistemas complejos.

---

## **11. Autómatas temporales**
### **¿Qué es?**
- Una extensión de las FSM que agrega restricciones temporales o eventos dependientes del tiempo.
- Los estados tienen tiempos asociados, y las transiciones pueden depender de estos.

### **Aplicaciones**
- Sistemas en tiempo real.
- Modelado de protocolos de comunicación.
- Simulación de procesos industriales.

---

## **12. Workflows basados en BPMN**
### **¿Qué es?**
- Notación de modelado de procesos de negocio (BPMN) que permite definir procesos con eventos, tareas y condiciones.
- Más visual y centrado en la colaboración empresarial.

### **Aplicaciones**
- Gestión de procesos empresariales.
- Automatización de tareas repetitivas.
- Diseño de flujos en herramientas como Camunda o Zeebe.
