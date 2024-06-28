<il><h3><a href="./content/chapter-5.4/chapter-5.4.md">5.2.4 Sprint 4</a></h3></il>
   <ul>
      <il><h3><a href="./content/chapter-5.4/chapter-5.4.md">5.2.4 Sprint 4</a></h3></il>
      <ul>
         <il><h3><a href="./content/chapter-5.4/chapter-5.4.md">5.2.4.1. Sprint Planning 4</a></h3></il>
         <table>
  <tr>
    <th>Sprint #</th>
    <td>Sprint 4</td>
  </tr>
  <tr>
    <th>Sprint Planning Date</th>
    <td>2024-05-29</td>
  </tr>
  <tr>
    <th>Time</th>
    <td>06:00 PM</td>
  </tr>
  <tr>
    <th>Location</th>
    <td>Servidor de Discord del Equipo</td>
  </tr>
  <tr>
    <th>Prepared By</th>
    <td>Renzo Ramos</td>
  </tr>
  <tr>
    <th>Attendees</th>
    <td>Juan Pablo/ Diego Acuña / Belen Ramos / Renzo Ramos / Gustavo Pardo</td>
  </tr>
    <tr>
    <th>Sprint Review Summary</th>
    <td>El objetivo del sprint anterior fue el desarrollo del Back End. Para este sprint, la meta fue centrada en la finalización del front end y back end y de la corrección de errores encontrados para finalizar el proyecto.</td>
  </tr>
  <tr>
    <th>Sprint Retrospective Summary</th>
    <td>Aún había ciertas partes faltantes al back end y front end por lo que el grupo se ha enfocado a corregirlas.</td>
  </tr>
  <tr>
    <th>Sprint Goal</th>
    <td>La meta de este Sprint es corregir los errores encontrados y la adición de elementos faltantes en los sprints anteriores.</td>
  </tr>
  <tr>
    <th>Sprint Velocity</th>
    <td>4</td>
  </tr>
  <tr>
    <th>Sum of Story Points</th>
    <td>18</td>
  </tr>
</table>
         <il><h3><a href="./content/chapter-5/chapter-5.md">5.2.4.2. Sprint Backlog 4</a></h3></il>
         <table border="1">
  <tr>
    <th>Sprint #</th>
    <th>User Story</th>
    <th>Work-item/Task</th>
    <th>Id</th>
    <th>Title</th>
    <th>Description</th>
    <th>Estimation (Hours)</th>
    <th>Assigned To</th>
    <th>Status (To-do / In-Process / To-Review / Done)</th>
  </tr>
  <tr>
    <td rowspan="2">Sprint 4</td>
    <td rowspan="2">HU01:  Registrar Cuenta</td>
    <td>TA01</td>
    <td>#182062235</td>
    <td>Desarrollar el Bounded Context Authentication</td>
    <td>Crear el bounded context de Authentication con su respectiva estructura</td>
    <td>4</td>
    <td>Gustavo Zapata</td>
    <td>Done</td>
  </tr>
  <tr>
    <td>TA02</td>
    <td>#182062223</td>
    <td> Crear los endpoints de Profiles y documentarlos en SwaggerUI</td>
    <td>Desarrollar los controladores del Bounded Context</td>
    <td>4</td>
    <td>Gustavo Zapata</td>
    <td>Done</td>
  </tr>
  <tr>
    <td rowspan="2">Sprint 4</td>
    <td rowspan="2">HU01:  Listar medicamentos</td>
    <td>TA01</td>
    <td>#182062235</td>
    <td> Desarrollar el Bounded Context HealthTracking</td>
    <td>Crear los aggregates,entities,commands,queries, services y repositories del Bounded Context HealthTraking</td>
    <td>6</td>
    <td>Renzo Ramos</td>
    <td>In process</td>
  </tr>
  <tr>
    <td>TA02</td>
    <td>#182062223</td>
    <td> Realizar los endpoints con los métodos http GET POST DELETE PATCH de Medications</td>d
    <td> Crear los controladores para documentar los endpoints de Medications</td>
    <td>4</td>
    <td>Renzo Ramos</td>
    <td>To-do</td>
  </tr>
