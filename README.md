# examen-mysql
El objetivo de este examen es diseñar una base de datos que permita almacenar y gestionar la información sobre médicos, empleados y pacientes de un centro de salud. La base de datos debe reflejar la estructura del personal médico, incluidos médicos titulares, interinos y sustitutos, junto con sus horarios y períodos de sustitución. Además, se debe llevar un registro detallado de las vacaciones planificadas y disfrutadas, tanto para médicos como para empleados. Finalmente, se gestionará la relación entre pacientes y los médicos asignados.



Problema


El centro de salud necesita una solución para organizar y consultar la información del personal médico, los empleados y los pacientes de manera eficiente. Actualmente, la falta de un sistema centralizado genera dificultades a la hora de saber quién está activo, quién está de vacaciones o en sustitución, y quién tiene asignados a los pacientes. Además, el cálculo de las horas de consulta semanales y la gestión de las vacaciones planificadas son tareas que se realizan manualmente, lo que resulta en errores y pérdida de tiempo.



Características Principales


Gestión de médicos: Registro completo de médicos, incluyendo su tipo (titular, interino o sustituto), horarios de consulta y períodos de sustitución.
Gestión de empleados: Información detallada de los empleados no médicos, incluyendo ATS, auxiliares de enfermería, celadores y administrativos.
Gestión de pacientes: Relación entre pacientes y médicos asignados.
Control de vacaciones: Registro de las vacaciones planificadas y disfrutadas tanto para médicos como empleados.


Requisitos del Modelo Lógico y Físico


El modelo lógico debe reflejar correctamente las entidades, relaciones, atributos y cardinalidades.
El modelo físico debe ser implementable en una base de datos MySQL, reflejando correctamente las estructuras de tablas, claves primarias y foráneas.
Evidencia fotográfica o uso de plataformas como drawSQL o StarUML debe ser proporcionada, ya sea en forma de capturas de pantalla o enlaces a los diagramas.


Tecnologías y Herramientas


Base de Datos: MySQL para la gestión de la información.
Lenguaje de Consulta: SQL para realizar las consultas necesarias y gestionar los datos.
Herramientas de Diseño: Herramientas de modelado de bases de datos (por ejemplo, MySQL Workbench) para visualizar y diseñar la estructura de la base de datos.

me enfoque en solo estas preguntas:

1. **Número de pacientes atendidos por cada médico**



```sql



```



2. **Total de días de vacaciones planificadas y disfrutadas por cada empleado**



```sql



```



3. **Médicos con mayor cantidad de horas de consulta en la semana**



```sql



```



4.  **Número de sustituciones realizadas por cada médico sustituto**



```sql



```



5.  **Número de médicos que están actualmente en sustitución**



```sql
<img width="1234" height="736" alt="image" src="https://github.com/user-attachments/assets/aaa822d9-0c7e-416f-b6eb-b40688e93df2" />

