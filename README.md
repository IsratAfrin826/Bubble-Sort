# Bubble-Sort
Bubble sort is a simple sorting algorithm. This sorting algorithm is comparison-based algorithm in which each pair of adjacent elements is compared and the elements are swapped if they are not in order. This algorithm is not suitable for large data sets as its average and worst case complexity are of O(n2) where n is the number of items.

## Bubble Sort Algorithm
Step 1 − Check if the first element in the input array is greater than the next element in the array.

Step 2 − If it is greater, swap the two elements; otherwise move the pointer forward in the array.

Step 3 − Repeat Step 2 until we reach the end of the array.

Step 4 − Check if the elements are sorted; if not, repeat the same process (Step 1 to Step 3) from the last element of the array to the first.

Step 5 − The final output achieved is the sorted array.

## Algorithm: Sequential-Bubble-Sort (A)

fori ← 1 to length [A] do

for j ← length [A] down-to i +1 do

   if A[A] < A[j-1] then
   
      Exchange A[j] ⟷ A[j-1]

## Pseudocode

voidbubbleSort(int numbers[], intarray_size){

   inti, j, temp;
   
   for (i = (array_size - 1); i>= 0; i--)
   
   for (j = 1; j <= i; j++)
   
   if (numbers[j-1] > numbers[j]){
   
      temp = numbers[j-1];
      
      numbers[j-1] = numbers[j];
      
      numbers[j] = temp;
      
   }
   
}
