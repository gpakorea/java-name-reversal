/*
 * Project: NameReversal.java
 * Description: An investigation into "for" loops.
 * Name: Aaron Snowberger
 * Date: Sept 14, 2015
 */

// public class - the class name MUST match the file name
// class - it can be any name

public class NameReversal {
  
  public static void main( String[] args ) {
    
    // #1
    int j=0, g=0;
    for ( g = 0; g < 5; g++ ) {
      j++; // g=0, j=1 / g=1, j=2 / g=2, j=3 / g=3, j=4 / g=4, j=5 / g=5
      System.out.println( "g = " + g ); // Scope - we only see g IN the loop
    }
    System.out.println( "j = " + j ); // Start = 0, prints = 
    System.out.println( "g = " + g ); // Scope - I dunno g, because it's not declared OUT of the loop
    
    // #2
    int s = 1;
    for ( int i = 3; i >= 0; i-- ) {
      s = s + i; // 1+3 / 4+2 / 6+1
    }
    System.out.println( "s = " + s );
    
    // #3
    int p = 6;
    int m = 20, k;
    for ( k = 1; k < p; k++ ) {
      m = m + k * k; // 20+1 / 21+4 / 25+9 / 34+16 / 50+25 / 75...
    }
    System.out.println( "m = " + m ); 
    
    // #4
    double a = 1.0;
    for ( int i = 0; i < 9; i++ ) {
      a*=3;
    }
    System.out.println( "a = " + a );
    
    // #6
    double d = 100.01;
    int q = 0;
    for ( int yellow = 0; yellow < 50; yellow+=5 ) {
      q = 19 + yellow;
      d++;
    }
    System.out.println( "d = " + d );
    System.out.println( "q = " + q );
    
    // #7
    // Write a for-loop that prints 3(*1), 6(*2), 12(*4), 24(*8)
    int num;
    for ( int i = 1; i < 9; i*=2 ) {
      num = 3 * i;
      System.out.println( "num = " + num );
    }
    
    // #8
    // Write a for-loop that prints 24, 12, 6, 3
    int num2;
    for ( int i = 8; i > 0; i/=2 ) {
      num2 = 3 * i;
      System.out.println( "num2 = " + num2 );
    }
    
  } // end main method
  
} // end class