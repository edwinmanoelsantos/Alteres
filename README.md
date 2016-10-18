import java.util.ArrayList;
import java.util.List;
import java.util.Scanner;


public class ListaInversa {
	public int indice;
	public String palavra;
	public String letra1;
	public String letra2;
	public String letra3;
	public String letra4;
	public List inicio;
	public List fim;
	List<String> palavra0 = new ArrayList();
	public Object anterior;

	public static class main{
	public static void main(String [] args) {
		Scanner teclado = new Scanner(System.in);
		
		System.out.println("Digite a Primeira letra");
		ListaInversa posicao1 = new ListaInversa();
		posicao1.indice = 0;
		posicao1.letra1 = teclado.next();
		
		System.out.println("Digite a Segunda letra");
		ListaInversa posicao2 = new ListaInversa();
		posicao2.indice = 1;
		posicao2.letra2 = teclado.next();;
		
		System.out.println("Digite a Terceira letra");
		ListaInversa posicao3 = new ListaInversa();
		posicao3.indice = 2;
		posicao3.letra3 = teclado.next();;
		
		System.out.println("Digite a Quarta letra");
		ListaInversa posicao4 = new ListaInversa();
		posicao4.indice = 3;
		posicao4.letra4 = teclado.next();;
		
		
		for(int n = 4; n >= 0; n--){
		System.out.println("palavra");
	
		}
	}
	}

}
