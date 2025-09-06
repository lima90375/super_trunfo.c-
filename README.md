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

// Caculo de Desidade populacional : Carta 1
float desidade  = população / area;

// Caculo de Pib per caiptal: Carta 1
float per = pib / população;

// Caculo Super poder : Carta 1 
float carta_poder = população + area + pib + ponto_turistico;




// Carta 2
    char estado2 = 'B';
    char codigo2 [5] = "B02";
    char nome_cidade2 [8] = "Bahia";
    int populacao2 = 14850513;
    float area2 = 567.295;
    float pib2 = 138.5; // em bilhões
    int pontos_turisticos2 = 25;



// Caculo da Desidade Polucinal : Carta 2
    float desidade2 = populacao2 / area2;

// Caculo Pib per Capital: Carta 2
float per2 = pib2 / populacao2;

// Calculo Super Poder : Carta 2
float carta_poder2 = populacao2 + area2 + pib2 + pontos_turisticos2;


// Varialvel de comparação
int resultadoA, resultadoB, resultadoC, resultadoD, resultadoE, resultadoF, resultadoG;

// Comparação das Cartas
 resultadoA = população > populacao2;
 resultadoB = area > area2;
 resultadoC = pib > pib2;
 resultadoD = ponto_turistico > pontos_turisticos2;
 resultadoE =  desidade > desidade2;
 resultadoF = per > per2;
 resultadoG = carta_poder > carta_poder2;



 // Impressão da Carta 1
printf("Carta 1:\n\n");

printf("Estado: %c\n",letra);
printf("Código: %s\n",codigo);
printf("Nome da Cidade: %s\n",nome_cidade);
printf("População: %d\n",população);
printf("Área: %f km²\n",area);
printf("PIB: %f bilhoes reais\n",pib);
printf("Número de Pontos Turisticos: %d\n",ponto_turistico);
printf("Densidade Populacional: %f hab/km²\n", desidade);
printf("PIB per Capita: %f  reais\n",per);
printf("Super Poder: %f \n\n\n", carta_poder);




 // Impressão da Carta 2
printf("Carta 2:\n\n");
    
    printf("Estado: %c\n", estado2);
    printf("Código: %s\n", codigo2);
    printf("Nome da Cidade: %s\n", nome_cidade2);
    printf("População: %d\n", populacao2);
    printf("Área: %f km²\n", area2);
    printf("PIB: %f bilhões de reais\n", pib2);
    printf("Número de Pontos Turísticos: %d\n", pontos_turisticos2);
    printf("Densidade Populacional: %f hb/km²\n", desidade2);
    printf("PIB per Capita: %f reais\n",per2);
    printf("Super Poder: %f \n\n\n", carta_poder2);

// Impressão Comparação
 printf("Comparação das Cartas: \n\n");

 printf("População:Carta 2 venceu %d\n", resultadoA);
 printf("Area:Carta 2 venceu %d\n", resultadoB);
 printf("PIB:Carta 2 venceu %d\n", resultadoC);
 printf("Pontos Turisticos:Carta 2 venceu %d\n", resultadoD);
 printf("Desindade Populacional:Carta 1 venceu %d\n", resultadoE);
 printf("PIB per Capita:Carta 2 venceu %d\n", resultadoF); 
 printf("Super Poder:Carta 2 venceu %d\n", resultadoG);


    return 0;




}
