# El-rinc-n-del-friki
## 1. Fundamentos del sistema
La idea sería que dentro de un juego multijugador en cooperativo haya una página en la que puedas comunicarte con otros para intercambiar objetos y comunicarse para hacer raids, y  que todo esto pueden hacerlo con varios juegos. Tambien tendra una suscripción de pago que le de ventajas a los usuarios que la pagen.

## 2. Análisis y especificación de requisitos

Funcionales:
Los usuarios deben iniciar sesión con su correo y si es posible enlazar la aplicación con el juego para que los usuarios puedan ver desde el juego el objeto para intercambiar
Cada usuario podrá crear ofertas y podrá interactuar con las ofertas de los demás, si  un usuario se guarda una oferta no se ocultara a los demás usuarios, si hay muchos usuarios interesados en una oferta se podrá hacer una puja.
También para querer ampliarlo al máximo, en los chat habrá un traductor de idiomas que traducirá  al idioma del dispositivo para que se puedan comunicar aunque no hablen el mismo idioma.
Es importante que los usuarios se puedan comunicar por medio de la aplicación/pagina web para negociar y para comunicarse para hacer las raids pero esto se hará solo por texto, no habrá chat de voz.  

No funcionales:
La aplicación debe de ser capaza de soportar todas las consultas 
A la hoara de iniciar sesión los mensajes se tienen que enviar en menos de 5s y tanto la página como la aplicación tiene que mantener la sesión iniciada.


## 3. Diseño


## 4. Implementación
public class hola{

    public static void main(String[] args) {

       System.out.println("Hola mundo");

        if(true){
            System.out.println("Condición verdadera");
        }else{
            System.out.println("Condición falsa");
        }
    
    }
}
public class area{

    public static void main(String[] args){
        
        double r=5;
        double Pi=3.14159;
        double area=Pi*r*r;
        
        System.out.println("el area es "+area);
    }
}
public class OperacionesMatematicas {

    public static int SumarNumeros(int NumeroUno, int NumeroDos){
        return NumeroUno+NumeroDos;
    }

    public static int RESTAR(int A, int B){
        return A-B;
    }

    public static int multiplicacion(int NUM1,int num2){
        return NUM1*num2;
    }

    public static int DivisionDeEnteros(int dividendo, int divisor){
        return dividendo/divisor;
    }

    public static void main(String[] args){
    
        System.out.println(SumarNumeros(3,4));
        System.out.println(RESTAR(5,2));
        System.out.println(multiplicacion(2,6));
        System.out.println(DivisionDeEnteros(8,2));
    }
}
public class Corrigiendo {

    public class alumno{
        private String NOMBRE;
        private int edad;private double NotaFinal;
        public alumno(String n,int e,double nf){
            NOMBRE=n;edad=e;NotaFinal=nf;
        }
        public void Mostrardatos(){
            System.out.println("Alumno: "+NOMBRE+", Edad:"+edad+", Nota Final:"+NotaFinal);
        }
        public boolean aprobado(){
            if(NotaFinal>=5.0){
                return true;
            }else{
                return false;
            }
        }
        public void mensajeFinal(){
            if(aprobado()){
                System.out.println("felicidades "+NOMBRE+" aprobaste!");
            }
            else{
                System.out.println("Lo siento "+NOMBRE+" no aprobaste");
            }
        }
}

    class curso{
       private String NOMBRE_CURSO;
    private alumno[] lista;
    public curso(String n, alumno[] l){
        NOMBRE_CURSO=n;lista=l;
    }
    public void mostrarTodo(){
        System.out.println("curso: "+NOMBRE_CURSO);
        for(alumno a:lista){
            a.Mostrardatos();a.mensajeFinal();
        }
    }
    }
    public static void main(String[] args){
        alumno a1 = new alumno("ana",18,6.5);
        alumno a2 = new alumno("PEDRO",19,4.3);
        alumno a3 = new alumno("Lucia",17,8.7);
        alumno [] lista = {a1,a2,a3};
        curso c1 = new curso("programacion",lista);
    c1.mostrarTodo();
    }
    
    
}

## 5. Plan de pruebas del sistema
Añade aquí lo que hicimos para diseñar las pruebas

### 5.1. Pruebas de aceptación


## 7. Los diccionarios de datos
