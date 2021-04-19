# sum-and-multiplication-of-two-matrices
project 
package arrays;

public class Additionmultiplication {

	public static void main(String[] args) {
		int a[][]= {{1,3,4},{2,4,3},{3,4,5}};
		int b[][]= {{1,3,4},{2,4,3},{1,2,4}};
		int s[][]= new int[3][3];
		int m[][]= new int[3][3];
		int i=0,j=0;
		for(i=0;i<3;i++) {
			for(j=0;j<3;j++) {
				s[i][j]= a[i][j]+b[i][j];
				 m[i][j]= a[i][j]*b[i][j];
				System.out.println(" sum and multiplication of two matrices is " + s[i][j] + " and "+ m[i][j] );
				
				
				
				
			}
		}
		
	
		
		
		
		
	}

}
