# Java Programs 

####  1. Factorial  

## Logic 

    public static void main(String[] args) {
      int n=4;
      int fac =factorial(n);
      System.out.println(fac);

    }

    public static int factorial(int n) {
      int k=1;
      for (int i=1;i<=n;i++) {
        k=i*k;			
      }

      return k;

    }
 

