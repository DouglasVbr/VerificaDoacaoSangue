# VerificaDoacaoSangue


package verificadoacaosangue;

import java.util.Scanner;

public class VerificaDoacaoSangue {

    
    public static void main(String[] args) {
       
        Scanner Scanner = new Scanner(System.in);
        // solicita ao usuario que insira a idade e peso 
        
        System.out.println("Digite a idade:");
        int idade = Scanner.nextInt();
        System.out.println("Digite o peso(EM KG):");
        Double peso = Scanner.nextDouble();
        
        // VERIFICA SE A PESSOA ESTÁ ADPITA A DOAR SANGUE
        if(idade >= 18 && idade <=65 && peso >=50){
            System.out.println("voce está apta para doar sangue.");
        }else{
            System.out.println("voce não está apta para doar sangue.");
            
        }
        // fecha o Scanner 
        Scanner.close();
        
        
    }
    
}
