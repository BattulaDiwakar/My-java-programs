import java.util.*;
public class Summinmax
{
    public static void main(String args[])
    {
        Scanner sc = new Scanner(System.in);
        int n = 10;
        int arr[] = new int[n];
        int sum=0;
        System.out.println("Enter "+n+" array elements");
        for(int i =0;i<n;i++)
        {
            arr[i] = sc.nextInt();
        }
        for(int i =0;i<n;i++)
        {
            sum = sum+arr[i];
        }
        int max = arr[0];
        for(int i =0;i<n;i++)
        {
            if(arr[i] > max)
            {
                max = arr[i];
            }
        }
        int min =arr[0];
        for(int i =0;i<n;i++)
        {
            if(arr[i] < min)
            {
                min = arr[i];
            }
            
        }
        double avg =sum/10.0;
        System.out.println("Array:");
        System.out.println("Sum: "+sum);
        System.out.println("min: "+min);
        System.out.println("max: "+max);
        System.out.printf("average: %.1f",avg);
    }
}
