# Reconocimiento-de-partes-y-funcionamiento-de-una-maquina-de-anestesia

Alissia Montealegre Quintero. 
Raul Alexander Peñuela Jimenez.
Silvia Lorena Vargas Rueda.

Instrumentación Biomédica y Biosensores  
Facultad de Ingeniería, Universidad Militar Nueva Granada, VII Semestre  

## Resumen

En esta práctica de laboratorio se realizó el reconocimiento de los componentes y el funcionamiento de la máquina de anestesia Mindray WATO EX-20, con el propósito de comprender sus principales subsistemas y las condiciones necesarias para su operación. Se llevó a cabo una revisión documental del manual del fabricante y de fuentes bibliográficas relacionadas con los tipos de anestesia, el suministro de gases, el sistema respiratorio y la ventilación mecánica. Asimismo, se reconocieron los espacios y componentes principales del equipo, incluyendo la ubicación destinada al vaporizador, la válvula APL, el recipiente absorbente de CO₂ y el fuelle; se analizaron las alarmas técnicas descritas en el manual para reconocer las posibles causas de falla. Los resultados permitieron establecer que las situaciones anormales pueden estar relacionadas con conexiones inadecuadas, fugas en el circuito respiratorio, problemas de calibración de los sensores y alteraciones en el suministro de gases o energía eléctrica. Finalmente, se reconoció la importancia de las verificaciones previas y del mantenimiento preventivo para favorecer el funcionamiento adecuado y seguro del equipo.

**Palabras clave:** máquina de anestesia, WATO EX-20, ventilación mecánica, sistema respiratorio, alarmas técnicas.

---

## I. Introducción

La anestesia constituye un elemento fundamental en la atención quirúrgica, ya que permite realizar procedimientos médicos mediante el control de la sensibilidad dolorosa y, dependiendo de la técnica empleada, del estado de conciencia y de la respuesta motora del paciente. A lo largo de su evolución, las técnicas anestésicas han incorporado diferentes medicamentos y métodos de administración que han permitido ampliar las posibilidades de intervención y mejorar las condiciones en las que se realizan los procedimientos quirúrgicos. Entre estas técnicas se encuentra la anestesia general, que produce una pérdida reversible de la conciencia y de la percepción del dolor, y que puede administrarse mediante agentes intravenosos, inhalatorios o una combinación de ambos [1].

Para la administración de anestesia general por vía inhalatoria se utilizan equipos especializados denominados máquinas o estaciones de anestesia, cuya función es suministrar gases medicinales y agentes anestésicos de manera controlada, además de proporcionar soporte ventilatorio durante el procedimiento. Estos equipos integran diferentes sistemas que trabajan conjuntamente para garantizar el suministro de la mezcla gaseosa, facilitar el intercambio respiratorio y mantener condiciones de seguridad para el paciente. De acuerdo con Vandroux, Beaulieu y Nathan-Denizot [2], una estación de anestesia está constituida por un sistema de suministro de gases frescos, circuitos respiratorios, ventilador, dispositivos de administración de agentes anestésicos, sistemas de absorción de dióxido de carbono y elementos de monitorización y alarma. La integración de estos componentes permite controlar diferentes condiciones de funcionamiento y responder ante posibles alteraciones durante la administración de anestesia.

Uno de los aspectos más importantes de estos equipos es el control de la ventilación, debido a que durante la anestesia general puede ser necesario proporcionar respiración asistida o controlada para mantener una adecuada oxigenación y eliminación de dióxido de carbono. La ventilación mecánica se fundamenta en la generación de diferencias de presión que permiten movilizar un volumen de gas hacia los pulmones y posteriormente facilitar su salida durante la espiración. Para ello, los ventiladores utilizan diferentes modalidades de funcionamiento, entre las que se encuentran la ventilación controlada por volumen y la ventilación controlada por presión. Como explican Ortiz y colaboradores [3], la selección y programación de estas modalidades depende de variables como la presión, el flujo, el volumen corriente y los tiempos del ciclo respiratorio, las cuales permiten evaluar y controlar el comportamiento del sistema ventilatorio.

Desde la perspectiva de la ingeniería biomédica, las máquinas de anestesia representan sistemas de instrumentación complejos, debido a la integración de componentes mecánicos, neumáticos, electrónicos y de control. Su funcionamiento requiere que los diferentes subsistemas operen de manera coordinada, ya que una alteración en el suministro de gases, la ventilación o los mecanismos de seguridad puede afectar directamente las condiciones del paciente. Por esta razón, además de comprender su funcionamiento, es necesario reconocer la importancia de las pruebas de verificación, las alarmas, el mantenimiento preventivo y los procedimientos de limpieza y desinfección. Estas actividades permiten identificar posibles fallas, conservar las condiciones de operación del equipo y reducir los riesgos asociados con su utilización en ambientes clínicos.

En este contexto, la presente práctica se centra en el reconocimiento de las partes y el funcionamiento de la máquina de anestesia Mindray WATO EX-20, un equipo destinado a proporcionar anestesia respiratoria durante procedimientos quirúrgicos. Según el manual del fabricante, está constituido por una unidad principal, un ventilador anestésico, un conjunto de medidores de flujo, una unidad de vaporización y un sistema respiratorio. Asimismo, dispone de modalidades de ventilación controlada por volumen (VCV) y controlada por presión (PCV), además de funciones como la compensación de fugas, la presión positiva al final de la espiración (PEEP), las pruebas automáticas de fugas y el almacenamiento de eventos de alarma [4]. Estas características permiten estudiar la relación entre los diferentes sistemas que conforman el equipo y comprender su participación en la administración de anestesia.

Por lo anterior, el desarrollo de esta práctica permite relacionar los fundamentos de anestesiología y ventilación mecánica con el funcionamiento de un equipo biomédico utilizado en entornos quirúrgicos. El reconocimiento de sus componentes, la comprensión de sus principios de operación y la identificación de los procedimientos básicos de mantenimiento y seguridad contribuyen a fortalecer las competencias necesarias para la evaluación y gestión de tecnología biomédica, teniendo en cuenta que el correcto funcionamiento de estos dispositivos es indispensable para su utilización segura y confiable en la atención de los pacientes.

---

## II. Marco teórico

### 2.1. Anestesia y sus principales tipos

La anestesia es un procedimiento médico que permite controlar la percepción del dolor y otras respuestas del organismo durante una intervención quirúrgica o procedimiento clínico. Su administración depende de las características del paciente, el tipo de intervención y el efecto que se necesita conseguir. De acuerdo con el alcance de su acción, se reconocen tres modalidades principales: anestesia local, regional y general [1].

