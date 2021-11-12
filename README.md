# demo

public class errorhandling {
    public static void main(String args[]){
        try{
            String a =null;
            System.out.println(a.charAt(0));
        }
        catch(NullPointerException a){
            System.out.println(a);
            System.out.println("null pointer exception");

        }
        try{
            int a[]=new int[5];
            a[6]=5;
        }
        catch(ArrayIndexOutOfBoundsException a){
                System.out.println(a);
                System.out.println("array iondex    ");

        }
        
        try{
        int a=1,b=0;
        int c=a/b;
        System.out.println("division:"+c);
        }
        catch(ArithmeticException a){
                System.out.println(a);
                System.out.println("division by zero is not possible    ");

        }
        
    }
    
}

