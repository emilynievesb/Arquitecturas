# 🏗️ Arquitectura de Software 🏗️

La arquitectura de software representa la columna vertebral de un sistema de software, definiendo sus componentes, relaciones y principios de diseño. Es el plano maestro que guía la construcción de un sistema de software, una hoja de ruta trazada en las primeras etapas del proceso de desarrollo.

La importancia de la arquitectura de software radica en su capacidad para proporcionar una visión general del sistema, permitiendo que los desarrolladores tomen decisiones informadas sobre el diseño y la implementación. Además, garantiza la escalabilidad, adaptabilidad y mantenibilidad del sistema.

En sus comienzos, el desarrollo de software se llevaba a cabo de manera informal. Con el tiempo, han surgido nuevos modelos y estándares para abordar los desafíos contemporáneos. Estos modelos y estándares se conocen como arquitectura de software. De manera similar a los planos de un edificio, la arquitectura de software define la estructura, el funcionamiento y la interacción entre las partes del software.

# 🛠️ Funcionamiento de la Arquitectura de Software 🛠️

La arquitectura de software es como el plano de una ciudad. Se basa en decisiones de diseño que determinan cómo se construyen y gestionan los componentes del software. Estas decisiones abarcan la elección de lenguajes de programación, la distribución de tareas, la gestión de datos, la comunicación entre componentes y la seguridad. La arquitectura actúa como un plan maestro que guía el ciclo de vida del software, desde la concepción hasta la implementación y el mantenimiento.

# Problemas que resuelve la Arquitectura de Software

| Problemas que resuelve la Arquitectura de Software | Descripción                                                                                                            |
| -------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------- |
| Complejidad                                        | Descompone sistemas complejos en componentes manejables, facilitando su desarrollo.                                    |
| Escalabilidad                                      | Define cómo un sistema puede crecer y adaptarse sin requerir una reconstrucción completa.                              |
| Mantenimiento                                      | Facilita la corrección de problemas y la incorporación de nuevas funcionalidades sin afectar otras partes del sistema. |
| Reutilización                                      | Promueve la reutilización de componentes y módulos, ahorrando tiempo y recursos.                                       |
| Rendimiento y Eficiencia                           | Optimiza el rendimiento al distribuir tareas y recursos de manera eficiente.                                           |

# Componentes de la Arquitectura de Software

| Componentes de la Arquitectura de Software | Descripción                                                                                               |
| ------------------------------------------ | --------------------------------------------------------------------------------------------------------- |
| Componentes del Sistema                    | Módulos o partes del software que realizan tareas específicas.                                            |
| Interconexiones                            | Formas en que los componentes se comunican, como llamadas a funciones o intercambio de datos.             |
| Patrones de Diseño                         | Soluciones estándar para problemas de diseño.                                                             |
| Consideraciones de Calidad                 | Factores como seguridad, escalabilidad y eficiencia que deben tenerse en cuenta en el diseño del sistema. |

# 🧩 Patrones de Diseño 🧩

Los patrones de diseño en la arquitectura de software son soluciones generales y reutilizables para problemas comunes en el diseño de software. Aunque se asemejan a los patrones de diseño de software, tienen un alcance más amplio, centrándose en la estructura y el comportamiento de los componentes individuales de un sistema.

Estos patrones se enfocan en la resolución de problemas comunes en el diseño de software, abordando la estructura y el comportamiento de los componentes individuales del sistema.

Algunos ejemplos de patrones de diseño incluyen:

🛰️ **Factory Pattern:** Este patrón permite la creación de objetos sin exponer la lógica de creación.

🛰️ **Singleton Pattern:** Garantiza la existencia de una única instancia de una clase en el sistema.

🛰️ **Adapter Pattern:** Permite la comunicación entre dos clases que no son compatibles.

## 🏗️ Patrones de Arquitectura 🏗️

Los patrones de diseño de arquitectura de software se dividen en dos categorías principales:

## ⚙️ Patrones de Organización:

Los patrones de organización se centran en la estructura global del sistema, definiendo cómo los componentes del software se organizan y se relacionan entre sí. Estos patrones ayudan a los arquitectos de software a dividir el sistema en partes manejables y a definir la forma en que interactúan. Algunos ejemplos notables incluyen:

### ⚙️ Patrón de Capas:

Este patrón divide el sistema en capas o niveles, donde cada capa tiene una función específica. Por ejemplo, en una aplicación web, puedes tener una capa de presentación (interfaz de usuario), una capa de lógica de negocios y una capa de acceso a datos. La capa de presentación se encarga de la interacción con el usuario, la capa de lógica de negocios implementa la lógica empresarial y la capa de acceso a datos se ocupa de la persistencia de datos. Este enfoque ayuda a separar las preocupaciones y facilita la gestión y la escalabilidad del sistema.

### ⚙️ Patrón Cliente-Servidor:

El Patrón Cliente-Servidor divide el sistema en dos partes principales: los clientes y los servidores. Los clientes son responsables de realizar peticiones, como solicitar información o servicios, mientras que los servidores responden a estas peticiones proporcionando los recursos solicitados. Este modelo establece una clara separación de responsabilidades y es fundamental en arquitecturas de red y sistemas distribuidos. Los servidores pueden ser centralizados o distribuidos, y esta arquitectura es común en aplicaciones web, donde los navegadores actúan como clientes y los servidores web manejan las solicitudes y respuestas.

### ⚙️ Patrón de Microservicios:

Este patrón divide el sistema en servicios independientes, cada uno con su propia funcionalidad específica. Cada microservicio se ejecuta de manera autónoma y se comunica con otros microservicios para realizar tareas más complejas. Esta arquitectura permite la flexibilidad y la escalabilidad, ya que cada microservicio se puede desarrollar, implementar y escalar de forma independiente. Es especialmente útil en sistemas grandes y complejos, donde cada microservicio puede estar respaldado por un equipo de desarrollo dedicado.

## ⚙️ Patrones de Comportamiento:

Los patrones de comportamiento se centran en cómo los componentes del sistema interactúan para lograr objetivos específicos. Estos patrones definen cómo se produce la comunicación, la colaboración y la coordinación entre los componentes del sistema. Aquí tienes algunos ejemplos relevantes:

### ⚙️ Patrón Modelo-Vista-Controlador (MVC):

El Patrón Modelo-Vista-Controlador (MVC) es ampliamente utilizado en aplicaciones web y de software. Divide una aplicación en tres componentes principales: el Modelo, que maneja los datos y la lógica de negocio; la Vista, que se encarga de la presentación y la interfaz de usuario; y el Controlador, que gestiona las interacciones del usuario y la coordinación entre el Modelo y la Vista. Esta separación de responsabilidades facilita el desarrollo, la mantenibilidad y la escalabilidad de las aplicaciones.

### ⚙️ Patrón Broker:

El Patrón Broker actúa como intermediario entre componentes o servicios, centralizando la comunicación y la gestión de servicios. El Broker actúa como un punto de acceso central para los componentes del sistema, facilitando la integración y la comunicación. Es especialmente útil en sistemas distribuidos, donde puede actuar como un conserje que conecta diferentes servicios en un hotel, gestionando las solicitudes y las respuestas.