- **Anestesia local:** consiste en la administración de un anestésico directamente sobre una zona específica del cuerpo para bloquear temporalmente la transmisión de los impulsos nerviosos relacionados con el dolor. El paciente permanece consciente y la pérdida de sensibilidad se limita al área tratada. Se utiliza principalmente en procedimientos menores, como suturas, intervenciones odontológicas y cirugías.
- **Anestesia regional:** produce la pérdida temporal de sensibilidad en una región más amplia del cuerpo mediante el bloqueo de los nervios que transmiten las señales sensitivas. Entre sus técnicas se encuentran la anestesia raquídea, epidural y los bloqueos de nervios periféricos. A diferencia de la anestesia local, su efecto comprende una zona anatómica más extensa y puede utilizarse en procedimientos quirúrgicos de mayor complejidad.
- **Anestesia general:** produce un estado reversible de inconsciencia acompañado de la pérdida de percepción del dolor y, dependiendo de los medicamentos utilizados, de la disminución o supresión de los movimientos y reflejos del paciente. Puede administrarse mediante medicamentos intravenosos, agentes inhalatorios o la combinación de ambos. Durante su aplicación se requiere supervisar las funciones respiratorias y cardiovasculares, por lo que las máquinas de anestesia cumplen un papel importante en el suministro de gases y el soporte ventilatorio [1].

### 2.2. Máquina de anestesia

La máquina de anestesia es un equipo biomédico que integra diferentes sistemas destinados a suministrar gases medicinales, administrar agentes anestésicos y proporcionar soporte respiratorio durante los procedimientos quirúrgicos. Su funcionamiento depende de la interacción entre los sistemas de suministro de gases, control de flujo, vaporización, ventilación y monitorización. Estos componentes permiten regular las condiciones de administración de la mezcla gaseosa y supervisar el comportamiento del sistema respiratorio [2].

Una estación de anestesia convencional puede dividirse en los siguientes subsistemas:

- **Sistema de suministro de gases:** recibe los gases medicinales provenientes de cilindros o redes centrales y permite regular su presión para el funcionamiento del equipo.
- **Sistema de control de flujo:** regula la cantidad de cada gas que ingresa al circuito, permitiendo establecer la composición y el caudal de la mezcla.
- **Sistema de vaporización:** incorpora el agente anestésico inhalatorio a la mezcla de gases en una concentración determinada.
- **Sistema respiratorio:** conduce los gases entre la máquina y el paciente, permitiendo los procesos de inspiración y espiración.
- **Sistema de ventilación:** proporciona el movimiento de gases necesario para mantener el soporte respiratorio.
- **Sistema de monitorización y alarmas:** permite supervisar variables relacionadas con la ventilación y detectar condiciones que puedan comprometer el funcionamiento del equipo.

La integración de estos subsistemas permite que la máquina funcione como una unidad, por lo que una alteración en cualquiera de ellos puede afectar el suministro de gases o la ventilación del paciente [2].

### 2.3. Gases medicinales utilizados en las máquinas de anestesia

Las máquinas de anestesia utilizan diferentes gases medicinales para preparar la mezcla que será administrada al paciente. Entre los más comunes se encuentran el oxígeno, el aire medicinal y el óxido nitroso. Cada uno cumple una función específica dentro del proceso de anestesia y su suministro debe mantenerse bajo condiciones controladas.

- **Oxígeno (O₂):** es indispensable para mantener el aporte de oxígeno necesario para los tejidos y evitar condiciones de hipoxia. Se utiliza como componente principal de la mezcla respiratoria y permite establecer la concentración inspirada de oxígeno que requiere el paciente.
- **Aire medicinal:** corresponde a una mezcla de gases, principalmente nitrógeno y oxígeno, utilizada para complementar el suministro de oxígeno y ajustar la concentración de este último dentro de la mezcla respiratoria. Su utilización permite modificar la composición del gas fresco sin depender exclusivamente del oxígeno puro.
- **Óxido nitroso (N₂O):** es un gas con propiedades analgésicas y anestésicas que puede utilizarse como complemento de otros agentes anestésicos. Su administración debe controlarse junto con la concentración de oxígeno para evitar mezclas con una proporción insuficiente de este último.

Los gases pueden llegar al equipo mediante una red central de distribución o a través de cilindros conectados directamente a la máquina. En los sistemas de cilindros, el gas se encuentra almacenado a alta presión y requiere mecanismos de regulación antes de ingresar a los circuitos internos. El sistema de alta presión comprende los elementos encargados de recibir y reducir la presión del gas, mientras que el sistema de baja presión participa en su regulación y conducción hacia los medidores de flujo y la salida de gas fresco. Esta organización permite controlar el suministro antes de que la mezcla llegue al circuito respiratorio [2].

La disposición de estos sistemas se representa en el esquema general de una estación de anestesia presentado por Vandroux y colaboradores, donde se identifican las entradas de gases, los reguladores, los medidores de flujo, los vaporizadores y la salida de gas fresco [2].

En la configuración de la máquina Mindray WATO EX-20, los gases que se incorporan a través del sistema de alta presión son aquellos almacenados en cilindros de respaldo conectados directamente al equipo, típicamente oxígeno ($O_2$) y óxido nitroso ($N_2O$) [4] (o aire medicinal en configuraciones con cilindro auxiliar). Estos cilindros almacenan el gas a presiones elevadas (alrededor de 2000 psi o 13.8 MPa para el $O_2$ y 745 psi o 5.1 MPa para el $N_2O$), por lo que atraviesan válvulas antirretorno, filtros y reguladores de presión primaria que reducen la presión antes de ingresar al sistema de control de flujo [2], [4]. Por el contrario, el suministro proveniente de la red central hospitalaria (habitualmente oxígeno, aire medicinal y óxido nitroso) ingresa directamente a través del sistema de presión intermedia o de tuberías (entre 40 y 60 psi / 280 a 415 kPa) [4].

### 2.4. Sistema de respiración de la máquina de anestesia

El sistema de respiración es el conjunto de componentes encargados de conducir la mezcla de gases entre la máquina de anestesia y el paciente, permitiendo la entrada de gas durante la inspiración y la salida durante la espiración. Además, en los sistemas circulares, permite recuperar parte de los gases exhalados para reutilizarlos después de eliminar el dióxido de carbono. Esto contribuye a disminuir el consumo de gases medicinales y agentes anestésicos [2].

Entre sus principales componentes se encuentran:

