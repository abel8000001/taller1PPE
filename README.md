Taller 1 - Plataformas de Programación Empresarial.

Es una aplicacion web hecha en Java Spring con Gradle. Elegí este framework porque es el que hemos estado trabajando en clase.

Para ejecutarse localmente, se debe contar con Java y Git (opcional)

Verificar si Java está instalado
  java -version

(opcional) clonar y abrir el repo
  git clone <repo-url>
  cd <repo-name>

Ejecutar la app directamente con Gradle
  .\gradlew.bat bootRun

O hacer build manual y ejecutar el .jar
  .\gradlew.bat build
  java -jar build\libs\*.jar

Ejecutar tests
  .\gradlew.bat test

Abrir la app en el buscador
  Start-Process "http://localhost:8080/"
