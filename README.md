# Swing2020
##  201任务戳→:  [Excel OL](https://docs.qq.com/sheet/DYVVCenN5QmF0dnVn)
##  202任务戳→:  [Excel OL](https://docs.qq.com/sheet/DYXB3cE9XVXVHQVN4)


```
import javax.swing.*;
import java.awt.event.KeyAdapter;
import java.awt.event.KeyEvent;

public class App {
   JPanel myPanel=new JPanel();
   JLabel label_txt=new JLabel();
   //构造方法
   public App() {

   }
   //显示窗体方法
   void go(){
       JFrame frame = new JFrame("TestGUI");
       myPanel.setLayout(null);
       myPanel.add(label_txt);
       frame.setContentPane(myPanel);
       frame.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
       frame.setBounds(100,100,512,720);
       //frame.pack();
       frame.setVisible(true);
   }
   public static void main(String[] args) {
       new App().go();
   }
}
```
