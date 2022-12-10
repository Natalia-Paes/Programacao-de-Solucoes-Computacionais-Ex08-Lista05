# Programacao-de-Solucoes-Computacionais-Ex08-Lista05
Faça uma função que informe a quantidade de dígitos de um determinado número inteiro informado.
import java.util.Scanner;

public class Ex08 {
    public static void main(String[] args) throws Exception {
        Scanner sc = new Scanner(System.in);
        System.out.println("Informe um número inteiro: ");
        int number = sc.nextInt();
        sc.close();
        System.out.println("O número informado" + number + ", possui " + qtdDigitos(number) + " digitos.");
    }

    public static int qtdDigitos(int x) {
        String digitos = Integer.toString(x);
        return digitos.length();
    }
}
