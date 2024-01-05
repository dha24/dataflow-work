# dataflow-work
repo contains pipelines for java and python both to submit the job on dataflow


## dataflow-work

mvn archetype:generate \
  -DarchetypeArtifactId=google-cloud-dataflow-java-archetypes-starter \
  -DarchetypeGroupId=com.google.cloud.dataflow \
  -DgroupId=com.example.pipelinesrus.newidea \
  -DartifactId=newidea \
  -Dversion="[1.0.0,2.0.0]" \
  -DinteractiveMode=false


  
mvn compile -e exec:java \
 -Dexec.mainClass=Grep
