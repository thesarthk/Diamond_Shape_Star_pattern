# Diamond_Shape_Star_pattern
Diamond Shape Star pattern using Java
public class Star_Diamond {
    public static void main(String[] args) {
        for(int i=1;i<=5;i++){
//
            for (int k=5;k>i;k--){
                System.out.print("  ");
            }
            for(int j=1;j<=i;j++){
                if(j==1){ System.out.print("*"+"  ");}
                else {
                    System.out.print("  ");
                }
            }

            for(int j=i-1;j>=1;j--){
                if(j==1) {System.out.print("*"+" ");}
                else {
                    System.out.print("  ");
                }

            }

            System.out.println("");

        }

        for(int i=1;i<=4;i++){
//
            for (int k=1;k<=i;k++){
                System.out.print("  ");
            }
            for(int j=1;j<=(4-(i-1));j++){
                if(j==1){ System.out.print("*"+"  ");}
                else {
                    System.out.print("  ");
                }

            }

            for(int j=(4-i);j>=1;j--){
                if(j==1) {System.out.print("*"+" ");}
                else {
                    System.out.print("  ");
                }

            }

            System.out.println("");

        }
    }
}
