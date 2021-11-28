<h2>Home task #18</h2>
<h4>Description</h4>
<p>This app acts as a school journal. Allows you to enter data in the form of marks, students, subjects, teachers, and student parents.</p>
<h4>Task list</h4>
<ol>
<li> Git repo
<li> README.MD file with the task and description. gitignore
<li> create new maven project with 3 modules
<ol>
    <li>entity module
    <li>persistence module
    <li>(optinal) integration test module 
    <li>naming: {project-name}-persistence. examples: school-journal-persistence, car-service-entity, etc
</ol>
<li> Create POJO classes
<li> Use at least 4 class level annotations (for example embedded, immutable, and so on)
<li> Use at least 5 field level annotations (for example, transient)
<li> Use at least 2 diff id generation strategy
<li> create your custom id generation strategy and use it
<li> create your custom name strategy and use it
</ol>
<h4>Technologies</h4>
<ol>
<li>Java version: 11
<li>MySQL database
<li>docker-compose
<li>Flyway
<li>Hibernate
<li>Slf4j+logback
<li>Lombok
</ol>
<h4>How to run</h4>
<p>In order to build and run the application, follow these steps. 
In the console, go to the project directory and type:</p>
<ol>
<li>mvn clean package
<li>docker-compose up -d
<li>mvn flyway:migrate
</ol>
