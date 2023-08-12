# SolidRhombus
here is a code of SolidRhombus in java.


public class SolidRhombus {
    public static void SolidRhombus(int n){
        for(int i=1;i<=n;i++){
            for(int j=1;j<=n-i;j++){
                System.out.print(" ");
            
        }
        for(int j=1;j<=i;j++){
             System.out.print("*");

        }
        System.out.println();
        }
    }
public static void main(String[] args) {
    SolidRhombus(5);
}
}

