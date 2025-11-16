# Ex12 Add Elements from an Array into a TreeSet
## DATE:16-11-2025
## AIM:
To write a Java program that adds elements from an array into a TreeSet and displays the elements in sorted order.
## Algorithm
1. Start the program.
2. Initialize an array with integer elements.
3. Create an empty TreeSet.
4. Add all elements from the array into the TreeSet.
5. Display the elements of the TreeSet (which are automatically sorted).
6. Stop the program.
   

## Program:
```
/*
Program that adds elements from an array into a TreeSet and displays the elements in sorted order.
Developed by: TIMMAPURAM YOGEESWAR
RegisterNumber: 212223230233
*/
import java.util.*;

public class Main {
    public static void main(String[] args) {

        Integer[] arr = {50, 20, 40, 10, 30};

        System.out.println("Array elements: " + Arrays.toString(arr));

        TreeSet<Integer> set = new TreeSet<>(Arrays.asList(arr));

        System.out.println("\nTreeSet elements (sorted): " + set);
    }
}

 
*/
```

## Output:

<img width="528" height="140" alt="image" src="https://github.com/user-attachments/assets/68bd2bf9-9af7-45cd-935a-0602f8dd18e5" />


## Result:
The program successfully adds elements from an array into a TreeSet.
