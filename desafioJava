import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        String nome = "Leticia Pagliato";
        String tipoConta = "corrente";
        double saldo = 1599.99;

        System.out.println("*************************************");
        System.out.println("\nNome do cliente: "+ nome);
        System.out.println("Tipo de conta: " + tipoConta);
        System.out.println("Saldo atual: "+ saldo);
        System.out.println("\n*************************************");
          
        String menu = """
                ** Digite sua opção: **
                1 - Consultar saldo
                2 - Transferir
                3 - Receber
                4 - Sair
                """;
        int opcao = 0;
        Scanner leitura = new Scanner(System.in);
        while (opcao != 4) {
            System.out.println(menu);
            opcao = leitura.nextInt();
        if (opcao == 1){
            System.out.println("O saldo atual é: " + saldo);
        } else if (opcao == 2){
            System.out.println("Qual valor de transferencia? ");
            double valor = leitura.nextDouble();
            if (valor > saldo) {
                System.out.println("Não há saldo suficiente");
            } else {
                saldo -= valor;
                System.out.println("Novo saldo: "+saldo);
            }
        } else if (opcao == 3){
            System.out.println("Valor recebido: ");
            double valor = leitura.nextDouble();
            saldo += valor;
            System.out.println("Novo saldo: "+saldo);
        } else if (opcao != 4) {
            System.out.println("Opção inválida!");
            
         }
       }
    }
}
