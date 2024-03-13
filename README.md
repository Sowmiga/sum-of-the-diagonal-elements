# sum-of-the-diagonal-elements
I have a done a program in SUM OF DIAGONAL ELEMENTS  using java programming language.

import java.util.*;
public class Main
{
	public static void main(String[] args) {
	    Scanner sc=new Scanner(System.in);
	    int row=sc.nextInt();
	    int col=sc.nextInt();
	    int sum=0;
	    int [][]a=new int[row][col];
	    for(int i=0;i<row;i++){
	        for(int j=0;j<col;j++){
	            a[i][j]=sc.nextInt();
	            if(i==j||i+j==row-1)
	            sum=sum+a[i][j];
	        }
	    }
	    System.out.println(sum);
	}
}
