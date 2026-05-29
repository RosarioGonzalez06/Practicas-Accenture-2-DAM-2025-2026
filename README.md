# Prácticas en Accenture · 2º DAM · 2025/2026

**María del Rosario González Ortiz y Lucas Faura Martín**  
Ciclo Formativo de Grado Superior — Desarrollo de Aplicaciones Multiplataforma  
Curso 2025/2026

---

## Sobre Accenture

**Accenture** es una empresa multinacional líder en servicios profesionales de consultoría, tecnología y externalización. A nivel global, ayuda a organizaciones y empresas a acelerar su transformación digital, optimizar sus operaciones e impulsar la innovación mediante el uso de tecnologías avanzadas (como cloud e inteligencia artificial) y plataformas empresariales de primer nivel.

## Descripción

Este repositorio recoge el diario de prácticas realizadas en **Accenture** durante el segundo año del CFGS de DAM. Las prácticas se han centrado en el aprendizaje y desarrollo sobre la plataforma **Salesforce CRM** (Customer Relationship Management), que permite a las empresas gestionar las relaciones con sus clientes, automatizar procesos de negocio complejos y desarrollar aplicaciones a medida de forma escalable. Tambien se ha centrado en ...

---

## Diario de Prácticas de Rosario González Ortiz

A lo largo de estas prácticas he utilizado diferentes herramientas y tecnologías centradas en Salesforce, incluyendo **Apex** para el desarrollo backend, **Lightning Web Components (LWC)** para el frontend, automatizaciones mediante **Salesforce Flow**, y herramientas de inteligencia artificial generativa como **Salesforce Einstein AI**, todo ello aplicado en los entornos de **Commerce Cloud B2B** y **Sales Cloud**.

### Semanas 1–2 (03/03/2026 – 13/03/2026)
> **Formación inicial en Salesforce**

* Realización de módulos formativos oficiales de Salesforce para comprender el funcionamiento del CRM.

---

### Semana 3 (16/03/2026 – 20/03/2026)
> **Incorporación a proyecto Commerce Cloud B2B · Sector siderúrgico y finalización de la formación**

* Ejercicio final sobre los conocimientos adquiridos en los módulos de formación.
* Incorporación a un proyecto de **Salesforce Commerce Cloud (B2B)**.
* Inicio de tareas de **Testing de clases Apex** para entender la lógica del proyecto.

---

### Semana 4 (23/03/2026 – 27/03/2026)
> **Testing y análisis de componentes LWC**

* Continuación con el Testing de clases Apex del proyecto.
* Investigación de la lógica de un componente **LWC** para resolver un error en el botón *"Añadir al carrito"*.

---

### Semana 5 (07/04/2026 – 10/04/2026)
> **Componentes LWC y Custom Labels**

* Análisis de distintos componentes LWC para entender su lógica dentro del proyecto.
* Clonado y renombrado de **Custom Labels**, sustituyéndolos en el código base.

---

### Semana 6 (13/04/2026 – 17/04/2026)
> **Desarrollo de funcionalidades en el carrito de compra**

* Creación de un **campo personalizado** en un objeto de Salesforce.
* Modificación de clase Apex y estilos CSS para mostrar error visual (rojo) en el carrito cuando la cantidad supera el stock disponible.
* Implementación de un **selector de cantidades** en el carrito con estilos responsivos.
* Adición de un **spinner de carga** al pulsar "Seguir comprando".
* Creación de un **modal de errores** para el carrito cuando no hay stock disponible.

---

### Semana 7 (20/04/2026 – 24/04/2026)
> **Nuevo proyecto: Sales Cloud · Sector bancario**

* Cambio a proyecto en **Salesforce Sales Cloud**.
* Creación de **campos personalizados** en distintos objetos para la recogida de datos de negocio.
* Desarrollo de un **Batch Apex** para actualización masiva de datos.
* Creación de **clase Test** para el Batch Apex.
* Desarrollo de **componentes LWC padre e hijos** para una pantalla de gestión de usuarios.