- **Tubos respiratorios corrugados:** permiten transportar los gases entre la máquina y el paciente. Su flexibilidad facilita la conexión y adaptación del circuito.
- **Pieza en Y:** conecta las ramas inspiratoria y espiratoria con el dispositivo de vía aérea del paciente.
- **Válvulas unidireccionales:** controlan el sentido de circulación de los gases, evitando que el flujo se desplace en dirección contraria a la establecida.
- **Bolsa reservorio:** almacena temporalmente los gases del circuito y permite la ventilación manual, además de facilitar la observación de los movimientos respiratorios.
- **Válvula APL:** regula la presión del circuito durante la ventilación manual y permite liberar el exceso de gas cuando se alcanza el límite de presión establecido.
- **Absorbedor de CO₂:** contiene un material absorbente que retira el dióxido de carbono de los gases exhalados, permitiendo su reutilización dentro del circuito.
- **Fuelle:** participa en la ventilación mecánica mediante el desplazamiento de su estructura, permitiendo movilizar los gases hacia el paciente durante la inspiración.

El funcionamiento coordinado de estos elementos permite mantener la circulación de los gases y controlar las condiciones de presión dentro del circuito respiratorio [2].

#### Limpieza y esterilización del sistema respiratorio

Debido a que los componentes del sistema respiratorio entran en contacto con las secreciones y gases exhalados del paciente, deben someterse a protocolos estrictos de desinfección para evitar la contaminación cruzada [4]. De acuerdo con las especificaciones del manual de usuario de la Mindray WATO EX-20, los componentes que sí pueden esterilizarse en autoclave a vapor (hasta una temperatura máxima de 134 °C) incluyen: el bloque principal del circuito respiratorio, el fuelle de silicona, la campana o cubierta del fuelle, el recipiente absorbente de $CO_2$ (vacío y sin cal sodada), las válvulas unidireccionales (inspiratoria y espiratoria) junto con sus cubiertas transparentes, y los tubos corrugados o piezas en Y reutilizables diseñados para alta temperatura [4]. Por el contrario, elementos sensibles como los sensores de flujo, el sensor de $O_2$ y el manómetro de presión de vía aérea no deben someterse a autoclave, requiriendo métodos de desinfección química o limpieza superficial según corresponda [4].

### 2.5. Ventilación mecánica en las máquinas de anestesia

La ventilación mecánica es un procedimiento mediante el cual un equipo proporciona soporte al proceso respiratorio, facilitando el movimiento de aire hacia los pulmones y su posterior salida. Su objetivo es contribuir al intercambio gaseoso mediante el control de variables como el volumen corriente, la presión, el flujo y la frecuencia respiratoria [3].

El ciclo ventilatorio comprende dos fases principales:

- **Inspiración:** corresponde a la entrada de gas hacia los pulmones, generada mediante un gradiente de presión que permite movilizar el volumen de gas establecido.
- **Espiración:** consiste en la salida del gas desde los pulmones hacia el circuito respiratorio, generalmente como resultado de la retracción elástica pulmonar.

Durante este proceso, el ventilador controla diferentes parámetros que permiten ajustar la ventilación de acuerdo con las condiciones del paciente. Entre ellos se encuentran el volumen corriente, la presión inspiratoria, la frecuencia respiratoria, la relación inspiración-espiración y la presión positiva al final de la espiración (PEEP) [3].

#### 2.5.1. Modalidades de ventilación

Las modalidades de ventilación mecánica pueden clasificarse según la variable que controla la administración del gas. Entre las más utilizadas se encuentran:

- **Ventilación controlada por volumen (VCV):** el ventilador suministra un volumen corriente previamente establecido durante cada ciclo inspiratorio. La presión generada en las vías respiratorias puede variar dependiendo de la distensibilidad pulmonar y la resistencia de las vías aéreas.
- **Ventilación controlada por presión (PCV):** el ventilador establece una presión inspiratoria determinada y regula el flujo de gas para mantenerla durante el tiempo inspiratorio. En este caso, el volumen corriente obtenido depende de las características mecánicas del sistema respiratorio del paciente.

Estas modalidades permiten diferentes estrategias de soporte ventilatorio y requieren la supervisión de sus parámetros para mantener condiciones adecuadas de funcionamiento [3].

En la máquina Mindray WATO EX-20, el fabricante documenta las modalidades VCV y PCV como opciones de ventilación mecánica. También contempla la ventilación manual, en la cual el operador utiliza la bolsa reservorio y la válvula APL para controlar la ventilación y limitar la presión del circuito [4].

#### 2.5.2. Parámetros de ventilación

| Parámetro | Descripción |
|---|---|
| Volumen corriente (VC) | Cantidad de gas suministrada o movilizada durante una respiración. |
| Frecuencia respiratoria | Número de ciclos respiratorios realizados por minuto. |
| Presión inspiratoria | Presión aplicada durante la fase inspiratoria. |
| PEEP | Presión positiva que se mantiene al finalizar la espiración. |
| Relación I:E | Relación entre el tiempo de inspiración y el tiempo de espiración. |
| Tiempo inspiratorio | Duración de la fase de entrada de gas. |
| FiO₂ | Fracción inspirada de oxígeno presente en la mezcla gaseosa. |

El seguimiento de estas variables permite evaluar el comportamiento del ventilador y reconocer posibles alteraciones en el proceso respiratorio. Su interpretación debe considerar las condiciones fisiológicas del paciente y las características del circuito utilizado [4].

#### 2.5.3. Pausa inspiratoria

La pausa inspiratoria es un intervalo que se establece al finalizar la entrada de gas y antes de comenzar la espiración. Durante este periodo se interrumpe temporalmente el flujo, permitiendo que las presiones del circuito y de los alvéolos tiendan a equilibrarse. Esta condición permite obtener la presión de meseta, una variable utilizada para evaluar el comportamiento mecánico del sistema respiratorio [3].

En la máquina WATO EX-20, el manual identifica el parámetro TIP:TI, correspondiente a la pausa inspiratoria expresada como proporción del tiempo inspiratorio. Su configuración se contempla dentro de los parámetros de ventilación controlada por volumen (VCV) [4].

#### 2.5.4. Submenús de configuración del ventilador
La interfaz de usuario del ventilador de la Mindray WATO EX-20 organiza sus funciones operativas y técnicas mediante una estructura de menú principal desplegable dividida en cuatro submenús fundamentales [4]:
- **Configuración de ventilación (Ventilación / Ajustes):** Permite seleccionar el modo ventilatorio (VCV, PCV o Manual/Espontáneo) y programar los parámetros respiratorios del paciente ($V_T$, frecuencia respiratoria, relación I:E, PEEP y presión límite) [4]. Es dentro de este submenú, específicamente al configurar el modo controlado por volumen (VCV), donde se habilita y ajusta la pausa inspiratoria mediante el parámetro TIP:TI [4].
- **Configuración de alarmas (Alarmas):** Permite definir los límites superior e inferior de seguridad para variables críticas como la presión en la vía aérea ($P_{aw}$), el volumen minuto ($MV$), el volumen corriente ($V_T$) y la concentración inspirada de oxígeno ($FiO_2$), así como consultar el historial de eventos [4].
- **Configuración del sistema (Sistema):** Gestiona las preferencias generales de la interfaz, como el brillo de pantalla, volumen de alarmas audibles, unidades de medida ((cmH$_2$O, hPa o mbar)), idioma, fecha y hora [4].
- **Mantenimiento y calibración (Mantenimiento):** Agrupa las rutinas técnicas de verificación previa al uso, como la prueba de fugas del circuito, la calibración del sensor de flujo y la calibración del sensor de oxígeno (21% y 100%) [4].

