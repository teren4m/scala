# scala


mvn archetype:generate -DarchetypeGroupId=net.alchim31.maven -DarchetypeArtifactId=scala-archetype-simple
mvn package

mvn dependency:copy-dependencies
mvn clean
mvn package