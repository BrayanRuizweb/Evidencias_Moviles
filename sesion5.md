<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 5 


<!-- Su documentación aquí -->

#### Actividad: Implementación de las Clases Automóvil y Motocicleta utilizando la herencia en java
>
>
>Implementar las clases derivadas (Automovil y Motocicleta) que hereden de la clase base (Vehiculo) en Java.
>
~~~
    class Vehiculo {
        protected String marca; // Cambiamos a protegido
        protected String modelo; // Cambiamos a protegido
        private int año;

        public Vehiculo(String marca, String modelo, int año) {
            this.marca = marca;
            this.modelo = modelo;
            this.año = año;
        }

        public void mostrarInformacion() {
            System.out.println("Marca: " + marca);
            System.out.println("Modelo: " + modelo);
            System.out.println("Año: " + año);
        }
    }
    ~~~

