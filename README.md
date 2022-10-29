# renovate-bumpversion-mvn
Renovate Bug in bumpVersion

## Expected 
Valid xml with updated version.

````xml
   <keycloak.version>19.0.3</keycloak.version>
   <springdoc-openapi.version>1.5.7</springdoc-openapi.version>
````

## Results
invalid xml like

````xml
   <keycloak.version>19.0.3</k19.0.3</springdoc-openapi.version>
````

