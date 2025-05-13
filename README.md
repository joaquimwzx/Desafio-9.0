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
package desafio9;

public class Desafio9 {

    public static void main(String[] args) {
        int[] eInteiros = {1, 2, 3, 4, 5, 6, 7, 8, 9, 10};
        for (int elemento : eInteiros) {
            System.out.println(elemento);
        }
        for (int i = eInteiros.length - 1; i >= 0; i--) {
            System.out.println(eInteiros[i]);
        }
    }

}
```
# Questao 4
```java
package desafio9;
import java.util.Scanner;

public class Desafio9 {

    public static void main(String[] args) {
        Scanner ler = new Scanner(System.in);
        int[] nInteiros = new int[10];
        int i, cN = 0;

        for (i = 0; i < nInteiros.length; i++) {
            System.out.println("Digite um numero");
            nInteiros[i] = ler.nextInt();
            if (nInteiros[i] < 0) {
                cN++;
            }

        }
        System.out.println("A quantidade de numeros negativos é:" + cN);
    }

}
```
# Questao 5
```java
package desafio9;


public class Desafio9 {

    public static void main(String[] args) {
        int[] nI = {1, 2, 3, 4, 5, 6, 7, 8, 9, 10};
        for (int i = 0; i < nI.length; i++) {
            System.out.println(nI[i] + "x" + 2 + " = " + (nI[i] * 2));
        }
    }

}
```
# Questao 6
```java
package desafio9;

import java.util.Scanner;

public class Desafio9 {

    public static void main(String[] args) {
        Scanner ler = new Scanner(System.in);
        int i;
        int[] nI = new int[10];
        for (i = 0; i < nI.length; i++) {
            System.out.println("Digite um numero:");
            nI[i] = ler.nextInt();
            if (nI[i] < 0) {
                nI[i] = 0;
            }
        }
        System.out.println("Resultado");
        for (i = 0; i < nI.length; i++) {
            System.out.println(nI[i]);
        }
    }

}
```
# Questao 7
```java
package desafio9;

import java.util.Scanner;
public class Desafio9 {

    public static void main(String[] args) {
        Scanner ler = new Scanner(System.in);
        int[] nota = new int[10];
        int i, soma = 0, media;
        for (i = 0; i < nota.length; i++) {
            System.out.println("Digite a nota:" + (i + 1) + ":");
            nota[i] = ler.nextInt();
            soma += nota[i];
        }

        media = soma / nota.length;
        System.out.println("\nMedia das notas:" + media);

        System.out.println("As notas maiores que a media é");
        for (i = 0; i < nota.length; i++) {
            if (nota[i] > media) {
                System.out.println("nota " + (i + 1) + ":" + nota[i]);
            }
        }
    }

}
```
# Questao 8
```java
