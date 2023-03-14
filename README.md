# 13.02.2023-Assignment
### 1. Print the Square pattern
```
import java.util.Scanner;
public class Main {
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        System.out.print("Enter the Number : ");
        int a=sc.nextInt();
        for(int i =1;i<=a;i++)
        {
            for(int j=1;j<=a;j++)
            {
                System.out.print("* ");
            }
            System.out.print("\n");
        }
    }
}
```
### OUTPUT:
![image](https://user-images.githubusercontent.com/94228215/224887404-5d7b539a-cb31-414a-a85a-92628c045489.png)

### 2.print the bottom diamond pattern
```
import java.util.Scanner;
public class Main {
    public static void main(String[] args)
    {
        Scanner sc=new Scanner(System.in);
        System.out.print("Enter the Number : ");
        int a=sc.nextInt();
        for(int i=0;i<=a;i++)
        {
            for(int j=0;j<=i;j++)
            {
                System.out.print(" ");
            }
            for(int k=0;k<=a-1-i;k++)
            {
                System.out.print("*" + " ");
            }
            System.out.print("\n");
        }
    }
}
```
### OUTPUT:
![image](https://user-images.githubusercontent.com/94228215/224887722-25f1ee7e-3ff8-49a9-9103-e804547bc7db.png)

### 3.
```

```
### OUTPUT:
![image](https://user-images.githubusercontent.com/94228215/224888122-f5cd6439-1755-4bbf-a151-6b5d4c26897d.png)



