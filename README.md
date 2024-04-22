# Suma

La clase Suma proporciona un método para sumar dos números enteros.

## Uso

// Crear una instancia de la clase Suma
Suma suma = new Suma();

// Definir dos números enteros para sumar
int num1 = 5;
int num2 = 3;

// Llamar al método sumar y mostrar el resultado
int resultado = suma.sumar(num1, num2);
System.out.println("La suma de " + num1 + " y " + num2 + " es: " + resultado);




## Método sumar

El método sumar toma dos números enteros como parámetros y devuelve su suma.

java

/**
 * El método suma dos números enteros y devuelve el resultado.
 *
 * @param a El primer número entero a sumar.
 * @param b El segundo número entero a sumar.
 * @return El resultado de la suma de a y b.
 */
public int sumar(int a, int b) {
    return a + b;
}


## Ejemplo de uso

        
Definir dos números enteros para sumar
        int num1 = 5;
        int num2 = 3;
        
  Llamar al método sumar y mostrar el resultado
        int resultado = suma.sumar(num1, num2);
        System.out.println("La suma de " + num1 + " y " + num2 + " es: " + resultado);



## Autor: Biemil Seydiev Sadakov.