### 2.6. Componentes principales de la máquina de anestesia WATO EX-20

La máquina de anestesia Mindray WATO EX-20 incorpora diferentes elementos que intervienen en la administración de anestesia y el soporte ventilatorio. Entre los componentes que se destacan para el desarrollo de esta práctica se encuentran el vaporizador, la válvula APL, el recipiente absorbente de CO₂ y el fuelle [4].

- **Vaporizador:** es el dispositivo encargado de transformar un agente anestésico líquido en vapor e incorporarlo a la mezcla de gases que se administra al paciente. Su funcionamiento permite regular la concentración del anestésico inhalatorio mediante un control de ajuste. La concentración seleccionada determina la cantidad de agente anestésico que se incorpora al flujo de gas fresco. El vaporizador debe utilizarse con el agente para el cual fue diseñado, debido a que sus características físicas influyen en la precisión de la vaporización [4].
- **Válvula APL (Adjustable Pressure Limiting):** es una válvula limitadora de presión ajustable que regula la presión máxima dentro del circuito respiratorio durante la ventilación manual. Cuando la presión alcanza el valor establecido, permite liberar el exceso de gas hacia el sistema de evacuación. Su función es evitar que se acumulen presiones excesivas dentro del circuito y facilitar el control de la ventilación manual. En la ventilación mecánica, el control de presión se realiza mediante los mecanismos propios del ventilador [4].
- **Recipiente absorbente de CO₂:** es el componente que contiene el material encargado de absorber el dióxido de carbono presente en los gases espirados. Generalmente utiliza cal sodada, un material que reacciona químicamente con el CO₂ y permite retirar este compuesto antes de que los gases sean nuevamente inhalados. Su funcionamiento es importante en los circuitos circulares, ya que permite reutilizar parte de la mezcla respiratoria y disminuir el consumo de gases frescos. El material absorbente debe reemplazarse cuando pierde su capacidad de absorción, siguiendo los procedimientos e indicaciones del fabricante [4].
- **Fuelle:** es un elemento del sistema de ventilación mecánica encargado de movilizar los gases hacia el paciente mediante su expansión y compresión. En el equipo WATO EX-20, el conjunto del fuelle forma parte del sistema respiratorio y participa en la administración controlada del volumen de gas durante la ventilación mecánica. Su funcionamiento debe verificarse para identificar posibles fugas o alteraciones en su desplazamiento, debido a que estas pueden afectar la cantidad de gas suministrada al paciente [4].

### 2.7. Sistemas de seguridad y monitorización

Las máquinas de anestesia incorporan mecanismos de seguridad destinados a detectar alteraciones en el suministro de gases, la ventilación y las condiciones de funcionamiento del equipo. Estos mecanismos incluyen alarmas, sensores, válvulas de protección y procedimientos de verificación que permiten identificar situaciones que requieren intervención del personal encargado.

En la WATO EX-20 se incluyen funciones como la compensación de fugas del sistema respiratorio, la compensación automática de la distensibilidad del circuito, el control electrónico de PEEP y el corte automático del suministro de óxido nitroso cuando se detecta una presión insuficiente de oxígeno. También dispone de almacenamiento y revisión de eventos de alarma, lo que permite consultar las condiciones que han generado alertas durante el funcionamiento [4].

La monitorización permite observar variables como la concentración inspirada de oxígeno, la presión de las vías respiratorias, el volumen corriente y la frecuencia respiratoria. Estos parámetros proporcionan información sobre el comportamiento del sistema ventilatorio y permiten identificar desviaciones respecto a los límites establecidos [3]. Su supervisión es especialmente importante durante la anestesia general, debido a que las alteraciones respiratorias pueden comprometer la oxigenación del paciente [4].

### 2.8. Mantenimiento y pruebas de funcionamiento

El mantenimiento de una máquina de anestesia comprende las actividades de inspección, limpieza, verificación y revisión técnica necesarias para conservar sus condiciones de funcionamiento. Estas actividades permiten identificar daños, fugas, obstrucciones o fallas en los componentes que participan en el suministro de gases y la ventilación.

El fabricante de la WATO EX-20 establece la realización de pruebas de funcionamiento antes de cada paciente y después de determinados procedimientos de mantenimiento o reparación. Entre las verificaciones contempladas se encuentran las pruebas de suministro de gases, revisión de cilindros, comprobación del sistema de control de flujo, inspección del vaporizador, pruebas de alarmas y evaluación del sistema respiratorio [4].

Estas comprobaciones son necesarias para verificar que el equipo se encuentre en condiciones adecuadas antes de su utilización. Asimismo, permiten reconocer posibles fallas en los diferentes subsistemas y evitar que un dispositivo con resultados de prueba no satisfactorios sea utilizado con un paciente.

