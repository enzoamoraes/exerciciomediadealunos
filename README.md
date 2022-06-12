# exerciciomediadealunos

package mediabranch1;

import java.util.Scanner;
@SuppressWarnings("unused")
public class mediabranch {
    public static void main( String[] args){
        int soma = 0;
        int Q[]={35,4,22,20,36,30};
        int n = Q.length;
        
        for(int C=0; C<n; C++){
            soma = soma + Q[C];
        }
        int media = soma/n;
        System.out.println("A média é " + media + ", e as salas que passaram é: 1(com 35), 5(com 36) e a 6(com 30)."); 

        }
}


![image](https://user-images.githubusercontent.com/103973508/173249363-1e9e36d8-127f-4c89-a606-a2a9f185bb0f.png)
