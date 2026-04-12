#include<stdio.h>
int main() {
printf("25331A05E9\n");
    int rows, cols, i, j;
    int matrix[100][100]; 

    
    printf("Enter number of rows and columns: ");
    scanf("%d %d", &rows, &cols);

        printf("Enter elements for a %dx%d matrix:\n", rows, cols);
    for (i = 0; i < rows; i++) {
        for (j = 0; j < cols; j++) {
            printf("Element [%d][%d]: ", i, j);
            scanf("%d", &matrix[i][j]);
        }
    }

    
    printf("\nThe Matrix is:\n");
    for (i = 0; i < rows; i++) {
         for (j = 0; j < cols; j++) {
            
            printf("%d\t", matrix[i][j]);
        }
               printf("\n");
    }

    return 0;
}