### 2.9. Protocolos operativos y pruebas de seguridad de la WATO EX-20
Para garantizar la seguridad clínica durante la anestesia, el fabricante establece procedimientos específicos de actuación y verificación técnica [4]:
-**Actuación ante alarma de "Batería en uso":**  Si el equipo muestra este mensaje mientras un paciente se encuentra conectado, indica la pérdida de alimentación de la red eléctrica alterna (AC) [4]. El operador debe verificar inmediatamente la conexión del cable de alimentación a la toma mural, comprobar el estado de los disyuntores o fusibles y supervisar el indicador de carga restante de la batería (cuya autonomía nominal con batería nueva y cargada es de aproximadamente 90 minutos) [4]. Si el suministro eléctrico no se restablece antes de que la batería alcance un nivel crítico, se debe preparar la transición a ventilación manual mediante la bolsa reservorio y disponer de un sistema alternativo de ventilación [4].
**Frecuencia de reemplazo del absorbente de $CO_2$:** La cal sodada contenida en el recipiente absorbente debe sustituirse cuando pierda su capacidad química de neutralización [4]. En la práctica clínica, esto se determina mediante tres criterios: el cambio de color del indicador químico del absorbente (generalmente de blanco a violeta o azul, según el fabricante del reactivo), la detección de dióxido de carbono inspirado ($FiCO_2 > 0\text{–}2\text{ mmHg}$) en el capnógrafo, o el cumplimiento de las horas máximas de uso continuo recomendadas por el fabricante [4].
- **rueba de fuga en el cilindro de alta presión:** Para verificar la estanqueidad del sistema de cilindros, se deben apagar los controles de flujo (flujómetros cerrados) y abrir completamente la válvula del cilindro correspondiente hasta registrar la presión en el manómetro [4]. Posteriormente, se cierra la válvula del cilindro y se observa la lectura del manómetro durante un minuto; si la presión desciende de forma apreciable (típicamente más de 50 psi o 345 kPa), existe una fuga en el yugo, la junta (arandela Bodok) o el regulador de alta presión que debe corregirse antes de usar el equipo [4].
- **Influencia del sensor de $O_2$ en la prueba del sistema de control de flujo:** Contar o no con el sensor de oxígeno influye directamente en el alcance de la verificación [4]. Durante la prueba de control de flujo y del sistema de protección contra mezclas hipóxicas (sistema de enlace proporcional), el sensor de $O_2$ permite confirmar que la concentración real de oxígeno entregada al circuito nunca descienda por debajo del umbral seguro (25%) al abrir el óxido nitroso [4]. Si el equipo no cuenta con el sensor de $O_2$ instalado o este se encuentra agotado, es posible comprobar mecánicamente el desplazamiento de los flotadores y la ausencia de fugas en los flujómetros, pero se pierde la verificación electrónica de la fracción inspirada de oxígeno ($FiO_2$) [4].
- **Función del sistema de presión negativa (AGSS):** El Sistema de Evacuación de Gases Anestésicos (AGSS, por sus siglas en inglés) utiliza una fuente de presión negativa o vacío controlado para recolectar y expulsar hacia el exterior del quirófano los gases exhalados excedentes liberados a través de la válvula APL o la válvula de descarga del ventilador [4]. Su objetivo principal es evitar la contaminación ambiental de la sala de cirugía y proteger al personal médico de la exposición crónica a agentes anestésicos volátiles y óxido nitroso [4].

---

## III. Metodología

La práctica se desarrolló mediante una metodología demostrativa y de revisión documental, orientada al reconocimiento de los componentes, principios de funcionamiento y procedimientos básicos de mantenimiento de la máquina de anestesia Mindray WATO EX-20. Para ello, se tomó como referencia la explicación de los diferentes subsistemas del equipo, la identificación de sus componentes principales y la consulta del manual de usuario proporcionado por el fabricante.

<p align="center">
<img width="366" height="383" alt="MaqAne" src="https://github.com/user-attachments/assets/1e89d16a-882d-47c6-81e4-e0bbe456f459" />
</p>

<p align="center">
  <em>Figura 1. Máquina de anestesia Mindray WATO EX-20. Tomado de: [4].</em>
</p>


El desarrollo de la actividad se organizó en las siguientes etapas:

**A. Revisión de información técnica y fundamentos teóricos.**

Inicialmente, se realizó una revisión bibliográfica sobre los principios de funcionamiento de las máquinas de anestesia. Se consultaron documentos técnicos y artículos científicos relacionados con los tipos de anestesia, los gases medicinales utilizados, los sistemas de respiración y las modalidades de ventilación mecánica. Adicionalmente, se tomó como referencia el manual de usuario de la Mindray WATO EX-20 para identificar las características particulares del equipo y complementar la información necesaria para el desarrollo de la práctica.

**B. Reconocimiento general de la máquina de anestesia.**

Se abordó la estructura general de la máquina de anestesia WATO EX-20, identificando los principales subsistemas que permiten su funcionamiento. Se consideraron el suministro de gases medicinales, el control de flujo, la unidad de vaporización, el sistema respiratorio, el ventilador y los elementos de monitorización y seguridad. Esta etapa permitió comprender cómo se relacionan los diferentes componentes durante la administración de anestesia y el soporte ventilatorio.

**C. Identificación de los componentes del sistema respiratorio.**

Se estudiaron los elementos que conforman el sistema respiratorio de la máquina, prestando especial atención al vaporizador, la válvula limitadora de presión ajustable (APL), el recipiente absorbente de dióxido de carbono (CO₂) y el fuelle. Para cada componente se revisó su ubicación, función y participación en el proceso de administración de gases y ventilación. En el caso del vaporizador, se identificó el espacio destinado para su instalación, aunque no se encontraba montado durante la práctica.

**D. Revisión de los modos de funcionamiento del ventilador.**

Se consultaron las modalidades de ventilación disponibles en el equipo, particularmente la ventilación controlada por volumen (VCV) y la ventilación controlada por presión (PCV). Se estudiaron sus principios de funcionamiento y los parámetros que intervienen en la programación ventilatoria, como el volumen corriente, la presión inspiratoria, la frecuencia respiratoria y la relación inspiración-espiración. Asimismo, se revisó la función de la pausa inspiratoria y su relación con los parámetros de ventilación.

**E. Consulta de procedimientos de seguridad y mantenimiento.**

Finalmente, se revisaron los procedimientos establecidos por el fabricante para verificar las condiciones de funcionamiento de la máquina de anestesia. Se tuvieron en cuenta las pruebas de suministro de gases, detección de fugas, funcionamiento del sistema respiratorio, revisión de alarmas y condiciones de alimentación eléctrica. También se estudiaron las recomendaciones de mantenimiento preventivo y las medidas de seguridad necesarias para evitar riesgos durante la utilización del equipo.

A partir de estas etapas, se recopiló y organizó la información necesaria para responder las preguntas propuestas en la guía de laboratorio, relacionando los fundamentos teóricos con las características técnicas de la máquina de anestesia WATO EX-20.

## IV. Resultados

Durante la práctica de reconocimiento de la máquina de anestesia Mindray WATO EX-20 se identificaron visualmente algunos de los componentes principales del sistema respiratorio y del suministro de gases. La observación permitió relacionar la disposición física de estos elementos con las funciones descritas en el manual del fabricante.

### 4.1. Identificación de los componentes del sistema respiratorio

<p align="center">
<img width="900" height="1600" alt="Fig_1" src="https://github.com/user-attachments/assets/d99a870b-41ec-4bcb-95b1-a2d8b37a1954" />
</p>

<p align="center">
  <em>Figura 2. Fuelle de ventilación. Tomado de: [elaboración propia].</em>
</p>


En la figura 2 se observa el conjunto del fuelle, ubicado dentro de una cámara transparente que presenta una escala de volumen corriente (VT), graduada desde 300 hasta 1500 mL. Este componente permite observar el desplazamiento del fuelle durante la ventilación mecánica y relacionarlo con el volumen corriente suministrado.

<p align="center">
<img width="900" height="1600" alt="Fig_2" src="https://github.com/user-attachments/assets/1a0ed73b-a32e-4da8-aec4-ac0b6d13a9bc" />
</p>

