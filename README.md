
package com.first;

import java.util.Scanner;

public class Factorial {

	public static void main(String[] args) {
  
			int fact=1,i,n;
			Scanner sc =new Scanner(System.in);
			System.out.println("enter no=");
			n=sc.nextInt();
			for(i=1;i<=n;i++) {
				fact=fact*i;
			}
			System.out.println(fact);
	}

}
