import java.util.Scanner;
public class Main {
    static Scanner ler= new Scanner(System.in);
    public static void main(String[] args){
        int opcao;
        do {
            menu();
            opcao = ler.nextInt();
            interpretarOpcao(opcao);
        } while (opcao != 0);
    }
    public static void menu(){
        System.out.print("----------ATRIBUIÇÃO DE PROJETOS DE ESTÁGIO ----------\n" +
                "1 -Carregar dados dos ficheiros\n" +
                "2 - Listar estudantes por pontuação\n" +
                "3 - Listar projetos\n" +
                "4 - Listar projetos por procura\n" +
                "5 -Executar atribuiçãode projetos\n" +
                "6 -Consultar estudantes colocados\n" +
                "7 -Consultar estudantes não colocados\n" +
                "8 -Consultar projetos com vagas disponíveis\n" +
                "9 -Apresentar estatísticas\n" +
                "10 -Guardar resultados em ficheiros\n" +
                "0 -Sair\n"+
                "Digite a opção do menu:");
    }
    public static void interpretarOpcao(int opcao){
        switch (opcao){
            case 1:
                break;
            case 2:
                break;
            case  3:
                break;
            case  4:
                break;
            case  5:
                break;
            case  6:
                break;
            case  7:
                break;
            case  8:
                break;
            case  9:
                break;
            case  10:
                break;
            case  0:
                System.out.print("A sair.");
                break;
            default:
                System.out.print("Numero da opção errada.");
                break;
        }
    }
    public static int verificarInt(int num){
        while(num<0){
            System.out.print("Número inválido. Digite novamente:");
            num= ler.nextInt();
        }
        return num;
    }
}
