#include <stdio.h>

int main() 
{
    
    int weights[5];  // Array to store the weights of the 5 treasures
    int totalWeight = 0;  // Variable to store the total weight
    int i;

    // Input weights of each treasure
    printf("Enter the weights of the five treasures:\n");
    for (i = 0; i < 5; i++) {
        printf("Treasure %d weight: ", i + 1);
        scanf("%d", &weights[i]);
    }

    // Calculate the total weight by summing up each treasure's weight
    for (i = 0; i < 5; i++) {
        totalWeight += weights[i];
    }

    // Output the total weight
    printf("Total weight collected from treasures: %d\n", totalWeight);

    return 0;
}


Explanation:
1.Define an Array for Weights: We declare an array weights[5] to store the weights of the five treasures.
2.Input Weights: We use a loop to take input from the user for each treasure's weight.
3.Calculate Total Weight: Using another loop, we add up each element in the weights array and store the result in totalWeight.
4.Output the Result: Finally, we display the total weight collected.
