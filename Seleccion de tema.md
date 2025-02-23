**Entregable**
- [ ] Subir en formato pdf cuando este disponible. Un solo integrante del grupo subir el documento en formato PDF a la plataforma oymas.

**Notas**
Cada Grupo debe subir los nombres y matriculas de los estudiantes, recordando que el maximo por grupos es de 4 estudiantes y minimo de 1. 

A continuación, algunos criterios para elegir el tema:
- El tema a tratar debe ser novedoso, atractivo, interesante y realista.  
- El participante debe cerciorarse de que existe suficiente información y de que es posible conseguirla de alguna fuente accesible y confiable.  
- El Informe Final debe ostentar un buen nivel profesional, con el nivel y la importancia que se exige para un trabajo de grado.  
- Los responsables del proyecto deben poseer amplios conocimientos acerca del tema o estar en capacidad de adquirirlos antes de empezar el desarrollo del mismo.  
- El tema debe expresar claramente en que consiste el estudio o investigación y debe ser breve.  
- Lo que anuncia el nombre del informe tiene que corresponderse con lo que se va a desarrollar en la misma.
# Tema seleccionado:
## Mitigación de la Dependencia en Servicios Externos: Un Desafío Contemporáneo en Privacidad y Soberanía Tecnológica
### Planteamiento de Problema:
En el entorno tecnológico actual, el uso de servicios de terceros de acceso gratuito se ha convertido en una práctica predominante tanto para individuos como para organizaciones, incluyendo pequeñas y medianas empresas (PyMEs) y entidades gubernamentales. La aparente gratuidad de estas soluciones ofrecidas por megacorporaciones tecnologicas, resulta atractiva debido a su facilidad de adopcion, mantenimiento delegado y escalabilidad immediata.

Sin embargo, establecer esta dependencia en la infraestructura tecnologica de nuestras operaciones conlleva riesgos significativos y costos sutiles, no inmediatamente aparentes, en terminos de privacidad, seguridad y soberania tecnologica. La centralizacion del almacenamiento y procesamiento de los datos en plataformas externas expone a nuestras organizaciones a vulnerabilidades, derivadas de politicas de uso ambiguas y arbitrarias, accesos no autorizados, incumplimiento normativo y posibles interrupciones en la disponibilidad del servicio

Este estudio tiene como objetivo analizar los riesgos inherentes a la dependencia de servicios externos y evaluar estrategias para la adopción de infraestructuras autogestionadas como una alternativa viable y sostenible. Se propone explorar el impacto económico y operativo de esta transición, así como los desafíos técnicos y organizacionales asociados a su implementación. A través de un enfoque comparativo, se analizara un caso de éxito en el sector clave PyMEs, cuyos recursos se ven en su punto mas limitado, garantizando la escalabilidad a modelos menos restringidos.  Tambien se ofrecerán modelos de mitigación que optimicen la relación costo-beneficio en distintos contextos.
### **Recursos y Enfoque Metodológico**

Para abordar esta problemática, se recurrirá a un enfoque multidisciplinario que combine análisis de riesgo, evaluación de modelos de infraestructura autogestionada y estudios de caso en diferentes sectores. Se considerarán fuentes académicas, informes técnicos y normativas de referencia, tales como:

- **Marco normativo y regulaciones**: GDPR (Reglamento General de Protección de Datos), NIST Cybersecurity Framework, ISO/IEC 27001.
- **Modelos de infraestructura descentralizada**: Soluciones de auto-hosting como Nextcloud, Matrix, self-hosted CI/CD, Kubernetes on-premise.
- **Casos de estudio**: Implementaciones en sectores gubernamentales, PyMEs y comunidades de software libre.
- **Evaluaciones económicas y operativas**: Comparaciones entre costos de dependencia en servicios externos y costos de inversión en soluciones autogestionadas.

Este trabajo busca contribuir a la discusión sobre la sostenibilidad tecnológica y la privacidad en un entorno digital cada vez más dependiente de infraestructuras centralizadas, proponiendo estrategias que permitan a las organizaciones recuperar el control sobre su información y operaciones.


# Otros Candidatos 
## Ciberseguridad: Implementación y Análisis de un Honeypot en la Infraestructura Dominicana
### Planteamiento del Problema

