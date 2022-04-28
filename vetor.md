# EstudoVetor

```java
import java.util.Arrays;
import java.util.Locale;
import java.util.Scanner;

public class Teste {

	public static void main(String[] args) {

		// pode ser declarado desta forma
		// String[] cars;

		// pode ser declarado e inicializado
		String[] cars = { "Fusca", "Gol", "Palio" };

		// imprime primeira posição de um vetor
		System.out.println(cars[0]);

		// para alterar um valor, deve consultar o indice
		cars[0] = "Argo";

		// nova saida
		System.out.println(cars[0]);

		// para imprimir quantos deu elementos tem em um array
		System.out.println(cars.length);

		// utilize Arrays.fill para preencher um array por completo
		Arrays.fill(cars, "Uno");

		// agora toda frota de carro é formada por uno
		System.out.println(cars[0]);

		// para vizualizar o vetor inteiro, utiliza o método tostring, se não tiver sido
		// modificado
		System.out.println(Arrays.toString(cars));

		// encontrando primeira posição vazia e preenchendo o valor
		String vagas[] = { "Ocupado", "Vazio", "Ocupado" };

		System.out.println(Arrays.toString(vagas));

		for (String c : vagas) {
			for (int i = 0; i < vagas.length; i++) {
				if (c == "Vazio") {
					vagas[i] = "Ocupado";
					System.out.println("Indice: " + i + " " + vagas[i]);
				}

			}
		}
		
		

		System.out.println(Arrays.toString(vagas));
		
		

//		referencias
//		https://www.geeksforgeeks.org/arrays-fill-java-examples/
//		https://blog.betrybe.com/java-foreach/

	}
}
```
