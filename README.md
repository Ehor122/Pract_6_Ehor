Практична 6

Виконав: Горбач Єгор

Опис

Тема: 


Код:

#include <stdio.h>

#include <math.h>

int main() {
  
    int x1, y1, x2, y2;
   
    printf("Enter the coordinates of the origin of the vector (x1 y1): ");
    
    scanf("%d %d", &x1, &y1);
    
    printf("Enter the coordinates of the end of the vector (x2 y2): ");
    
    scanf("%d %d", &x2, &y2);

    
    // Calculating the length of the vector
    
    double length = sqrt((x2 - x1) * (x2 - x1) + (y2 - y1) * (y2 - y1));

    
    // Print the result to six decimal places
    
    printf("Vector length: %.6f\n", length);

    return 0;
}
