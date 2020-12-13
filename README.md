문제1.
package sujin;

import java.util.Scanner;

public class step1 {

	public static void main(String[] args) {
		//1.스캐너로 단어 입력받기
		Scanner scann=new Scanner(System.in);
		System.out.println("영어단어를 입력하세요.");
		//1.입력받은 내용 저장
		String choice = scann.next();
		
		//배열로 저장
		String[] choice2 =new String[choice.length()];
		
		//2. 스캐너로 숫자 입력받기
		Scanner scann1=new Scanner(System.in);
		
		System.out.println("정수를 입력하세요.");
		//2.입력받은 숫자 저장
		int number = scann1.nextInt();
		//배열로 저장 
		int[] numero = new int[number];
		for(int i=0; i<number; i++) {
			numero[i]=scann1.nextInt();
			System.out.print("numero["+i+"]:");
		}
		
		//3. 스캐너로 방향 입력받기
		Scanner scann2 = new Scanner(System.in);
				
		System.out.println("L또는R를 입력하세요.");
		//3.입력받은 내용 저장
		String direction = scann2.next();
		
		//만약에 방향에 l이면 
		if(direction =="L") {
			//입력받은 숫자만큼 왼쪽으로 이동- 포문으로 숫자길이 만큼 이동 출력 더하기 
			 
			
		}else {
			//입력받은 숫자만큼 오른쪽으로 이동
		}

	}

}
================================
문제2
package sujin;
class Cube{
	
	//2차원배열
	int[][]cube=new int[3][3]; //3x3
	
	//메서드 = 함수 
	int addU(int x,int y) {
		int result = x+y;
		return result;
		
	}
}
public class step2 {
	public static void main(String[] args) {
		//객체생성
		Cube cube1;
		cube1 = new Cube();
		
		//객체생성 후 접근
		cube1.addU(3, 3);
		
	}
}