</table>
         <il><h3><a href="./content/chapter-5.4/chapter-5.4.md">5.2.4.3. Development Evidence for Sprint Review</a></h3></il>
        En esta sección se presentan los commits realizados por los integrantes del equipo para las últimas partes del back end restantes.
<table border="1">
  <tr>
    <th>Repository</th>
    <th>Branch</th>
    <th>Commit Id</th>
    <th>Commit Message</th>
    <th>Commit Message Body</th>
    <th>Committed on (Date)</th>
  </tr>
  <tr>
    <td>RenzoRamosR /oncontigo-platform</td>
    <td>/feature/iam-auth </td>
    <td>61173a7</td>
    <td>feat: add iam authentication</td>
    <td>feat: add iam authentication</td>
    <td>26/06/2024</td>
  </tr>
   <tr>
    <td>RenzoRamosR /oncontigo-platform</td>
    <td>develop</td>
    <td>481d1c3</td>
    <td>Merge pull request #4 from RenzoRamosR/feature/iam-auth</td>
    <td>Merge pull request #4 from RenzoRamosR/feature/iam-auth</td>
    <td>26/06/2024</td>
  </tr>
    <tr>
    <td>RenzoRamosR /oncontigo-platform</td>
    <td>develop</td>
    <td>c95e30d</td>
    <td>feat: patient class</td>
    <td>feat: patient class</td>
    <td>26/06/2024</td>
  </tr>
    <tr>
    <td>RenzoRamosR /oncontigo-platform</td>
    <td>develop</td>
    <td>bef517c</td>
    <td>feat: doctor class added</td>
    <td>feat: doctor class added</td>
    <td>26/06/2024</td>
  </tr>
    <tr>
    <td>RenzoRamosR /oncontigo-platform</td>
    <td>feature/HealthTracking</td>
    <td>a72e3e1</td>
    <td>feat: doctor and patient outboundservices added</td>
    <td>feat: doctor and patient outboundservices added</td>
    <td>27/06/2024</td>
  </tr>
  <tr>
    <td>RenzoRamosR /oncontigo-platform</td>
    <td>feature/HealthTracking</td>
    <td>7bed46d</td>
    <td>feat: HealthTracking updated</td>
    <td>feat: HealthTracking updated</td>
    <td>27/06/2024</td>
  </tr>
   <tr>
    <td>RenzoRamosR /oncontigo-platform</td>
    <td>feature/HealthTracking</td>
    <td>83dda16</td>
    <td>fixed</td>
    <td>fixed</td>
    <td>27/06/2024</td>
  </tr>
   <tr>
    <td>RenzoRamosR /oncontigo-platform</td>
    <td>develop</td>
    <td>3081a8f</td>
    <td>Merge pull request #5 from RenzoRamosR/feature/HealthTracking</td>
    <td>Merge pull request #5 from RenzoRamosR/feature/HealthTracking</td>
    <td>27/06/2024</td>
  </tr>
   <tr>
    <td>RenzoRamosR /oncontigo-platform</td>
    <td>feature/HealthTracking</td>
    <td>2b69198</td>
    <td>feat(healthTracking): New endpoints added</td>
    <td>feat(healthTracking): New endpoints added</td>
    <td>27/06/2024</td>
  </tr>
   <tr>
    <td>RenzoRamosR /oncontigo-platform</td>
    <td>develop</td>
    <td>072ffb6</td>
    <td>Merge pull request #6 from RenzoRamosR/feature/HealthTracking</td>
    <td>Merge pull request #6 from RenzoRamosR/feature/HealthTracking</td>
    <td>27/06/2024</td>
  </tr>
   <tr>
    <td>RenzoRamosR /oncontigo-platform</td>
    <td>feature/roles</td>
    <td>f0432e8</td>
    <td>Edit</td>
    <td>Edit</td>
    <td>28/06/2024</td>
  </tr>
   <tr>
    <td>RenzoRamosR /oncontigo-platform</td>
    <td>feature/roles</td>
    <td>a7fe30c</td>
    <td>feat: patient and doctor outboundservice added</td>
    <td>feat: patient and doctor outboundservice added</td>
    <td>28/06/2024</td>
  </tr>
   <tr>
    <td>RenzoRamosR /oncontigo-platform</td>
    <td>feature/roles</td>
    <td>7766825</td>
    <td>Facade added</td>
    <td>Facade added</td>
    <td>28/06/2024</td>
  </tr>
   <tr>
    <td>RenzoRamosR /oncontigo-platform</td>
    <td>develop</td>
    <td>270b92f</td>
    <td>Merge pull request #7 from RenzoRamosR/feature/roles/td>
    <td>Merge pull request #7 from RenzoRamosR/feature/roles/td>
    <td>28/06/2024</td>
  </tr>
   <tr>
    <td>RenzoRamosR /oncontigo-platform</td>
    <td>feature/HealthTracking</td>
    <td>e8eb8c0</td>
    <td>feat(profiles): DBContext adjusted</td>
    <td>feat(profiles): DBContext adjusted</td>
    <td>28/06/2024</td>
  </tr>
   <tr>
    <td>RenzoRamosR /oncontigo-platform</td>
    <td>develop</td>
    <td>8ddc000</td>
    <td>Merge pull request #8 from RenzoRamosR/feature/HealthTracking</td>
    <td>Merge pull request #8 from RenzoRamosR/feature/HealthTracking</td>
    <td>28/06/2024</td>
  </tr>
