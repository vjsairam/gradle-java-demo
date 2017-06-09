## Synopsis

Este proyecto fue creado para mostrar el uso de gradle para construir aplicaciones java, y ejecutar test unitarios.

## Instalación

Clonar proyecto

	git clone https://github.com/rabadiaz/gradle-java-demo

NOTA: para este procedimiento debe tener instalado el comando git

## Pruebas

Una vez clonado el proyecto podemos ejecutar el build y esto ejecutara automaticamente los tests, el comando a ejecutar es gradle wrapper.

a.- En Linux ejecutamos:
	
	./gradlew build

b.- En Windows ejecutamos:
	
	gradlew build 

Los resultados de los test unitarios se encuentran en el archivo 

	build/test-results/test/TEST-AppTest.xml

Tambien es generado un archivo html con el reporte de los test:

	build/reports/tests/test/index.html
