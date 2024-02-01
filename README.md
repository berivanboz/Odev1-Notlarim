# Odev1-Notlarim
GitHub Görevi - 1

  /*
  #1 Enter the value in degree
  #2 Set result = Degree value*PI/180
  #3 print the sine function
  #4 NB: conversion from degree to radians Dg*PI/180
  */


#include <stdio.h>
#include <math.h>
#define PI 3.14

int main (void) {
	
	double result, Dg;
	printf("Enter the degree value:	");
	scanf("%lf", &Dg);
	result = sin(Dg*PI/180);
	printf("Sine function of %5.2lf degree is %5.2lf\n", Dg, result);
	return 0;
}

