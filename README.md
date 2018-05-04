# JHipster_Learning

<ul>
  <li>Which type of application would you like to create?
    <ol>
      <li>Monolithic application: this a classical, one-size-fits-all application. It’s easier to use and develop, and is our recommended default.</li>
      <li>Microservice application: in a microservices architecture, this is one of the services</li>
      <li>Microservice gateway: in a microservices architecture, this is an edge server that routes and secures requests</li>
      <li>JHipster UAA server: in a microservices architecture, this is an OAuth2 authentication server that secures microservices</li>
    </ol>  
  </li>
  <li>What is the base name of your application?</li>
  <li>What is your default Java package name?</li>
  <li>Do you want to use the JHipster Registry to configure, monitor and scale your application?</li>
  <li>Which type of authentication would you like to use?
    <ol>
      <li>JWT authentication: use a JSON Web Token (JWT), which is the default choice</li>
      <li>HTTP Session Authentication: the classical session-based authentication mechanism, like we are used to do in Java</li>
      <li>OAuth 2.0 / OIDC Authentication: this uses an OpenID Connect server, like Keycloak or Okta, which handles authentication outside of the application.</li>
      <li>Authentication with JHipster UAA server: this uses a JHipster UAA server that must be generated separately, and which is an OAuth2 server that handles authentication outside of the application.</li>
    </ol
  </li>
   <li>
     Which type of database would you like to use?
     <ol>
       <li>No database (only available when using a microservice application)</li>
       <li>An SQL database (H2, MySQL, MariaDB, PostgreSQL, MSSQL, Oracle), which you will access with Spring Data JPA</li>
       <li>MongoDB</li>
       <li>Cassandra</li>
       <li>Couchbase</li>
     </ol>
   </li>
   <li>
     Which production database would you like to use?
    </li>
      <li>Which development database would you like to use?</li>
      <li>Do you want to use the Spring cache abstraction?</li>
      <li>Do you want to use Hibernate 2nd level cache?</li>
      <li>Would you like to use Maven or Gradle?</li>
      <li>Which other technologies would you like to use?
        <ol>
          <li>swagger-codegen</li>
          <li>ElasticSearch</li>
          <li>Hazelcast</li>
          <li>Websocket</li>
        </ol>
      </li>
      <li>Which Framework would you like to use for the client?
        <ol>Angular</ol>
        <ol>React</ol>
      </li>
      <li>Would you like to use the LibSass stylesheet preprocessor for your CSS?</li>
      <li>Would you like to enable internationalization support?</li>
      <li>Which testing frameworks would you like to use?
        <ol>
          <li> default JHipster provide Java unit/integration testing (using Spring’s JUnit support) and JavaScript unit testing (using Karma.js)</li>
        </ol>
      </li>
      <li>
        Would you like to install other generators from the JHipster Marketplace?
      </li>
      
</ul>

<hr/>
<ul>
  <li><h3><b>Creating Entity</b></h3>
    <ol>
      <li>command -- jhipster entity <entityName> </li>
      <li>Do you want to add a field to your entity?</li>
      <li>What is the name of your field?</li>
      <li>What is the type of your field?</li>
      <li>Do you want to add validation rules to your field?</li>
      <li>Which validation rules do you want to add?</li>
      <li>Do you want to add a relationship to another entity?</li>
      <li>What is the name of the other entity?</li>
      <li>What is the name of the relationship?</li>
      <li>What is the type of the relationship?</li>
      <li>What is the name of this relationship in the other entity?</li>
      <li>Do you want to use separate service class for your business logic? </li>
      <li>Do you want to use a Data Transfer Object (DTO)?</li>
      <li>Do you want to add filtering?</li>
      <li>Do you want pagination on your entity?</li>
    </ol>
  </li>
 </ul>

<hr/>

<ul>
  <li><h3><b>Creating Controller</b></h3>
    <ol>
      <li>jhipster spring-controller <ControllerName></li>
      <li>Do you want to add an action to your controller?</li>
      <li>What is the name of your action?</li>
      <li>What is the HTTP method of your action?</li>
    </ol>
  </li>
</ul>


<hr/>
<b><h3># Generating Complete Application</h3></b>

https://start.jhipster.tech/#/  -- For GUI