</table>
         <il><h3><a href="./content/chapter-5/chapter-5.md">5.2.4.4. Testing Suite Evidence for Sprint Review</a></h3></il>
         No se desarrolló en este sprint, pues en esta parte se presentarán los Unit Tests, Integration Tests y
Acceptance Tests automatizados, para Web Services
<il><h3><a href="./content/chapter-5.4/chapter-5.4.md">5.2.4.5. Execution Evidence for Sprint Review</a></h3></il>
Implementacion de la Landing page en el FrontEnd<br>
<img src="../images/sprint3-images/execution/lamding.png"/> <br>
Responsive Modals<br>
<img src="../images/sprint3-images/execution/modals.png"/> <br>
SideBar del FrontEND <br>
<img src="../images/sprint3-images/execution/side.png"/> <br>
<il><h3><a href="./content/chapter-5/chapter-5.md">5.2.4.6. Services Documentation Evidence for Sprint Review</a></h3></il>
<img src="../images/sprint3-images/services/health.png"/> <br>
<img src="../images/sprint3-images/services/profiles.png"/> <br>
<img src="../images/sprint3-images/services/swagger.png"/> <br>

<il><h3><a href="./content/chapter-5/chapter-5.md">5.2.4.7. Software Deployment Evidence for Sprint Review</a></h3></il>

#### FrontEnd We App deployment link:  https://onc-frontend-202401.web.app/
<img src="../images/chapter-5/sprint5.2-deployment/deployment1.png"/> <br>  <br>

<img src="../images/sprint3-images/deploy/frontdeploy1.png"/>
<img src="../images/sprint3-images/deploy/frontdeplo2.png"/>

#### API RESTFul deployment:


<il><h3><a href="./content/chapter-5/chapter-5.md">5.2.4.8.Team Collaboration Insights during Sprint.</a></h3></il>
FRONTEND & BACKEND
<img src="../images/chapter-5/sprint5.2-teamcollaboration/branches.png"/> <br>
<img src="../images/sprint3-images/insights/commits.png"/> <br>
<img src="../images/chapter-5/sprint5.2-teamcollaboration/members.png"/> <br>
<img src="../images/sprint3-images//insights/network.png"/> <br>
<img src="../images/sprint3-images/insights/overview.png"/> <br>


</ul>
 
