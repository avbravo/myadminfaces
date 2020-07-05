# myadminfaces
myadminfaces jsf project


Para crear un uberjar
java -jar payara-micro-5.2020.2.jar --deploy myadminfaces.war --outputUberJar elsa.jar

#Crear  el Uberjar
java -jar    /home/avbravo/software/payara/payara-micro-5.2020.2.jar --deploy /home/avbravo/NetBeansProjects/secund/myadminfaces/target/myadminfaces.war --outputUberJar /home/avbravo/Descargas/myadminfaces.jar


#Ejecutar el war

java -jar -Xmx512m /home/avbravo/software/payara/payara-micro-5.2020.2.jar  --deploy /home/avbravo/NetBeansProjects/secund/myadminfaces/target/myadminfaces.war --nocluster --logo --port 8081

