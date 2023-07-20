import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        float num1 = 0, num2 = 0, mul= 0, rest = 0,sum=0;
        Scanner consola = new Scanner((System.in));
        System.out.println("Escriba el num1");
        num1 = consola.nextFloat();
        System.out.println("escriba el num2");
        num2 = consola.nextFloat();


        if (num1==num2)
        {
            mul = (num1 * num2);
            System.out.println("la multipli es " + mul);
        }
        if (num1>num2)
        {
            rest = (num1 - num2);
            System.out.println("la resta es" + rest);
        }
        if (num1<num2)
        {
            sum = (num1+num2);
            System.out.println("la suma es"+ sum);
        }
    }
}
