# Dia.semana
Esse é um programa em java que recebe um número e informa qual dia da semana é.

package principal;

import java.util.Scanner;

public class Principal {

	public static void main(String[] args) {
		
		Scanner sc = new Scanner(System.in);
		
		int x;
		String dia;
		
		System.out.println("Informe o numero para saber que dia da semana é:");
		x = sc.nextInt();
		
		switch(x){
			case 1:
				dia = "domingo";
				break;
			case 2:
				dia = "segunda";
				break;
			case 3:
				dia = "terça";
				break;
			case 4:
				dia = "quarta";
				break;
			case 5:
				dia = "quinta";
				break;
			case 6:
				dia = " sexta";
				break;
			case 7:
				dia = "sábado";
				break;
			default:
				dia = "Valor Invalido ";
				break;
		}
		
		System.out.printf("O dia da semana é "+ dia );
		
	}

}
