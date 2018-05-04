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
</ul>
