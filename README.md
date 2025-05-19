# desafio8

# questao1
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
        Scanner ler = new Scanner(System.in);
        DecimalFormat decimal = new DecimalFormat ("0.00");

        System.out.println("Digite o 1º número fracionário: ");
        double n1 = ler.nextDouble();
        System.out.println("Digite o 2º número fracionário: ");
        double n2 = ler.nextDouble();
        System.out.println("Digite o 3º número fracionário: ");
        double n3 = ler.nextDouble();
       System.out.println("A média destes três números é "+decimal.format((calcularMedia(n1,n2,n3))));

    }
    public static  double calcularMedia( double n1, double n2, double n3 ) {
        double soma = ( n1 + n2 + n3 ) / 3;
        return soma;
```
# questao5
```java
        String palavra;
        Scanner ler = new Scanner(System.in);
        System.out.println("Digite uma palavra: ");
        palavra = ler.next();
        System.out.println("Palavra original: "+palavra);
        System.out.println("Palavra invertida: "+inverterTexto(palavra));
    }
    public static String inverterTexto( String texto ) { 
        String inverter = " ";
        for (int i = texto.length() - 1; i >= 0; i--) {
            inverter += texto.charAt(i);
    }
    return inverter;
```
# questao6
```java
        double valor;
        Scanner ler = new Scanner(System.in);
        System.out.println("Digite um valor em metros: ");
        valor= ler.nextDouble();
        System.out.println("De metros para Km é: " + conversorKM(valor)+"Km");
}
    public static double conversorKM( double conversor ) {
        double calculo = conversor / 1000;
        return calculo;
```
# questao7
```java
        double raio;
        Scanner ler = new Scanner(System.in);
        System.out.println("Digite um número: ");
        raio = ler.nextDouble();
        System.out.println("O volume da esfera é: "+(calcularVolume(raio)) + "cm³");

    }

    public static double calcularVolume(double x) {
        double calculo = (4.0 / 3.0) * Math.PI * (Math.pow(x, 3));
        return calculo;
```
