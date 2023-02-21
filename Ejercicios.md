# Ejercicio-2-OpenBootcamp
OpenBootcamp
int numeroIf = 10;

if (numeroIf > 0) {
    System.out.println("El número es positivo");
} else if (numeroIf < 0) {
    System.out.println("El número es negativo");
} else {
    System.out.println("El número es cero");
}
-----------------------------------------------------------------------------------
int numeroWhile = 0; // inicializamos la variable en cero

while(numeroWhile < 3) { // mientras la variable sea menor que 3
  numeroWhile++; // incrementamos el valor en uno en cada iteración
  System.out.println("El valor actual de numeroWhile es: " + numeroWhile); // mostramos el valor por pantalla
}
-----------------------------------------------------------------------------------
do {
  // Cuerpo del bucle
} while(false);
------------------------------------------------------------------------------------
for (int numeroFor = 0; numeroFor <= 3; numeroFor++) {
    System.out.println(numeroFor);
}
------------------------------------------------------------------------------------
// Definir la variable "estacion"
String estacion = "verano";

// Evaluar el valor de "estacion" utilizando un switch
switch (estacion) {
  case "primavera":
    System.out.println("Es primavera.");
    break;
  case "verano":
    System.out.println("Es verano.");
    break;
  case "otoño":
    System.out.println("Es otoño.");
    break;
  case "invierno":
    System.out.println("Es invierno.");
    break;
  default:
    System.out.println("La estación especificada no es válida.");
    break;
}
