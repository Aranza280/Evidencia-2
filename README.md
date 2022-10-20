# Evidencia-2
package avance.pkg2.evidencia.pkg1;
import java.util.Scanner;
public class Avance2Evidencia1 {
   public static void main(String[] args) {
       Scanner leer = new Scanner(System.in);
      int id _unico, id_paciente, id _doc, id _cita, op;
      String nom _paciente, nom _doc, especialidad, motivo _cita, fecha_cita, hora _cita;
      System.out.println("Escoga una opción");
      System.out.printIn("1. Alta de Doctor");
      System.out.println("2. Alta paciente");
      System.out.println("3. Crear cita");
      op = leer.nextInt();

      if (op==1)f
          System.out.println("Ingrese el id del Doctor");
          id doc = leer.nextint();
          System.out.printin("Ingrese nombre completo del Doctor");
          nom_doc = leer.nextLine();
          System.out.printin("Ingrese especialidad");
          especialidad = leer.nextLine();
          System.out.printin("¡Alta exitosa!");
     }

       if (op==2){
            System.out.printIn("Ingrese el id del paciente");
            id paciente = leer.nextint();
            System.out.printIn("Ingrese nombre completo del paciente");
            nom_paciente = leer.nextLine();
            System.out.printIn("¡Alta exitosa!");
}


        if (op==3){
            System.out.println("Ingrese id de la cita");
            id_cita = leer.nextint();
            System.out.printin("ingrese fecha de la cita");
            fecha cita = leer.nextLine();
            System.out. printin("'Ingrese hora de la cita").
            hora cita = leer.nextLine ();
            System.out.printIn("Ingrese motivo de la cita");
            motivo_cita = leer.nextLine();
            System.out.println(“¡Cita registrada!”);
         }
     }
 }
