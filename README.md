# Desafio-9.0
# Questao 1
package projetovetores;

import java.util.Scanner;
```java
public class ProjetoVetores {

    public static void main(String[] args) {
        Scanner ler = new Scanner(System.in);
        int[] v = new int[10];
        int i, cn100 = 0;

        for (i = 0; i < v.length; i++) {
            System.out.println("Digite um numero:");
            v[i] = ler.nextInt();
            if (v[i] > 100) {
                cn100++;
            }
        }
        System.out.println("O vetor possui:" + cn100 + " valores maiores que 100");
    }

}
```
# Questao 2
package projetovetores;
```java
public class ProjetoVetores {

    public static void main(String[] args) {
        int[] nInteiros = {1, 2, 3, 4, 5, 6, 7, 8, 9, 10};
        int soma = 0;
        for (int i = 0; i < nInteiros.length; i++) {
            soma += nInteiros[i];
        }
        System.out.println("a soma dos numeros dentro dos vetores é:" + soma);

    }

}
```
# Questao 3
```java
