# Estrutura-While
A instrução WHILE é utilizada para repetir um bloco de instrução por um período determinado ou então, enquanto uma condição para a verdadeira.

blog
cursos
quem somos
DOE
contato
Archives
ESTRUTURA WHILE DO JAVA
CURSO DE JAVA
Publicado em 25-02-2014 por Cláudio Rogério Carvalho Filho
ÍNDICE
ARTIGO
VIDEOAULA
Nesta aula vamos estudar os laços de repetição, porém, fazendo um exemplo onde as instruções estão em Portugues, ao invés de utilizar as instruções da linguagem Java.

A instrução WHILE é utilizada para repetir um bloco de instrução por um período determinado ou então, enquanto uma condição for verdadeira. O cabeçalho dessa instrução é mais simples, logo, faz da mesma muito mais flexível e isso nos proporciona um leque muito maior de utilizá-la.

Você pode pensar na instruão WHILE da mesma forma em que você pensa na instrução IF. Até porque, ambas estruturas só iram executar o bloco de instrução, caso a condição no cabeçalho seja verdadeiro. Então, a diferença, é que com a instrução IF o nosso programa verificara a condição, decidira se deve executar o bloco da instrução para caso a condição seja verdadeiro e então, segue o fluxo natural do programa. Com a instrução WHILE o funcionamento é semelhante, porém, nós ficaremos repetindo o bloco até que a condição determinada no cabeçalho seja verdadeira. Logo, será nosso dever prever uma situação dentro do bloco de instrução para fazer o nosso programa sair dessa estrutura.

EXEMPLO FEITO EM AULA
public class Aula0021 {

    public static void main(String[] args) {
        //Estrutura While

//        enquanto(<=9){
//            //incremento da variável que está servindo a nossa condição
//            inteira = inteira + 1;
//            imprima("essa msg");
//        }

        //INCREMENTADO - de 0 à 9
        int i = 0;
        while(i<=9){
            i = i + 1;
            System.out.println( i );
        }/*
         * 1
         * 2
         * 3
         * 4
         * 5
         * 6
         * 7
         * 8
         * 9
         * 10
         */

        //DE-CREMENTADO - de 9 à 0
        int x = 0;
        while(x>=0){
            x = x - 1;
            System.out.println( x );
        }
        /*
        * 10
        * 9
        * 8
        * 7
        * 6
        * 5
        * 4
        * 3
        * 2
        * 1
        * 0
        * */

    }

}
