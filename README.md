//pacote main
package main;
//importação de pacote
import java.util.Scanner;
 
//classe
public class Main {
 public static void main(String[] args) {
   
   //scanner  
   Scanner leitura = new Scanner(System.in);
   
   //variável  
   Produto p = new Produto();
 
   //dando nome para as variáveis
   System.out.println("Suco em pó");
   System.out.println("Tang");
   p.nome = leitura.nextLine();
 
   //dando um preço para as variáveis
   System.out.println(1.20);
   p.preco = leitura.nextDouble();
 
   //dando quantidade para as variáveis
   System.out.println(10);
   p.quantidade = leitura.nextInt();
 
   //imprimindo os resultados
   System.out.println("Suco em pó"+p.imprimir());
 
   System.out.println("Suco em pó");
   int qtd = leitura.nextInt();
   p.adicionarProdutos(qtd);
   system.out.println(""+ p.imprimir());
 
   system.out.println(10);
   qtd = leitura.nextInt();
   p.removerProdutos(qtd);
   System.out.pirntln("" + p.imprimir());
  }
}
