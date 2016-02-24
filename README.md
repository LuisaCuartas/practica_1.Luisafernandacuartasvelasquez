# practica_1.Luisafernandacuartasvelasquez
 package Práctica_1;

import java.util.Scanner;

    public class Práctica_1 {
    
        private Scanner teclado;

    public Práctica_1(string nombre) {
        this.nombre = nombre;
    }
        private string nombre;
        private string apellido;
        private int fechanacimiento;
        private int cedula;
        private int direccion;
        private int telefono;
        private string areas;
        
        public void inicializar(){
            
            teclado = new Scanner(System.in);
            System.out.println("digite su nombre: ");
            nombre = teclado.next();
            System.out.println("digite su fecha de nacimiento: ");
            fechanacimiento = teclado.nextInt();
            System.out.println("cual es su area favorita: ");
            areas = teclado.next();
        }
        
        public void imprimir(){
             System.out.println("nombre:"+nombre);
             System.out.println("fecha de nacimiento:"+fechanacimiento);
             System.out.println("area favorita:"+areas);
        }
             public void personanueva(){
                 if(nombre
             }  
            
     
       
    }
