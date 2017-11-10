# demoGWT2.7.0
Proyecto inicial de GWT

Creado a partir de arquetipo:

 mvn archetype:generate \
   -DarchetypeGroupId=org.codehaus.mojo \
   -DarchetypeArtifactId=gwt-maven-plugin \
   -DarchetypeVersion=2.7.0
   
También se agregó:

    <dependency>
      <groupId>com.google.gwt</groupId>
      <artifactId>gwt-codeserver</artifactId>
      <scope>provided</scope>
    </dependency>
