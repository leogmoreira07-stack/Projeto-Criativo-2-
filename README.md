# Projeto-Criativo-2-
Projeto de Banco em Java 2
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        String operacao = scanner.nextLine();

        // Validação exata, respeitando maiúsculas e minúsculas.
        boolean operacaoValida =
                operacao.equals("DEPOSITO") ||
                operacao.equals("SAQUE") ||
                operacao.equals("TRANSFERENCIA");

        System.out.println(operacaoValida ? "VALID" : "INVALID");

        scanner.close();
    }
}
