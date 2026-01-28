import java.util.*;
class Main{
    public static void main(String[] args){
        Scanner sc = new Scanner(System.in);
        int a = sc.nextInt();
        int b = sc.nextInt();
        int sum = a + b;
        System.out.println("Enter operation +,-,*,/");
        char ch = sc.next().charAt(0);
        switch (ch){
        case'+':
            System.out.println(a + b);
            break;
        case'-':
            System.out.println(a - b);
            break;
        case'*':
            System.out.println(a * b);
            break;
        case'/':
            System.out.println(a / b);
            break;
            default:
            System.out.println("Enter the valid operator and numbers");
        }
    }
}