En el panorama actual de la ciberseguridad, los activos digitales expuestos a Internet están en constante riesgo de ser atacados por una amplia gama de actores maliciosos, que van desde grupos patrocinados por Estados (State-Sponsored Actors) hasta ciberdelincuentes independientes. La creciente sofisticación de las amenazas cibernéticas requiere un enfoque proactivo en la detección y análisis de patrones de ataque para fortalecer las estrategias de defensa.

La recopilación de inteligencia de amenazas (Threat Intelligence) es un componente esencial en las operaciones de ciberseguridad defensiva. La monitorización y análisis de ataques en un entorno controlado permite obtener un **snapshot** del panorama actual de amenazas, proporcionando información crítica para la mitigación de riesgos. Estudios históricos sobre seguridad operacional (OPSEC), como el proyecto **Purple Dragon**, han demostrado la relevancia de la inteligencia de amenazas en la protección de infraestructuras críticas y operaciones militares (Departamento de Defensa de EE.UU., 1973). Además, documentos como el **"Compendio de Buenas Prácticas para Proteger las Infraestructuras Críticas Frente a los Atentados Terroristas"** de las **Naciones Unidas** (2018) enfatizan la necesidad de estrategias preventivas y colaborativas para salvaguardar instalaciones esenciales. Asimismo, el informe **"La Protección de la Fuerza ante las Nuevas Amenazas Tecnológicas"** del **Estado Mayor de la Defensa de España (2022)** analiza cómo el avance tecnológico ha incrementado la vulnerabilidad de las infraestructuras críticas, subrayando la importancia de una gestión de riesgos efectiva y la implementación de medidas de protección adaptadas a las amena++zas emergentes.

Este estudio propone la implementación de un **honeypot** en una dirección IP dominicana para capturar, analizar y clasificar patrones de ataque en el contexto local. Se busca comprender las tácticas, técnicas y procedimientos (TTPs) utilizados por los actores maliciosos que operan en la región y evaluar la viabilidad de estos sistemas como mecanismos efectivos de inteligencia de amenazas para la comunidad de ciberseguridad en República Dominicana.

### Recursos y Enfoque Metodológico

Para llevar a cabo esta investigación, se desplegará un servidor honeypot con servicios cuidadosamente expuestos para atraer intentos de intrusión, permitiendo la captura y análisis de ataques en múltiples capas:

1. **Networking**: Monitorización del tráfico con herramientas como Suricata y Wireshark.
2. **Administración de Sistemas**: Uso de logging avanzado con ELK Stack (Elasticsearch, Logstash, Kibana).
3. **Análisis de Amenazas**: Implementación de herramientas como Cowrie y Dionaea para registrar interacciones y detectar patrones de ataque.
4. **Clasificación de Amenazas**: Uso de frameworks como MITRE ATT&CK para categorizar las TTPs identificadas.

### Recursos Claves y Referencias

- **Marco de Inteligencia de Amenazas**: MITRE ATT&CK, Cyber Kill Chain, NIST Special Publication 800-150.
- **Investigaciones en OPSEC y Threat Intelligence**: DoD Purple Dragon (1973), NIST Cyber Threat Intelligence Guide.
- **Herramientas de Honeypots**: Cowrie, Kippo, T-Pot, MHN (Modern Honey Network).
- **Análisis de tráfico y respuesta a incidentes**: Suricata, Zeek (Bro), Wireshark.
- **Referencias regionales**: Reportes de amenazas cibernéticas en América Latina y el Caribe (OEA, 2023).

Este estudio no solo proporcionará una visión detallada del panorama de amenazas cibernéticas en República Dominicana, sino que también contribuirá al desarrollo de estrategias de defensa adaptadas a las particularidades del entorno local.

## El impacto del uso de la realidad virtual en los exámenes de conducción en la República Dominicana.
Haciendo uso de datos de accidentes viales públicos de antes y después de implementarse.
## Sistema de analisis de datos en tiempo real para redes sociales
Implica un proyecto de scraping avanzado en multiples redes sociales principales. Conocimiento de bypass a medidas antiscraping, y otros mecanismos. Compilacion de la data en bases de datos y desarrollo de una aplicacion web para visualizar la data.

## Optimizacion de redes 5G usando inteligencia artificial
### 🤷