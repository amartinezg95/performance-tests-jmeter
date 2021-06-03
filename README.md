# Performance tests

Ejemplo de comando para ejecutar el test de rendimiento (se debe ejecutar dede el bin de jmeter, el fichero .csv se crea solo, y cada vez que ejecutes hay q borrar el .csv y la carpeta report que se genera. Dentro de la carpeta report está el html):


```jmeter -n -t "c:\Users\alejc\Documents\github\performance-tests-jmeter\performance-test.jmx" -Jthreads=100 -Jduration=120 -Jrpm=120  -l "c:/Users/alejc/Documents/github/performance-tests-jmeter/result.csv" -e -o "c:/Users/alejc/Documents/github/performance-tests-jmeter/report"```

threads representa el número de hilos

duration la duración del test

rpm representa el número de peticiones por minuto que se quieren realizar.

