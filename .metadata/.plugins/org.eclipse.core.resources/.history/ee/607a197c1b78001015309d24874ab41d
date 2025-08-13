package Ch07;

import java.util.Scanner;

public class C02While {

	public static void main(String[] args) {
		// 2단-9단 출력
		
//		int dan =2 ;
//		while(dan<10) {
//			int i =1;
//			while(i<10) {
//				System.out.printf("%d * %d = %d\n",dan,i,dan*i);
//				i++;
//			}
//			System.out.println();
//			dan++;
//		}
		
		//2단 9단 (2x9 , 2x 8 ,... ,9x9,9x8,...9x1)
//		int i =2;
//		while(i<10) {
//			int j =9;
//			while(j>0) {
//				System.out.printf("%d x %d = %d\n", i , j ,i*j);
//				j--;
//			}
//			System.out.println();
//			i++;
//		}
		
		//2단 9단 (9x9 , 9x 8 ,... ,2x9,2x8,...2x1)
//		int i =9;
//		while(i>1) {
//			int j =9;
//			while(j>0) {
//				System.out.printf("%d x %d = %d\n" , i , j , i*j);
//				j--;
//			}
//			System.out.println();
//			i--;
//		}
		
		//2단 n단 (n>2)
//		Scanner scanner = new Scanner(System.in);
//		System.out.printf("n입력하삼 (단,n>2) : ");
//		int n = scanner.nextInt();
//		if (n<=2) {
//			System.out.println("조건 벗어남");
//			System.exit(-1);
//		}
//		int i =2;
//		while(i<=n) {
//			int j =1;
//			while(j<10) {
//				System.out.printf("%d x %d = %d\n",i,j,i*j);
//				j++;
//			}
//			System.out.println();
//			i++;
//		}
//		
		
		//n단 m단 (n<m)
		Scanner scanner = new Scanner(System.in);
		System.out.print("n의 수 입력하삼 : ");
		int n = scanner.nextInt();
		System.out.print("m의 수 입력하삼 (단, n과 같은 숫자는 안됨) : ");
		int m = scanner.nextInt();
		
		if(n>m) {
			int temp = n;
			n =m;
			m = temp;
		}
		if(n==m) {
			System.out.println("조건에 안 맞음");
			System.out.println("시스템을 강제 종료합니다.");
			System.exit(-1);
		}
	
		while(n<=m) {
			int j =1;
			while(j<10) {
				System.out.printf("%d x %d = %d\n", n , j ,n*j);
				j++;
			}
			System.out.println();
			n++;
		}
		
		
		
		
		
		
		
		
	}

}
