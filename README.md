# PrimoEsempio
package it.bitcamp.renato.eserciziofizzbuzz;

public class EsericizioFizzBuzz {

	public static void main(String[] args) {
		int i;
		for (i = 1; i <= 100; i++) {
			System.out.println(i);
			if (i % 3 == 0) {
				System.out.println("Fizz");
			} else if (i % 5 == 0) {
				System.out.println("Fuzz");
			} else if (i % 3 == 0 && i % 5 == 0) {
				System.out.println("Fizz Buzz");
			} else {
				System.out.println("Non esiste nessun Fizz Buzz");
			}
		}
	}
}
