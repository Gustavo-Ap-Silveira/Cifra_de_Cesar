#include <stdio.h>
int main() {
char letra;
int shift = 25;
     
    
    printf("Digite uma letra:");
    scanf("%c", &letra);
    
    letra = 'a' + (letra - 'a' + shift) %26;
    
    printf("Letra criptografada: %c\n", letra);
    
    return 0;
    
}
