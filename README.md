/*package com.company;

public class Main {
   public static void main(String args[]) {

       int year = 2029;
       if (year %400 ==0){

           System.out.println("this is a leap year");
       }
       else if (year %100 == 0){

           System.out.println("this is not a leap year");
       }
       else if (year %4 == 0){

           System.out.println("this is a leap year");
       }
       else {
           System.out.println("this is not a leap year");
       }
   }
}

package com.company;

public class Main {
   public static void main(String args[]) {

    double a = 3.87;     //this is called narrowing casting
    int b = (int)a;

       System.out.println(a);
       System.out.println(b);


   }
}

package com.company;
public class Main {
   public static void main(String args[]){

       int a = 5;
       System.out.println( a>4 && a<10); //when we have to check two conditions and generate true / false output


   }
   }
   }
   
   
   package com.company;
import java.util.Arrays;

public class Main{
    public static void main(String args[]){
        //java program to sort numeric array and String array
        int [] a1 = {
                123, 345, 567 ,567,
                3456, 346, 78, 357,
        };

        String [] a2 ={
                "java",
                "python",
                "c++",
                "PHP",

        };

        System.out.println("full array 1 : "+Arrays.toString(a1));
        Arrays.sort(a1);
        System.out.println("sorted : "+Arrays.toString(a1));
        System.out.println("full array 2: "+Arrays.toString(a2));
        Arrays.sort(a2);
        System.out.println("sorted 2: "+Arrays.toString(a2));

    }
}

package com.company;

public class Main{
    public static void main (String args[]){
        // java program for addition of elements of array 
        int [] a1 = {1,2,3,4,5,6,7,8,9,};
        int sum = 0;

        for (int i : a1)
        sum += i;
        System.out.println("sum" +sum);
    }
}



/*package com.company;
public class Main{
    public static void main(String args[]){

        //java program to calculate average using arrays

        int[] a1 = {1,2,3,4,5,6,7,8,9};
        int sum = 0;
        for (int i = 0; i < a1.length; i++)
            sum = sum + a1[i];
        double avg = sum / a1.length;
        System.out.println("avg value is :" +avg);

    }
}

java methods 

package com.company;
public class Main{
    public static int square(int num){
        return num*num;

    }

    public static void main(String args[]){
        int result;
        result = square(10);
        System.out.println("square root is: " +result);

    }
}

package com.company;
public class Main{
    public int addNumbers(int a, int b){
        int sum = a+b;
        return sum;
    }
    public static void main(String args[]){
        int num1 = 20;
        int num2 = 10;

        Main obj = new Main();

        int result = obj.addNumbers(num1,num2);
        System.out.println("Sum is: " +result);
    }
}*/