<p align="center">
  <em>Figura 3. Válvula APL y válvulas unidireccionales del sistema respiratorio. Tomado de: [Elaboración propia]</em>
</p>

En la figura 2 se identifica la válvula limitadora de presión ajustable (APL), cuya perilla presenta una escala expresada en cmH₂O. Su función es regular la presión dentro del circuito respiratorio durante la ventilación manual, permitiendo liberar el exceso de gas cuando se alcanza el límite establecido. También se observaron dos conjuntos de válvulas transparentes correspondientes a las vías inspiratoria y espiratoria, cuya función es dirigir el flujo de gas en el sentido adecuado y evitar su circulación en dirección contraria.

<p align="center">
<img width="900" height="1600" alt="Fig_3" src="https://github.com/user-attachments/assets/fd80e31e-4eda-4a22-91a3-85bf4761308c" />
</p>

<p align="center">
  <em>Figura 4. Recipiente absorbente de CO₂. Tomada de: [Elaboración propia]</em>
</p>

En la figura 4 se observa el recipiente absorbente de dióxido de carbono (CO₂), ubicado en el sistema respiratorio. Este componente contiene el material absorbente que permite retirar el CO₂ del gas exhalado antes de que vuelva a circular por el circuito. En su estructura se observa una indicación de temperatura de 134 °C. Sin embargo, esta señal no permite establecer por sí sola que todas las piezas del recipiente sean compatibles con esterilización en autoclave; esta condición debe verificarse en las indicaciones del fabricante.

### 4.2. Reconocimiento del sistema de suministro de gases

<p align="center">
<img width="900" height="1600" alt="Fig_4" src="https://github.com/user-attachments/assets/563c326d-b7e8-4d53-aad1-62b705707d40" />
</p>

<p align="center">
  <em>Figura 5. Panel frontal de suministro de gases y manómetros de la máquina WATO EX-20. Tomado de: [Elaboración propia]</em>
</p>

En la figura 5 se observa el panel frontal de la máquina, donde se encuentran los flujómetros correspondientes a aire medicinal (AIR), óxido nitroso (N₂O) y oxígeno (O₂). Estos permiten visualizar y regular el flujo de los gases suministrados al sistema de anestesia. En la parte inferior también se identifican los manómetros, que permiten supervisar las presiones de suministro, así como los controles asociados al funcionamiento del equipo.

En cuanto al vaporizador, no fue posible identificarlo durante la práctica, debido a que no se encontraba instalado en el espacio correspondiente de la máquina. Por esta razón, no se realizó una descripción visual de sus características ni de sus mecanismos de regulación. No obstante, se reconoce su importancia dentro del sistema de anestesia, ya que permite incorporar al flujo de gas fresco una concentración controlada del agente anestésico inhalado.

En general, el reconocimiento permitió identificar elementos fundamentales de la máquina WATO EX-20 y relacionar su ubicación con las funciones que cumplen dentro del proceso de suministro de gases y ventilación del paciente.

---

## V. ANÁLISIS DE RESULTADOS

Para el desarrollo de este análisis se tomó como fuente principal el *Manual del usuario de la máquina de anestesia Mindray WATO EX-20*, específicamente el Anexo D, en el cual el fabricante presenta los mensajes de alarma del equipo, sus posibles causas y las acciones recomendadas para cada situación. A partir de esta información se identificaron y organizaron las posibles fallas de los diferentes subsistemas, con el propósito de analizar su funcionamiento y establecer una clasificación según la cantidad de alarmas asociadas [4].

### 5.1. Análisis de las posibles fallas en los subsistemas de la máquina de anestesia

La revisión del manual de usuario de la máquina de anestesia Mindray WATO EX-20 permitió identificar diferentes situaciones que pueden afectar su funcionamiento. Estas se encuentran descritas principalmente en el Anexo D, donde se presentan los mensajes de alarma, sus posibles causas y las acciones recomendadas por el fabricante. A partir de esta información, las fallas se organizaron de acuerdo con el subsistema al que se relacionan, teniendo en cuenta que una misma alarma puede involucrar varios componentes.

**a) Subsistema de ventilación.** Este subsistema concentra una parte importante de las alarmas descritas en el manual, debido a que interviene directamente en el control y suministro de la ventilación al paciente. Entre las fallas identificadas se encuentran los errores de hardware del ventilador, problemas de comunicación entre sus módulos y el sistema principal, así como dificultades en el funcionamiento de las válvulas inspiratoria, PEEP y de seguridad PEEP.

También pueden presentarse errores durante el autotest del ventilador o fallas en el control de las válvulas. Estas situaciones pueden impedir que el equipo regule adecuadamente la presión y el flujo de los gases durante el ciclo respiratorio. Por esta razón, el fabricante contempla el uso de ventilación manual como medida de apoyo ante determinadas alarmas, mientras se verifica la causa del problema y se solicita asistencia técnica cuando corresponde.

**b) Sensores y sistema de monitorización.** Los sensores permiten obtener información sobre las condiciones del sistema respiratorio y la concentración de oxígeno, por lo que su funcionamiento es fundamental para la supervisión de la ventilación. El manual contempla fallas relacionadas con el sensor de oxígeno, el sensor de flujo y el canal de monitorización de presión.

Entre las causas señaladas se encuentran la desconexión de los sensores, errores de calibración, desviaciones entre las mediciones y el funcionamiento de las válvulas, acumulación de agua y daños físicos. También se contempla la falla del proceso de cero automático. Estas condiciones pueden ocasionar mediciones incorrectas o una disminución en la precisión de los parámetros presentados por el equipo. En consecuencia, se requiere verificar las conexiones, revisar el estado de los sensores y realizar los procedimientos de calibración indicados por el fabricante.

**c) Sistema respiratorio.** El sistema respiratorio comprende los componentes encargados de conducir los gases entre la máquina y el paciente. De acuerdo con el manual, pueden presentarse problemas por conexiones incorrectas, desconexión de las tuberías, fugas o instalación inadecuada de algunos elementos.

Entre las alarmas relacionadas se encuentran la presión de las vías aéreas mantenida por encima del límite, la presión inferior a -10 cmH₂O, la presión inspiratoria no alcanzada y el volumen corriente no alcanzado. Estas situaciones pueden estar asociadas con tubos doblados, obstrucciones, fugas o configuraciones inadecuadas de los parámetros ventilatorios. Asimismo, el equipo puede generar una alarma cuando el recipiente del absorbente de CO₂ no está instalado correctamente. Por tanto, el montaje y la revisión de las conexiones del circuito son aspectos importantes para garantizar su funcionamiento.

**d) Sistema eléctrico y de alimentación.** El funcionamiento de la máquina también depende de la disponibilidad de energía eléctrica y del estado de sus baterías. El manual identifica alarmas relacionadas con batería descargada, batería no detectada, baja tensión y fallas de comunicación o autotest del sistema de alimentación.

