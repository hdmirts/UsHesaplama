```java
import java.util.Scanner;

public class uslu {
    public static void main(String[] args) {
        Scanner inp = new Scanner(System.in);
        int m, n;
        System.out.print("Taban sayıyı giriniz :");
        m = inp.nextInt();

        System.out.print("Üs sayıyı giriniz :");
        n = inp.nextInt();

        int t =1;

        for(int i=1; i<=n; i++){
            t = t*m; 
        }
        System.out.print(m + "^" + n + "=" + t);

        /*
        -->aynı işlemi for yerine while yaparsak ;
        
        int t =1;
        while (i<=n){
            t*=m;
            i++;
        }
        */
    }
    
}
```

