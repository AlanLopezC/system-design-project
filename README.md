En caso de no tener carpeta lib/javafx-17.0.1:
Hay que agregar carpeta lib/javafx-17.0.1



Comands:

cd src

javac --module-path ../lib/javafx-sdk-17.0.1/lib/ --add-modules javafx.base,javafx.graphics,javafx.controls,javafx.fxml Prueba.java

para las terminales :

java --module-path ../lib/javafx-sdk-17.0.1/lib/ --add-modules javafx.base,javafx.graphics,javafx.controls,javafx.fxml Prueba
