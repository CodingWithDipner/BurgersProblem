# BurgersProblem

# CODE 
    /* package codechef; // don't place package name! */
    
    import java.util.*;
    import java.lang.*;
    import java.io.*;
    
    /* Name of the class has to be "Main" only if the class is public. */
    class Codechef
    {
    	public static void main (String[] args) throws java.lang.Exception
    	{
    		// your code goes here
    		Scanner sc=new Scanner(System.in);
    		
    		int T=sc.nextInt();
    		for(int i=1;i<=T;i++){
    		    int x=sc.nextInt();
    		    int y=sc.nextInt();
    		    
    		    if(x==y){
    		        System.out.println(x);
    		    }
    		    else if(x>y){
    		        System.out.println(x);
    		    }
    		    else{
    		        System.out.println(y);
    		    }
    		    
    		}
    	}
    }


