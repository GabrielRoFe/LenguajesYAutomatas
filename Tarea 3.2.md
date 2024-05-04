# Tarea 3.2
***Vera Rodríguez Héctor Gabriel.***

Un autómata finito es un modelo matemático utilizado en ciencias de la computación y teoría de la computación para representar sistemas que pueden estar en un número finito de estados y que cambian de estado en respuesta a ciertas entradas. Consiste en un conjunto finito de estados, un alfabeto de entrada, una función de transición que especifica cómo cambia de estado el autómata en respuesta a una entrada, un estado inicial y un conjunto de estados finales.

# Caso de uso en la vida real.

Conjunto de Estados: Los estados podrían ser "en espera", "ingresando tarjeta", "ingresando PIN", "seleccionando acción (retirar dinero, consultar saldo, etc.)", "procesando solicitud", "entregando dinero", "finalizado".

Alfabeto de Entrada: Los símbolos podrían ser los botones del teclado numérico y las opciones en la pantalla táctil.

Función de Transición: Por ejemplo, si estás en el estado "ingresando PIN" y introduces los números correctos, pasarías al estado "seleccionando acción". Si introduces un número incorrecto, podrías quedarte en el mismo estado o pasar a un estado de bloqueo.

Estado Inicial: Cuando el cajero automático está encendido, estaría en el estado "en espera".

Conjunto de Estados Finales: Podría ser el estado "entregando dinero", una vez que se ha completado la transacción con éxito.

![atmirage-interface](https://github.com/GabrielRoFe/LenguajesYAutomatas/assets/160956553/5ee02942-b064-434b-a872-bbf1961ab1b4)

# Aplicación.

Sistemas Bancarios y Financieros: Los cajeros automáticos son una parte fundamental de los sistemas bancarios y financieros modernos. Permiten a los clientes realizar una variedad de transacciones, como retiros de efectivo, depósitos, transferencias de fondos, consultas de saldo, entre otras, de manera rápida y conveniente.

Automatización de Procesos: La implementación de cajeros automáticos automatiza muchos de los procesos que de otro modo requerirían la intervención de personal bancario. Esto reduce los costos operativos para los bancos y brinda a los clientes acceso a servicios las 24 horas del día, los 7 días de la semana.

Mejora de la Experiencia del Cliente: Los cajeros automáticos ofrecen una experiencia de usuario intuitiva y conveniente. Los clientes pueden realizar transacciones sin tener que esperar en largas colas en sucursales bancarias, lo que mejora su satisfacción y fidelidad.

Seguridad: Los cajeros automáticos están diseñados con medidas de seguridad robustas para proteger las transacciones financieras de los usuarios. Esto incluye la encriptación de datos, la autenticación de usuarios mediante el uso de PINs y tarjetas bancarias, y la vigilancia física y electrónica para prevenir fraudes y robos.

Acceso a Servicios Bancarios en Áreas Remotas: Los cajeros automáticos pueden instalarse en áreas remotas o con poca presencia bancaria, brindando acceso a servicios financieros a comunidades que de otro modo tendrían dificultades para acceder a ellos.

![maxresdefault](https://github.com/GabrielRoFe/LenguajesYAutomatas/assets/160956553/67783f9f-1901-467c-b572-f7200e7359cc)

# Conclusión

Los autómatas finitos son una herramienta poderosa en ciencias de la computación y disciplinas relacionadas, con aplicaciones que abarcan desde el diseño de sistemas de control hasta la automatización de procesos en la industria financiera. A través de la representación formal de estados, transiciones y entradas, los autómatas finitos permiten modelar y comprender sistemas secuenciales de una manera clara y estructurada. Ejemplos prácticos, como el caso de uso del cajero automático, ilustran cómo estos modelos teóricos se aplican en la vida cotidiana para mejorar la eficiencia, la accesibilidad y la seguridad en una amplia gama de aplicaciones. En última instancia, los autómatas finitos continúan siendo una herramienta invaluable en el diseño y análisis de sistemas complejos, contribuyendo al desarrollo y avance de la tecnología en diversos campos.
