public class Main {                                                                                                                                                             
      public static void main(String[] args) {                                                                                                                               
        int sum = 0;                                                                                                                                                            
        for (int i = 1; i <= 100; i++) {                                                                                                                                        
            System.out.print(i + "\t");                                                                                                                                      
            if (i % 2 == 0) {                                                                                                                         
                System.out.println("even");                                                                                                                                     
                } else {                                                                                                                                               
                System.out.println("odd");                                                                                                                                      
           }                                                                                                                                                                 
            sum += i;                                                                                                                                                           
         }
        System.out.println("The sum of all numbers from 1 to 100 is " + sum + ".");
    }
}



<img width="639" alt="Screenshot 2024-02-01 195642" src="https://github.com/Billiegoat2008/Billiegoat2008/assets/156938498/37466c02-05b7-4fca-b873-d578a7b4d0fe">

The sum of all numbers from 1 to 100 is 5050.
