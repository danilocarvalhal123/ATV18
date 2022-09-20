# ATV18
#include <stdio.h>
//Faça um programa que peça o tamanho de um arquivo para download (em MB) e a velocidade de um link de Internet (em Mbps), calcule e informe o tempo aproximado de download do arquivo usando este link (em minutos).
int main(void) {
  float mb, mbps, tempo;
  printf("\nInforme do tamanho do arquivo em MegaByte:\t");
  scanf("%f", &mb);
  printf("\nInformar a velocidade do link em Mbps\t");
  scanf("%f", &mbps);
  tempo = (( mb  *  8 ) /  mbps ) /  60;
  printf("\nO temo estimado para download do arquivo é de: %.1f minutos ", tempo);
    
  return 0;
}
