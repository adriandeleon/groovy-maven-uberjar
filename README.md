Create a Groovy UberJar.

Open the pom.xml and modify the following line:

        `<mainClass>com.sample.groovy.uberjar.nameOfScript</mainClass>`

Run `mvn package` to create the uberjar. The jar will be generated in the target/ folder.

to run the jar, use `java -jar myproject-0.0.1-SNAPSHOT-standalone.jar`
