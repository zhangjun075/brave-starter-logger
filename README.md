mvn deploy:deploy-file -DgroupId=com.brave.log \
  -DartifactId=brave-starter-logger \
  -Dversion=1.4-SNAPSHOT \
  -Dpackaging=jar \
  -Dfile=./target/brave-starter-logger-1.4-SNAPSHOT.jar \
  -DrepositoryId=ppdai \
  -Durl=http://maven.repo.ppdai.com/nexus/content/repositories/snapshots/