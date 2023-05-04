# APP docSecure

## **Resumen:**

La aplicación a diseñar es un sistema de reserva de citas médicas en línea para una clínica. Los pacientes podrán reservar citas seleccionando una especialidad, un doctor, un horario y un día de la semana. Los doctores tendrán la posibilidad de crear un perfil y agregar información como nombre, apellido, experiencia y título. El sistema también contará con un panel de administración para que los administradores de la clínica puedan visualizar métricas importantes del negocio, tales como el número de citas generadas por día, mes o año, especialidades más solicitadas, doctores con mejor calificación, ingresos, entre otros datos relevantes.

Para lograr esto, se requiere desarrollar una aplicación web robusta y escalable. El sistema debe ser fácil de usar tanto para los pacientes como para los doctores y administradores. Se necesitará una base de datos sólida para almacenar la información de los pacientes, doctores y citas, así como para la generación de métricas y reportes.

La aplicación debe ser segura y contar con mecanismos de autenticación y autorización adecuados para garantizar la privacidad de la información de los pacientes. También se requiere un sistema de notificaciones por correo electrónico o mensaje de texto para recordar a los pacientes acerca de su cita programada.

En resumen, el sistema debe permitir que los pacientes puedan programar sus citas médicas fácilmente desde la comodidad de su hogar, lo que puede aumentar la eficiencia de la clínica, reducir los tiempos de espera y mejorar la experiencia del paciente en general.

## **Tipos de usuarios de la aplicación:**

### **1. Pacientes:**

Son los usuarios finales que utilizan la aplicación para reservar citas médicas en la clínica. Tienen la capacidad de buscar especialidades, médicos, horarios y días de atención, y reservar una cita médica. También tienen la capacidad de crear y editar su perfil personal para mantener sus datos actualizados.

### **2. Administradores:**

Son los usuarios encargados de administrar el sistema de reserva de citas en la clínica. Tienen la capacidad de visualizar y analizar las métricas del negocio como el número de citas generadas por día, mes, año y especialidad, los doctores con mejor calificación, ingresos, entre otros. Además, tienen la capacidad de administrar y editar la información de los médicos, especialidades, horarios de atención y días disponibles en el sistema.

### **3. Doctores:**

Serán usuarios que podrán registrarse y tener acceso a su perfil en el sistema de reserva de citas. En este perfil, podrán agregar información básica como su nombre, apellido, experiencia y título, así como también subir su foto y agregar una descripción sobre su práctica médica. Los doctores también podrán visualizar y gestionar sus citas, ver la información del paciente que reserva la cita y comunicarse con ellos si es necesario. Además, los doctores podrán actualizar su disponibilidad en cuanto a días y horarios de atención para que los pacientes puedan reservar citas en función de ello.

## **User Stories**

### **1. Para el usuario Paciente:**

- Como paciente, quiero poder autenticarme con mi correo electrónico y contraseña para poder acceder a mi perfil y hacer reservas de citas médicas.
- Como paciente, quiero poder ver mi historial de citas médicas previas y cancelar una cita si es necesario, después de autenticarme.
- Como paciente, quiero poder buscar médicos por especialidad y ver su información de perfil y horarios de disponibilidad, después de autenticarme.
- Como paciente, quiero poder hacer reservas de citas médicas eligiendo una especialidad, un médico y un horario de disponibilidad, después de autenticarme.
- Como paciente, quiero poder calificar al médico después de la cita, para ayudar a otros pacientes o administradores a elegir un médico adecuado.
- Como paciente, quiero poder realizar el pago por la cita médica mediante la aplicación, para tener una experiencia de reserva de cita sin problemas.

### **2. Para el usuario Doctor:**

- Como doctor, quiero poder autenticarme con mi correo electrónico y contraseña para poder acceder a mi perfil y administrar mi información personal y de disponibilidad.
- Como doctor, quiero poder actualizar mi perfil con mi información de contacto, experiencia y especialidades después de autenticarme.
- Como doctor, quiero poder ver mi horario de citas médicas y cancelar una cita si es necesario, después de autenticarme.
- Como doctor, quiero poder confirmar o rechazar las solicitudes de cita médica de los pacientes, después de autenticarme.

### **3. Para el usuario Administrador:**

- Como administrador, quiero poder autenticarme con mi correo electrónico y contraseña para poder acceder al panel de administración y ver las métricas de negocio.
- Como administrador, quiero poder ver el número de citas médicas generadas por día, mes, año y especialidad después de autenticarme.
- Como administrador, quiero poder ver el médico con la mejor calificación y el mayor número de citas generadas después de autenticarme.
- Como administrador, quiero poder ver los ingresos generados por las citas médicas después de autenticarme.
