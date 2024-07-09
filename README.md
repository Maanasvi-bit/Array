#include <stdio.h>

int main() {
    int array[5] = {10, 20, 30, 40, 50};  // Example array of 5 integers
    
    // Print addresses of each element in the array
    printf("Addresses of elements in the array:\n");
    for (int i = 0; i < 5; ++i) {
        printf("Element %d: %p\n", i, (void *)&array[i]);
    }
    
    return 0;
}
