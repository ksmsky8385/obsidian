
##### ※ 옵시디언에서는 입력함수 실행이 안되므로 실행시킬 수 없음. 코드를 눈으로만 확인하기.

##### ※ 러너코드의 작동을 위해 Scanner 사용 코드들의 scanner.close();는 전부 주석처리됨.



# **Java_mini_project_01_흐름제어**



### 1번 문제
![[스크린샷 2025-05-09 124441.png]]
```java //
package mini_project_01_흐름제어;

import java.util.Scanner;

public class No1 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		System.out.println("1번 : 입력한 정숫값을 표시\n");
		
		Scanner scanner = new Scanner(System.in);
		
		System.out.println("정수값:");
		int inputData = scanner.nextInt();
		
		System.out.println( inputData + "을(를) 입력했습니다.");
		
//        scanner.close();
		
	}

}
```

### 2번 문제
![[스크린샷 2025-05-09 125259.png]]
```java
package mini_project_01_흐름제어;

import java.util.Scanner;

public class No2 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		System.out.println("\n2번 : 입력한 정숫값의 +&- 100 값 출력\n");
		
		Scanner scanner = new Scanner(System.in);
		
		System.out.println("정수값:");
		int inputData = scanner.nextInt();
		
		System.out.println("100을 더한 값은 " + ( inputData+100) + "입니다.");
		System.out.println("100을 뺀 값은 " + ( inputData-100) + "입니다.");

//        scanner.close();
		
	}

}

```

### 3번 문제

![[스크린샷 2025-05-09 125709.png]]
```java
package mini_project_01_흐름제어;

import java.util.Scanner;

public class No3 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		System.out.println("\n3번 : 입력한 정숫값의 마지막자리 제외값 & 마직막자리값\n");
		
		Scanner scanner = new Scanner(System.in);
		System.out.println("정수값:");
		int a = scanner.nextInt();

	    int i = a / 10; // 마지막 자리 제외한 값
	    int j = a % 10; // 마지막 자리 숫자

	    System.out.println("마지막 자릿수를 제외한 값은 " + i + "입니다.");
	    System.out.println("마지막 자릿수는 " + j + "입니다.");

//		scanner.close();
		
	}

}

```



# Java_mini_project_02_조건문

### 1번 문제




### 2번 문제




# Java_mini_project_03_반복문

















