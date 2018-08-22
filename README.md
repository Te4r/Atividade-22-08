# Atividade-22-08
package banco;
import javax.swing.JOptionPane;
public class wsdqw {
    public static void main(String[] args) {
      String nome = JOptionPane.showInputDialog(null, "Digite seu nome: ");
      String txt = JOptionPane.showInputDialog(null, "Digite sua idade: ");
      int idade = Integer.parseInt(txt);
      
      if (idade >= 18){
          JOptionPane.showMessageDialog(null,nome+" você já pode tirar a CNH!!");
      }else{
          JOptionPane.showMessageDialog(null,nome+" você não pode tirar a CNH, você tem apenas " + idade + " anos.");
      }
    }
    
}
