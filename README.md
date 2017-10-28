# test
Refactor of RealizarSimulacion class

To compile, you will need to install in your .m2 repo this tree jars:

* rest_simulacionpoliza-2.15.0.jar
* scontratacion-1.19.0.jar
* ws_contratacion-1.2.28.jar

(for security reasons are not included)

Example: mvn install:install-file -Dfile=scontratacion-1.19.0.jar -DgroupId=sanitas.bravo.clientes -DartifactId=scontratacion -Dversion=1.19.0 -Dpackaging=jar

To create final jar -> mvn clean package
