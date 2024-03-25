import java.util.Scanner;
public class Main {
  public static void main(String[] args) {
    // declarar variaveis
    float nota;
    Scanner entrada = new Scanner(System.in);
    // ler nota
    do{
      System.out.print("Informe a nota: ");
      nota = entrada.nextFloat();
      if(nota < 0 || nota > 10){
        System.out.println("Nota inválida!");
      }
    } while(nota < 0 || nota > 10);
    System.out.println("Você digitou a nota: "+ nota);

    entrada.close();
  }
}
  
