#include <stdio.h>

int main() { 

// Carta 1
char letra = 'A';
char codigo [5] = "A01";
char nome_cidade [8] = "Alagoas";
int população = 3220104;
float area = 27.768;
float pib = 7.07;  // em bilhões
int ponto_turistico = 25;



// Carta 2
    char estado2 = 'B';
    char codigo2 [5] = "B02";
    char nome_cidade2 [8] = "Bahia";
    long int populacao2 = 14850513;
    float area2 = 567.295;
    float pib2 = 138.5; // em bilhões
    int pontos_turisticos2 = 25;



 // Impressão da Carta 1
printf("Carta 1:\n\n");

printf("Estado: %c\n",letra);
printf("Código: %s\n",codigo);
printf("Nome da Cidade: %s\n",nome_cidade);
printf("População: %d\n",população);
printf("Área: %fkm²\n",area);
printf("PIB: %f bilhoes reais\n",pib);
printf("Número de Pontos Turisticos: %d\n\n\n",ponto_turistico);


 // Impressão da Carta 2
printf("Carta 2:\n\n");
    
    printf("Estado: %c\n", estado2);
    printf("Código: %s\n", codigo2);
    printf("Nome da Cidade: %s\n", nome_cidade2);
    printf("População: %ld\n", populacao2);
    printf("Área: %f km²\n", area2);
    printf("PIB: %f bilhões de reais\n", pib2);
    printf("Número de Pontos Turísticos: %d\n\n", pontos_turisticos2);

    return 0;




}
