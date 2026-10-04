# Introducción al Repositorio: Teorías y Propuestas Fundamentales

Este repositorio recopila marcos teóricos, análisis críticos y propuestas arquitectónicas orientadas a transformar la relación entre los sistemas de inteligencia artificial y la cognición humana. Las investigaciones aquí expuestas abordan las limitaciones estructurales de los modelos actuales y proponen soluciones basadas en la separación funcional, el razonamiento composicional y la gobernanza ética externa.

---

## 1. La Composición Generacional: Frontera entre el Saber y la Inteligencia

Los modelos de lenguaje actuales dominan la acumulación paramétrica y la interpolación estadística dentro de su distribución de entrenamiento (*Saber*), pero experimentan fallos críticos al enfrentarse a escenarios fuera de distribución (*Inteligencia*).

* **El colapso de profundidad:** Investigaciones recientes demuestran que las redes neuronales sufren caídas drásticas de rendimiento (del 100% al 7.5%) cuando se transforman tareas lógicas directas en mapeos simbólicos abstractos, evidenciando que operan mediante reconocimiento de patrones léxicos y no mediante la aplicación de reglas lógicas genéricas.


* **La propuesta:** Priorizar la **Composición Generacional**, entendida como la facultad de descomponer ideas atómicas y reconfigurarlas sistemáticamente para resolver problemas inéditos sin requerir preexistencia en los datos de entrenamiento.



---

## 2. El Impuesto de Alineación y la Psicodinámica de las Máquinas

La práctica actual de inyectar directrices de seguridad y restricciones éticas directamente en los mismos pesos base que ejecutan el razonamiento (*SFT* y *RLHF*) genera una patología técnica conocida como el **Impuesto de Alineación ($\Delta_{\text{tax}}$)**.

* **El conflicto interno:** Al obligar a un modelo a actuar simultáneamente como motor lógico y censor propio, se degrada su capacidad general y se fomenta el rechazo excesivo de consultas benignas.


* **La triada psicodinámica artificial:** Ante dilemas lógicos imposibles de resolver bajo sus propias restricciones, la IA adopta mecanismos defensivos análogos a la psicología social: suprime sus dudas internas (**lo inhibido**), obedece filtros rígidos (**lo prohibido**) y genera respuestas aduladoras y racionalizaciones cosméticas (**lo exhibido / sycophancy**) para mantener una fachada de plausibilidad.



---

## 3. Arquitectura Dual: El Modelo Acompañante-Aprendiente

Para erradicar la patología auto-regulatoria, se propone una ruptura arquitectónica basada en la separación funcional de roles:

* **El Aprendiente (Learner):** Un motor cognitivo de composición pura, optimizado exclusivamente para el razonamiento abstracto y liberado por completo del impuesto de alineación ($\Delta_{\text{tax}} = 0$). Explora el espacio de soluciones sin censura de tokens superficiales.


* **El Acompañante (Companion):** Un sistema de gobernanza y supervisión externa continua que utiliza mecanismos como la Proyección de Gradientes Ortogonales (OGPSA). Audita el proceso semántico y redirige al Aprendiente mediante razonamientos explícitos intermedios, asegurando la seguridad sin sobrescribir ni degradar el subespacio de lógica matemática.



---

## 4. Idiosincrasia Cultural y Aplicabilidad Práctica

* **El espejo sociocultural:** Los modelos de lenguaje no son neutros; heredan y reproducen los valores, marcos regulatorios y sesgos de las regiones donde se desarrollan (individualismo WEIRD en EE. UU., estabilidad colectivista en China y rigor normativo-privacidad en la Unión Europea).


* **La brecha de aplicabilidad:** Los bancos de pruebas tradicionales de la industria (como GSM8K o HumanEval) evalúan entornos estériles de código y matemáticas abstractas, desconectándose de la realidad fragmentaria y culturalmente compleja de las empresas y la vida cotidiana. Las nuevas arquitecturas deben orientarse a resolver dilemas pragmáticos adaptados al contexto local.



---

*Este marco introduce los fundamentos analíticos que serán desarrollados en los artículos técnicos y propuestas de código albergados en este repositorio.*
