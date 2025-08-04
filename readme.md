# Esse codigo so pode ser usado no mac e linux 

## hello.c
//#include <cs50.h>

//#include <stdio.h>

int main(void)

{

   //string answer = get_string("What's your name? ");

   //printf("hello, %s\n" ,answer);
   
   printf("hello, world\n");

}

# Usando esse comando no terminal
-code hello.c

-make hello

-./hello

-check50 cs50/problems/hello

-ls- para ver a lista de arquivos e pastas na pasta atual

-rm hello- y(sim) ou n(nao) - solicitara um confirmacao e podemos responder

-mv hello.c goodbye.c- renomeamos o nosso arquivo ola.c com o nome goodbye.c

-mkdir lecture

-mv hello.c lecture/- para colocar o arquivo dentro dessa pasta

-cd lecture/- para mudar os diretórios em nosso terminal

-rmdir lecture/- serve para remover a pasta 

## additional.c
#include <cs50.h>

#include <stdio.h>

int main(void)

{

    int x = get_int("x: ");
    int y = get_int("y: ");
    printf("%i\n", x + y);

    long x = get_long("x: ");
    long y = get_long("y: ");
    printf("%li\n", x + y);

}

## truncation.c
#include <cs50.h>

#include <stdio.h>

int main(void)

{

    //get numbers from user
    int x = get_int("x: ");
    int y = get_int("y: ");
    //divide x by y
    //float z = (float) x / (float) y;
    float z = x / y;
    //printf("%f\n", z);
    printf("%i\n", x + y);
    
}

## conditions.c
#include <cs50.h>

#include <stdio.h>

int main(void)

{

    //prompt user for x
    int x = get_int("x: ");

    //prompt user for y
    int y = get_int("y: ");

    //compare x and y
    if (x < y)
    {
        printf("x is less than y\n");
    }
    else if (x > y)
    {
        printf("x is greater than y\n");
    }
    else
    {
        printf("x is equal to y\n");
    }
    
}
