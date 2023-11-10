# 01Vetor
01Vetor

package exemplos;

public class Exemplo01Vetor {

	public static void main(String[] args) {
		String[] carro = {"gol" , "santana" , "fusca" , "puma"};
		System.out.println(carro[0]);
		
		carro[3]= "marea";
		System.out.println(carro[3]);
		
		int [] numero= {12,3,4,6,7};
		System.out.println(numero[4]);
		System.out.println(numero.length);
		
		String []nome= {"Jailson", "andre", "rafael", "daniel", "maria"};
		
		for (int i = 0; i < nome.length; i++) {
			System.out.println(nome[i]);
		}


	}

}