Otra condición descrita es el aumento de temperatura de la placa de alimentación por encima del límite establecido por el fabricante. Estas situaciones pueden comprometer la continuidad del funcionamiento del equipo, especialmente cuando se presenta una interrupción de la alimentación eléctrica. Por esta razón, el manual indica la necesidad de conectar la máquina a la red eléctrica cuando la batería presenta un nivel bajo y contempla medidas de respaldo para mantener la ventilación del paciente.

**e) Sistema de suministro de gases.** Este subsistema proporciona los gases necesarios para el funcionamiento de la máquina de anestesia. Entre las alarmas identificadas se encuentran la baja presión del gas de la unidad, la presión insuficiente en el suministro de oxígeno y el flujo de gas fresco demasiado alto.

Estas condiciones pueden afectar la disponibilidad y regulación de los gases que recibe el sistema respiratorio. Una presión de suministro insuficiente puede impedir que la máquina trabaje bajo las condiciones requeridas, mientras que un flujo de gas fresco excesivo puede alterar el funcionamiento esperado del circuito. Por ello, es necesario comprobar las conexiones, la disponibilidad de los gases y los valores de flujo establecidos.

**f) Sistema de calentamiento.** El manual también contempla fallas relacionadas con el módulo de calentamiento, entre ellas errores del termistor, de la resistencia calefactora y de comunicación o autotest del módulo. Además, señala que la condensación de vapor en el sensor puede estar relacionada con una de estas fallas. Aunque este sistema no participa directamente en la generación de los ciclos ventilatorios, sus errores pueden activar alarmas y requerir revisión técnica.

**g) Sistema de control auxiliar.** El módulo de control auxiliar puede presentar errores de hardware, fallas de comunicación con el panel de control principal y problemas durante las pruebas de funcionamiento o los procesos de reinicio. El manual describe errores asociados con componentes internos como CPU, RAM, ROM y watchdog. También contempla fallas en la monitorización de presión y en el control de la válvula de seguridad. Estas condiciones pueden afectar la supervisión y el funcionamiento de mecanismos de protección, por lo que el fabricante recomienda reiniciar el equipo o solicitar asistencia técnica si el problema persiste.

Aunque el vaporizador es un componente fundamental para administrar el agente anestésico, las alarmas técnicas del Anexo D revisadas no presentan una categoría con un número equivalente de mensajes específicos para este elemento. Por esta razón, no se le asignó una cantidad de alarmas en el conteo. Esto no significa que esté exento de fallas: su instalación, llenado, selección del agente anestésico y funcionamiento deben realizarse de acuerdo con las indicaciones del fabricante.

### 5.2. Clasificación de los subsistemas según la cantidad de alarmas asociadas

Para establecer un orden de mayor a menor, se realizó un conteo de las entradas de alarmas técnicas presentadas en el apartado D.2 del Anexo D del manual de usuario. Cada mensaje se asignó al subsistema con el que tiene una relación funcional más directa. Cuando una alarma podía involucrar varios componentes, se clasificó según la causa principal descrita por el fabricante, evitando contabilizar en más de una categoría.

**Tabla 1. Clasificación de las alarmas técnicas según el subsistema de la máquina de anestesia Mindray WATO EX-20.**

| Orden | Subsistema | Número de alarmas |
|:---:|---|:---:|
| 1 | Subsistema de ventilación | 18 |
| 2 | Sensores y sistema de monitorización | 9 |
| 3 | Sistema respiratorio | 7 |
| 4 | Sistema de control auxiliar | 7 |
| 5 | Sistema eléctrico y de alimentación | 4 |
| 6 | Sistema de calentamiento | 3 |
| 7 | Sistema de suministro de gases | 3 |
| | **Total de entradas contabilizadas** | **51** |

*Nota: la clasificación se realizó a partir de las alarmas técnicas del apartado D.2 del Anexo D del manual de usuario [4].*

De acuerdo con el conteo, el subsistema de ventilación presenta la mayor cantidad de alarmas asociadas, con 18 entradas. Esto se relaciona con la variedad de componentes y funciones que intervienen en el proceso ventilatorio, como las válvulas, los módulos electrónicos y los mecanismos encargados de regular las condiciones de presión y flujo. En segundo lugar se encuentran los sensores y el sistema de monitorización, con nueve alarmas, lo que evidencia la importancia de mantener estos elementos correctamente conectados, calibrados y en buen estado.

El sistema respiratorio y el módulo de control auxiliar registran siete alarmas cada uno. En el primer caso, las situaciones se relacionan principalmente con conexiones, fugas, obstrucciones y condiciones inadecuadas del circuito. En el segundo, se presentan errores de hardware, comunicación y monitorización. Por su parte, el sistema eléctrico y de alimentación reúne cuatro alarmas, mientras que los sistemas de calentamiento y suministro de gases presentan tres cada uno.

Es importante aclarar que esta clasificación representa la cantidad de mensajes de alarma documentados en el manual y no la frecuencia real con la que se presentan las fallas durante el uso de la máquina. El fabricante no proporciona en este anexo estadísticas de ocurrencia ni probabilidades de falla. Por lo tanto, el orden permite comparar la cantidad de situaciones de alarma contempladas para cada subsistema, pero no afirmar que uno de ellos falle con mayor frecuencia en condiciones clínicas.

El análisis muestra que la máquina de anestesia WATO EX-20 depende de la interacción de varios subsistemas para mantener condiciones adecuadas de ventilación y suministro de gases. Aunque el ventilador reúne la mayor cantidad de alarmas en el apartado estudiado, esto no significa que sea el único elemento crítico. Los sensores, el circuito respiratorio, la alimentación eléctrica y los módulos de control también cumplen funciones necesarias para la operación segura del equipo.

Además, las alarmas permiten identificar condiciones que pueden afectar tanto el funcionamiento como la confiabilidad de la información presentada al usuario. Por ejemplo, una falla del sensor de flujo puede reducir la precisión de las mediciones, mientras que una fuga o una desconexión del circuito puede impedir que se alcance el volumen corriente configurado. De manera similar, una presión insuficiente de oxígeno o una batería descargada puede comprometer la disponibilidad de recursos necesarios para el funcionamiento de la máquina.

En conjunto, estos resultados resaltan la importancia de realizar las verificaciones previas al uso, comprobar el montaje del sistema respiratorio, revisar las conexiones de gases y verificar el estado de los sensores y de la alimentación eléctrica. También permiten comprender por qué las alarmas no deben interpretarse como simples avisos, sino como mecanismos que orientan la identificación de condiciones anormales y la aplicación de las acciones recomendadas por el fabricante.

---

## VI. DISCUSIÓN

