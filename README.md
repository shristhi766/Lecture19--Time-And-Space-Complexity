# Lecture19--Time-And-Space-Complexity
package coreJava;
        public class TimeComplexity{
        satic boolean isPrimeRam(int n)
       {
          if(n<=1) return false;
         if(n<=2) return true;
           for (int i = 2; i < Math.sqrt(n),i+1)
          if (n % i == 0) return false;
         }
           return true;
}
public void main(String[] args)
int n= 100;
int start = System.currentTime Millis();
System.out.println(isPrimeRam(n));
long end = System.out.println(isPrimeSham(n));
System.out.println(end - start);
System.out.println(isPrimeSham(n));
