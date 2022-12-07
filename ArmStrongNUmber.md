package com;

import java.util.Scanner;

public class Demo {
	
	public static void main(String[]args)
	{
		int no=371;
		
		int temp=no;
		int rem;
		int res=0;
		
		while(temp!=0)
		{
			rem=temp%10;
			res=(int) Math.pow(rem, 3)+res;
			temp=temp/10;
		}
		if(res==no)
		{
			System.out.println("No is Armstrong");
		}
		else
		{
			System.out.println("NO is not");
		}
	}
}