### 6.1. ¿Qué tipos de anestésicos son los más usados en cirugía?

Los anestésicos utilizados en cirugía varían según el procedimiento, la región del cuerpo que se va a intervenir, la duración de la operación y las condiciones del paciente. De manera general, se emplean anestésicos locales, regionales y generales. En los procedimientos que requieren anestesia local o regional se utilizan principalmente medicamentos como la lidocaína, bupivacaína, ropivacaína y mepivacaína. Estos fármacos bloquean temporalmente la transmisión de los impulsos nerviosos y permiten disminuir o eliminar la sensibilidad en una zona específica del cuerpo. Por ejemplo, la lidocaína suele emplearse en procedimientos de menor duración, mientras que la bupivacaína y la ropivacaína ofrecen una acción más prolongada, por lo que también pueden utilizarse para el control del dolor después de la cirugía [1].

Por otra parte, en la anestesia general se utilizan diferentes medicamentos para conseguir la pérdida de conciencia, la analgesia, la amnesia y la inmovilidad necesarias durante el procedimiento quirúrgico. Entre los agentes intravenosos se encuentran el propofol, el tiopental y el etomidato. También se emplean las benzodiacepinas como medicamentos complementarios, principalmente por sus efectos sedantes y amnésicos. Asimismo, se utilizan opioides, como el fentanilo y el remifentanilo, para controlar el dolor, y bloqueadores neuromusculares cuando se requiere relajación muscular. En cuanto a los anestésicos inhalatorios, se destaca el sevoflurano, utilizado principalmente para el mantenimiento de la anestesia general [1].

Una de las técnicas utilizadas es la anestesia general balanceada, que combina medicamentos administrados por vía intravenosa con agentes inhalatorios. Esta combinación permite complementar los efectos de los diferentes fármacos y alcanzar los objetivos anestésicos sin depender de dosis elevadas de un solo medicamento. Por lo tanto, la selección de los anestésicos no depende únicamente de cuál sea el más utilizado, sino de las necesidades de cada intervención y de la valoración realizada por el equipo de anestesiología.

### 6.2. ¿Qué diferencias plantea el modelo EX-35 con respecto al EX-20?

La máquina de anestesia Mindray WATO EX-35 presenta características adicionales en comparación con el modelo WATO EX-20, principalmente en la interfaz de usuario, las funciones de monitorización y las opciones de ventilación. Una de las diferencias más visibles es su pantalla táctil de 10,4 pulgadas, mientras que el EX-20 cuenta con una pantalla TFT a color de 7,4 pulgadas. Esta diferencia facilita el acceso a los parámetros y ajustes del equipo, haciendo más sencilla la interacción del personal clínico durante su funcionamiento [4], [5].

Otra diferencia importante es el sistema de alarmas inteligentes del EX-35, que proporciona información detallada en tiempo real para facilitar la identificación de situaciones anormales. Además, incorpora un módulo de análisis de gases anestésicos de tipo *Plug-and-Play*, con identificación automática de cinco agentes anestésicos y óxido nitroso. Esta característica permite ampliar las posibilidades de monitorización de los gases administrados al paciente. En el caso del EX-20, el manual describe el sistema de monitorización de oxígeno y las posibilidades de configuración del equipo mediante módulos y accesorios, por lo que sus funciones pueden variar según el equipamiento disponible [4], [5].

En cuanto a la ventilación, el EX-35 incorpora un ventilador multimodo que ofrece modalidades de ventilación controlada y asistida. También dispone de una función de cambio automático del gas impulsor, diseñada para mantener la ventilación mecánica cuando se presenta una falla en el suministro principal de dicho gas. Adicionalmente, el fabricante destaca la posibilidad de conectividad mediante salida HL7, que facilita la integración del equipo con sistemas de información clínica [5].

De esta manera, el WATO EX-20 ofrece las funciones necesarias para el suministro de gases, la administración de anestésicos y el soporte ventilatorio, mientras que el WATO EX-35 incorpora características adicionales relacionadas con la interfaz, la monitorización de gases anestésicos, las alarmas y la conectividad. Sin embargo, estas diferencias corresponden a las características técnicas de cada modelo y no significan, por sí solas, que uno garantice mejores resultados clínicos que el otro, ya que el desempeño también depende de su configuración, mantenimiento y correcta utilización por parte del personal especializado.

---

## VII. CONCLUSIÓN

La revisión de la máquina de anestesia Mindray WATO EX-20 permitió reconocer que su funcionamiento depende de la correcta integración de los sistemas de suministro de gases, ventilación, respiración, monitorización y alimentación eléctrica. A partir del análisis de las alarmas del fabricante, se identificó que muchas de las fallas pueden originarse por conexiones incorrectas, fugas u obstrucciones en el circuito respiratorio, instalación inadecuada de sus componentes, sensores desconectados o descalibrados y problemas en el suministro de gases o energía eléctrica. Esto demuestra que las fallas no siempre se deben a daños internos del equipo, sino que también pueden estar relacionadas con errores de montaje, mantenimiento o verificación previa. Por esta razón, es fundamental realizar las pruebas de funcionamiento antes de utilizar la máquina, comprobar las conexiones, revisar el estado del circuito respiratorio y verificar la calibración de los sensores, ya que estas acciones permiten detectar condiciones anormales oportunamente y reducir los riesgos durante su operación. Finalmente, complementar el reconocimiento teórico con prácticas supervisadas de verificación y mantenimiento preventivo permitiría fortalecer la capacidad para interpretar las alarmas e identificar las posibles causas de las fallas.

## REFERENCIAS

[1] A. Payo Salvatierra, “Anestesia y sus tipos. Desde su origen hasta la actualidad,” *NPunto*, vol. VII, no. 72, pp. 4-25, mar. 2024.

[2] D. Vandroux, P. Beaulieu y N. Nathan-Denizot, “Aparatos de anestesia,” *EMC - Anestesia-Reanimación*, vol. 52, no. 1, feb. 2026, ref. E-36-100-B-10.

[3] G. Ortiz, C. Dueñas, A. Lara, M. Garay, J. Blanco y G. Díaz Santos, “Bases de ventilación mecánica,” *Acta Colombiana de Cuidado Intensivo*, vol. 13, no. 2, pp. 17-45, 2013.

[4] Shenzhen Mindray Bio-Medical Electronics Co., Ltd., *Manual del usuario: Máquina de anestesia WATO EX-20*. Shenzhen, China: Mindray, 2018.

[5] Shenzhen Mindray Bio-Medical Electronics Co., Ltd., “WATO EX-35: Anesthesia Machine,” Mindray. [En línea]. Disponible en: [https://www.mindray.com/pe/products/anesthesia/wato-ex-35](https://www.mindray.com/pe/products/anesthesia/wato-ex-35).
