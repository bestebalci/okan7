package okan7;
import java.util.Scanner;
public class okan71 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		int count = 1;
		int dogrusayisi = 0;
		int kulsonuc, asilsonuc;
		int n1, n2;
		final int MAXSORUSAYISI = 5;
		Scanner input = new Scanner (System.in);
		while (count <= MAXSORUSAYISI ) {
			
		
		n1 = (int) (Math.random() *11 );
		n2 = (int) (Math.random() *11 );
		if (n1>n2)
			asilsonuc = n1-n2;
		else
			asilsonuc = n2-n1;
		System.out.println(count + "-cıkarma isleminin sonucunu girin" +n1 + " " + n2 );
		kulsonuc = input.nextInt();
		if(kulsonuc == asilsonuc){
			dogrusayisi++;
		}
		count++;
		System.out.println("dogru sayınız" + dogrusayisi);
		
		
		

	}
	

}
	