---

### Semana 8 (27/04/2026 – 30/04/2026)
> **Mejoras visuales y Testing**

* Modificación de estilos en el componente LWC de la cabecera de la pantalla de gestiones.
* Testing de distintas clases Apex del proyecto Sales Cloud.

---

### Semanas 9–10 (04/05/2026 – 15/05/2026)
> **Nuevo proyecto: Prototipado con IA en Salesforce · Sector consumo**

* Testing adicional de clases Apex del proyecto Sales Cloud.
* Incorporación a nuevo proyecto de **prototipado con IA** en Salesforce.
* Creación de campos personalizados y relleno con datos de prueba.
* Creación de un **Flow** que recoge datos de los campos y genera un **JSON estructurado** para su consumo por la IA.
* Ajuste y refinamiento de **prompts de IA** (Salesforce Einstein) para obtener respuestas en distintos formatos y adaptadas a los requisitos del cliente.

---

### Semana 11 (18/05/2026 – 22/05/2026)
> **Finalización proyecto IA · Vuelta a proyecto Sales Cloud**

* Finalización y entrega del proyecto de prototipado con IA.
* Modificación de un **Flow** existente en el proyecto Sales Cloud.
* Modificación de componentes LWC de la pantalla de gestiones.

---

### Semana 12 (25/05/2026 – 29/05/2026)
> **Componentes LWC, Flow y Testing**

* Modificación y mejora de componentes LWC de la pantalla de gestiones.
* Desarrollo de un **Flow** para reporte de casos
* Testing para varias clases Apex

---

## Conocimientos adquiridos por cada módulo profesional

A lo largo de las prácticas, he podido aplicar de forma práctica varios de los conocimientos vistos en los módulos de este curso:

* **Optativa:** He desarrollado *mocks* para realizar pruebas unitarias (*testing*) con APIs. Un *mock* se usa para simular la respuesta de la API, lo que me ha permitido probar el código sin necesidad de hacer peticiones reales a otros servidores ni depender de la conexión a internet.
* **Acceso a Datos:** He trabajado bastante con **LWC (Lightning Web Components)**. Es una tecnología muy similar a Angular, ya que también se basa en componentes con HTML, CSS y JavaScript. Aunque en Angular utilizábamos TypeScript, al final JavaScript es muy parecido, por lo que la manera en la que se conectan y manejan los datos por pantalla me ha resultado muy familiar gracias a lo aprendido en clase.
* **Desarrollo de Interfaces:** Durante el desarrollo de los distintos componentes, he aprendido la importancia de mantener el código limpio y organizado, acostumbrándome a documentar correctamente cada método de las clases para explicar su funcionamiento y facilitar el trabajo en equipo.
* **Sistemas de Gestión Empresarial:** Gran parte de la asignatura trata sobre los sistemas CRM. Al haber estado trabajando con **Salesforce** (el CRM más utilizado), me ha servido para entender de primera mano cómo las empresas gestionan a sus clientes, sus ventas y automatizan sus procesos de negocio.
* **Inglés:** Todo el entorno de trabajo, los recursos y la documentación de Salesforce están en inglés. Además, he tenido que utilizarlo a diario para comunicarme, ya que participaba en reuniones (*dailys*) con compañeros de otros países, como por ejemplo la India.
* **Proyecto Intermodular:** Me ha servido para comprobar cómo es la organización real de un proyecto en el mundo laboral. He aprendido a trabajar con metodologías ágiles y a utilizar herramientas como **Jira** para hacer el seguimiento de las tareas (*tickets*) y coordinarme con el equipo.

---

## Valoración Personal

Me ha encantado la experiencia y he aprendido muchísimo sobre **Salesforce**, una plataforma en la que llevaba bastantes años interesada. Todos los compañeros se han portado genial y me han ayudado siempre que ha hecho falta. Además, valoro muy positivamente haber podido participar de forma activa y directa en los proyectos reales.
