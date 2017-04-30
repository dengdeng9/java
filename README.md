# java
exercise in java

This is the area to keep the exercise in book.


class Main {
	public static void main(String[] args) {
		java.util.Scanner input = new java.util.Scanner(System.in);
		
		String s = input.next();
		
		while (s.indexOf('.') == -1) {//字符串s中没有.这个字符
			System.out.print(s.length() + " ");
			s = input.next();
		}
		
		System.out.print(s.substring(0, s.indexOf('.')).length());
	}
}
