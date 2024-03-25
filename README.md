import java.util.Scanner;




public class peso {

public static void main(String[] args){

     Scanner teclado = new Scanner(System.in);
     
     int opção; 
     
     double altura;
     
     System.out.println("insira uma opção de 1 para homem e 2 para mulher " );
     
     opção = teclado.nextInt();
     
     if(opção<1 || opção>2) System.out.println("esse numero é invalido deve ser o valor 1 ou 2 " );
     
      else {
         
         
         System.out.println("Insira a sua altura ");
     
     altura = teclado.nextDouble();     
     
     if (opção == 1 ) {
     
     System.out.println("o seu peso ideal é: "+ 72.7 * +altura+ -58); 
     
     
        } else if (opção == 1 ) {
            
    System.out.println("o seu peso ideal é: "+  62.1 * +altura+ -44,7);
    
    }

}

}

}
     
