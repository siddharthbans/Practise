import java.util.Scanner;

public class Reurs {
    public static void Printnumber(int n){
        if (n==0){
            return;
        }
        System.out.println(n);
        Printnumber(n-1);
    }



    public static void main(String args[]) {

        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        Printnumber(n);


    }}
