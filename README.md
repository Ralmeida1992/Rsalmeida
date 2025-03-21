import java.util.Scanner;

public class Exemplo02 {
   public Exemplo02() {
   }

   public static void main(String[] var0) {
      Scanner var1 = new Scanner(System.in);
      System.out.println("Informe dois numeros: ");
      int var2 = var1.nextInt();
      int var3 = var1.nextInt();
      if (var2 > var3) {
         System.out.println(" Qual numero é o maior: " + var2);
      }

      if (var3 > var2) {
         System.out.println(" Qual numero é o maior: " + var3);
      }

   }
}
      SENHA

import java.util.Scanner;
public class Senha {
    public static void main (String[] args) {

        Scanner in = new Scanner (System.in);
        int n1;

        System.out.println("Informe a senha: ");
        n1 = in.nextInt();
        
        if (n1 != 1234) {
            System.out.println("Senha incorreta: ");
        }
        else{
            System.out.println("Senha correta: ");
        }
    
            
    }


        

}


Exemplocondicao.java (if
import java.util.Scanner;
public class Exemplocondicao {
    public static void main (String[] args) {

        Scanner in = new Scanner (System.in);
        int idade;

        System.out.println("informe sua idade");
        idade = in.nextInt();

        // se a idade é maior ou igual a 18 
        if (idade >= 18 ){
        System.out.println("EH MAIOR DE IDADE");
        }
        // se a idade é menor que 18
        else {
            System.out.println("EH MENOR DE IDADE");

        }

       

    }
}


