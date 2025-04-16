#include <stdio.h>
int main() {
    float side1, side2, side3;
    printf("Enter the three sides of the triangle: ");
    scanf("%f %f %f", &side1, &side2, &side3);
    if (side1 <= 0 || side2 <= 0 || side3 <= 0) {
        printf("Not a valid triangle. Sides must be positive.\n");
    } 
    else if (side1 + side2 > side3 && side1 + side3 > side2 && side2 + side3 > side1) {
        if (side1 == side2 && side2 == side3) {
            printf("Equilateral Triangle\n");
        } 
        else if (side1 == side2 || side1 == side3 || side2 == side3) {
            printf("Isosceles Triangle\n");
        } 
        else {
            printf("Scalene Triangle\n");
        }
    } 
    else {
      
        printf("Not a valid triangle\n");
    }

    return 0;
}
