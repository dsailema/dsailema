<div align="center">

<img src="banner.svg" alt="Damaris Sailema, estudiante de Ingeniería de Software" width="100%">

<br><br>

<a href="mailto:sailemadamaris72@gmail.com"><img src="https://img.shields.io/badge/Correo-sailemadamaris72@gmail.com-722F37?style=for-the-badge&logo=gmail&logoColor=white&labelColor=1a1a1a" alt="Correo"></a>

</div>

<br>

---

## Sobre mí

Estudio Ingeniería de Software en la Universidad Técnica de Ambato y me enfoco en el desarrollo web, con interés creciente en el manejo y análisis de datos. Me gusta entender cómo funcionan las cosas por dentro, documentar lo que hago y mejorar cada proyecto paso a paso.

Trabajo en equipo con metodologías ágiles, control de versiones con Git y revisión de código mediante pull requests.

Idiomas: español (nativo) e inglés (B1).

---

## Tecnologías

<div align="center">

<img src="https://img.shields.io/badge/Java-722F37?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java">
<img src="https://img.shields.io/badge/PHP-5C4033?style=for-the-badge&logo=php&logoColor=white" alt="PHP">
<img src="https://img.shields.io/badge/JavaScript-8B5E3C?style=for-the-badge&logo=javascript&logoColor=white" alt="JavaScript">
<img src="https://img.shields.io/badge/.NET-722F37?style=for-the-badge&logo=dotnet&logoColor=white" alt=".NET">
<img src="https://img.shields.io/badge/Angular-5C4033?style=for-the-badge&logo=angular&logoColor=white" alt="Angular">
<img src="https://img.shields.io/badge/React-8B5E3C?style=for-the-badge&logo=react&logoColor=white" alt="React">
<img src="https://img.shields.io/badge/HTML-1a1a1a?style=for-the-badge&logo=html5&logoColor=white" alt="HTML">
<img src="https://img.shields.io/badge/CSS-722F37?style=for-the-badge&logo=css3&logoColor=white" alt="CSS">
<img src="https://img.shields.io/badge/SQL-5C4033?style=for-the-badge" alt="SQL">
<img src="https://img.shields.io/badge/PostgreSQL-8B5E3C?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
<img src="https://img.shields.io/badge/SQL_Server-1a1a1a?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" alt="SQL Server">
<img src="https://img.shields.io/badge/Git-722F37?style=for-the-badge&logo=git&logoColor=white" alt="Git">

</div>

---

## Proyectos destacados

### [EcuaRutas](https://github.com/JuanFull1/EcuaRutas)

Sistema web para la gestión del transporte interprovincial de pasajeros en Ecuador. Conecta en una sola plataforma a las cooperativas de buses, sus oficinistas y los clientes: las cooperativas administran flota, rutas y frecuencias; los oficinistas venden boletos en ventanilla; y los clientes consultan disponibilidad y pagan en línea.

**Tecnologías:** Angular, Bootstrap 5, C# con .NET 10, PostgreSQL, autenticación con JWT y roles (administrador, cooperativa, oficinista y cliente).

**Forma de trabajo:** equipo de 6 personas con GitFlow, Jira, Conventional Commits y pull requests hacia `develop` con 2 aprobaciones.

**Mi aporte (módulo de flota):**

- API de buses, grupos de buses y plantillas de asientos: registrar, consultar, editar y dar de baja buses, con validaciones y errores claros (400, 404, 409).
- Frontend de flota: lista de buses con filtro por estado y formulario de creación, con validaciones y mensajes de error en español.
- Seguridad: detecté que los controladores de flota estaban abiertos sin sesión y los protegí por rol, verificando los códigos 401, 403 y 200 con pruebas reales.
- Revisión de código: probé y revisé pull requests de mis compañeros contra la API.
- Documentación: guía de control de cambios con GitHub Issues para el informe del proyecto.

<br>

### Sistema Automatizado para la Homologación de Materias y Créditos (FISEI - UTA)

Sistema que permite a un profesor designado gestionar la homologación de materias y créditos de estudiantes, internos o externos, hacia una carrera y malla de destino. El administrador mantiene el catálogo académico (carreras, mallas, asignaturas, temas y subtemas) y el historial de un estudiante externo se importa desde una plantilla de Excel.

**Arquitectura y tecnologías:** microservicios en .NET 8 (Auth, Academic, Students, Documents y Homologation), cada uno con su propia base de datos en SQL Server, un API Gateway con Ocelot como entrada única y frontend en React.

**Forma de trabajo:** Scrum, Jira, GitHub e integración continua. Cada tarea se desarrolla en una rama propia, con commits convencionales, pruebas manuales documentadas y pull request hacia `develop`.

**Mi aporte (Sprint 2):**

- Estado de la malla: una malla puede estar en borrador o publicada, y la base de datos garantiza una sola publicada por carrera.
- Temas y subtemas: modelo de datos y un script que genera la carga inicial a partir de los planes analíticos en PDF (80 asignaturas y 619 temas).
- Students Service: servicio y base de datos con estudiante, historial académico y asignaturas cursadas, incluyendo cédula o pasaporte y horas por asignatura.
- Plantilla de importación: plantilla de Excel con las hojas Estudiante, Asignaturas y Contenidos, y su contrato de validación.
- Homologation Service: servicio y base de datos con el expediente, sus estados, el profesor responsable, la regla de un expediente activo por estudiante y carrera, la homologación compuesta y la ruta en el Gateway.

---

## En qué estoy trabajando ahora

- Arquitectura de microservicios con .NET y API Gateway.
- Modelado de bases de datos y consultas con SQL.
- Mejorar mi inglés técnico leyendo documentación.

---

<details>
<summary><b>English summary</b></summary>

<br>

I am a Software Engineering student at Universidad Técnica de Ambato, Ecuador. I am interested in web development and working with data. I work with Java, PHP, JavaScript, .NET, Angular, React, SQL, PostgreSQL, HTML and CSS. I work in teams using Git, code reviews and agile methods. I am improving my English (B1 level) and I am open to learning and collaborating on projects.

Contact: sailemadamaris72@gmail.com

</details>
