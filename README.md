# solidify
Estudos práticos sobre os princípios SOLID

## Base para criação de projetos
 - Single Responsability Principle : srp
 - Open Closed Principle: ocp
 - Liskov Substituition Principle: lsp
 - Interface Segregation Principle: isp
 - Dependency Inversion: di

```sh
$ mvn archetype:generate \
  -DgroupId=br.com.cpdias.solid \
  -DartifactId=single-responsability \
  -Dpackage=br.com.cpdias.solid.srp \
  -DarchetypeArtifactId=maven-archetype-quickstart \
  -DarchetypeVersion=1.4 \
  -DinteractiveMode=false

```
-------------------------------------------------------------------------------
https://www.youtube.com/shorts/bu79EVKoCyg?feature=share

------------------------------------------------------------------------------
ARTEMIS_FILE="https://downloads.apache.org/activemq/activemq-artemis/2.31.0/apache-artemis-2.31.0-bin.zip"
ARTEMIS_APP="artemis"

curl $ARTEMIS_FILE  --output ${ARTEMIS_APP}.zip
unzip ${ARTEMIS_APP}.zip
mv apache-artemis-2.31.0 ${ARTEMIS_APP}

rm -rf ${ARTEMIS_APP}/examples

rm ${ARTEMIS_APP}.zip

#https://1kevinson.com/springboot-artemis-broker/
