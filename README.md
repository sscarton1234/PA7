//PA7
import javax.swing.JFrame;

public class PacManViewer {

   public static void main(String[] args) {
   
      JFrame pacFrame = new JFrame();
      PacMan pacman = new PacMan();
      
      pacFrame.setSize(1000, 1000);
      pacFrame.setTitle("Pacman!");

      pacFrame.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);    //End program when JFrame is closed
      
      pacFrame.add(pacman);
      
      pacFrame.setVisible(true);
      
      return;
   }

}
