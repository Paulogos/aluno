# aluno
testes iniciais DAS
import java.util.Scanner;

public class OitoNumeros {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        // Solicita a entrada do usuário
        System.out.print("Digite um número: ");
        int numero = scanner.nextInt();

        System.out.println("\nOs oito primeiros números a partir de " + numero + " são:");

        // Loop para exibir os 8 números seguintes
        for (int i = 0; i < 8; i++) {
            System.out.println(numero + i);
        }

        scanner.close();
    }
}
