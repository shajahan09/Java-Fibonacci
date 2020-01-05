# Java-Fibonacci
public class Fibonacci {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        // TODO code application logic here
        Scanner a = new Scanner(System.in);
        System.out.println("Enter Number");
        int n =a.nextInt();
        System.out.println("Fibonacci "+n+" is "+fib(n));
       
    }

    private static int fib(int n) {
        //throw new UnsupportedOperationException("Not supported yet."); //To change body of generated methods, choose Tools | Templates.
    if(n==0){
    return 0;
    } else if(n==1){
       return 1; 
    }else{
      return fib(n-1) +fib(n-2);
    }
        
    }
    
    
}


