import java.util.Scanner;
public class Arraymean
{
    public static double array_mean_cal(int n,int arr[])
    {
        double v=0;
        for(int i=0;i<n;i++)
        {
            v = v+arr[i];
        }
        double tot = v/n;
        return tot;
    }
    public static void main(String[] args)
    {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        int arr[] = new int[n];
        for(int i=0;i<n;i++)
            arr[i] = sc.nextInt();
        System.out.printf("%.1f",array_mean_cal(n,arr));
    }
}
