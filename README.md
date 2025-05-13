# desafio8

# questao 1
```java
        Scanner ler = new Scanner (System.in);
        
        System.out.println("Digite um número inteiro: ");
        int numero1 = ler.nextInt();
        System.out.println("Digite outro número inteiro: ");
        int numero2 = ler.nextInt();
        System.out.println("Digite mais um número inteiro: ");
        int numero3 = ler.nextInt();
        mostrarMaior(numero1, numero2, numero3);
    }
    public static void mostrarMaior( int numero1, int numero2, int numero3 ) {
        if ( numero1 == numero2 && numero1 == numero3 && numero2 == numero3 ) {
            System.out.println("TODOS NÚMEROS SÃO IGUAIS");
        } else {
        if ( numero1 > numero2 && numero1 > numero3 ) {
            System.out.println("Primeiro número MAIOR: "+numero1);       
        } else if ( numero2 > numero1 && numero2 > numero3 ) {
            System.out.println("Segundo número MAIOR: "+numero2);
        } else {
            System.out.println("Terceiro número MAIOR: "+numero3);
```
# questao2 
```java
        Scanner ler = new Scanner (System.in);
        
        System.out.println("Digite uma palavra: ");
        String palavra = ler.next();
        converteMaiusculaEConta ( palavra );
    }
    public static void converteMaiusculaEConta ( String palavra )  {
        System.out.println(palavra.toUpperCase());
        System.out.println(palavra.length()+" caracteres");
```
# questao3
```java
        Scanner ler = new Scanner(System.in);

        System.out.println("Digite um número: ");
        int numero = ler.nextInt();
        somarLista(numero);
    }
    public static void somarLista(int numero) {
        int x = 0;
        int soma = 0;
        while (x < numero) {
        x++;
        soma = soma + x;
        }
        System.out.println("A soma dos números é "+soma);
```
# questao4
```java
