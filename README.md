# Program-to-Sort-the-array-of-elements
public class Arrays {
	public static void main(String[] args) {
		
		 int []arr2= {8,493,2,10,1,221,43,0};
		 int len2=arr2.length;
		 int x=0;
		 for(int i=0;i<len2;i++)
		 {
			 for(int j=i+1;j<len2;j++)
			 {
				 if(arr2[i]>arr2[j])
				 {
					 x=arr2[i];
					 arr2[i]=arr2[j];
					 arr2[j]=x;
				 }
			 }
		 }
		 System.out.print("Sorted array");
		 for (int i=0; i<len2; i++) 
		 {     
	            System.out.print(arr2[i] + " ");    
	     } 
		 


}
}
