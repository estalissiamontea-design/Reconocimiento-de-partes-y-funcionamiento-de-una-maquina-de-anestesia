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

Debido a que algunos componentes del sistema respiratorio entran en contacto directo o indirecto con las secreciones y los gases exhalados del paciente, deben someterse a procedimientos adecuados de limpieza y desinfección para evitar la contaminación cruzada. La selección del procedimiento depende del material, las indicaciones del fabricante y el nivel de contacto con el paciente.

El manual de la Mindray WATO EX-20 contempla procedimientos específicos para limpiar, desinfectar y reinstalar elementos como las válvulas inspiratoria y espiratoria, el conjunto del fuelle, el recipiente absorbente de CO₂, los tubos respiratorios y la pieza en Y [4]. No obstante, no todos estos componentes necesariamente admiten esterilización en autoclave. La compatibilidad con este procedimiento debe verificarse individualmente en las instrucciones del fabricante, considerando los materiales y las condiciones de temperatura y presión del proceso.

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
