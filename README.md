# EXPERIMENT 09: WRITE A PROGRAM TO ADD,RETRIEVE AND REMOVE THE ELEMENT FROM THE ARRAYLIST

## AIM:
To write a program to add,retrieve and remove the element from the arraylist.

## PROCEDURE:
1. Create an arraylist.
2. Add elements using add() method.
3. Add an arraylist to the existing arraylist using addAll() method.
4. Display the added arraylist.
5. Remove the elements using remove() method.
6. Retrieve the required element using get(index) method.
7. End the program.

## PROGRAM:
```
import java.util.*;
class Arraylistdemo
{
    public static void main(String[] args)
    {
        ArrayList<String> arr = new ArrayList<String>();
        System.out.println("Size of ArrayList: "+arr.size());

        arr.add("A");
        arr.add("B");
        System.out.println("Elements of first ArrayList: "+arr);
        ArrayList<String> arr2 = new ArrayList<String>();
        arr2.add("C");
        arr2.add("D");

        arr2.addAll(arr);
        System.out.println("Elements of second ArrayList: "+arr2);

        arr2.remove("C");
        System.out.println("Elements of ArrayList after deletion: "+arr2);
        System.out.println("Size of ArrayList: "+arr2.size());

        System.out.println("The element at 2nd index is: "+arr2.get(2));
    }
}
```

## OUTPUT:
![image](https://github.com/Rithigasri/Experiment09-Java/assets/93427256/7355bbb5-63ed-4ccc-904b-47e708eef3d3)

## RESULT:
Hence, a program to add,retrieve and remove element from arraylist is executed successfully.
