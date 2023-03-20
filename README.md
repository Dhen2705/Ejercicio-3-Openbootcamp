# Ejercicio-3-Openbootcamp
Ejercicio Tema 3 Openbootcamp Introducción a la programación

Primera parte:

Crear una función con tres parámetros que sean números que se suman entre sí.
Llamar a la función en el main y darle valores.

Segunda parte:

Crear una clase coche.
Dentro de la clase coche, una variable numérica que almacene el número de puertas que tiene.
Una función que incremente el número de puertas que tiene el coche.
Crear un objeto miCoche en el main y añadirle una puerta.
Mostrar el número de puertas que tiene el objeto.



public class Main { public static void main(String[] args) { int resultado; resultado = suma(8,4,6); System.out.println(resultado); }

    public static int suma (int a, int b, int c ) {
        return  a + b + c;

    }
}


public class Coche {

    public int puertas = 0;

    public static void main(String[] args) {
        Coche miCoche = new Coche();
        miCoche.SumarPuerta();
        miCoche.SumarPuerta();
        miCoche.SumarPuerta();
        miCoche.SumarPuerta();
        System.out.println(miCoche.puertas);
    }
    public void SumarPuerta() {
        this.puertas++;
    }
}
