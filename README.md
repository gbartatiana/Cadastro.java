# Cadastro.java
Exercicio Aula JAVA Fuctura

import java.util.Scanner;

public class Cadastro{

	public static void main (String args[]){

	Scanner form = new Scanner(System.in);

	System.out.println("************************");
	System.out.println("**** SEJA BEM-VINDO ****");
	System.out.println("************************");



	System.out.println("Informe seu nome:");
	String nome = form.nextLine();


	System.out.println("Informe seu cpf:");
	String cpf = form.nextLine();


	System.out.println("Informe sua idade:");
	int idade = form.nextInt();


	System.out.println("Informe sua altura:");
	double altura = form.nextDouble();

		System.out.println();
		System.out.println("*****************************");
		System.out.println("NOME: " + nome);
		System.out.println("CPF: " + cpf);
		System.out.println("IDADE: " + idade);
		System.out.println("ALTURA: " + altura);
		System.out.println("*****************************");
	}//end main
}//end class Cadastro


