# Applet
Display name and colors in applet

import java.awt.*;

public class journal9 extends Applet
{

public void paint(Graphics g)
{
  setForeground(Color.red);
  
  g.fillRect(10,10,400,400);
  
  g.setFont(newFont("TimesNewRoman",Font.BOLD,12));
  
  g.setColor(Color.yellow);
  
  g.drawString("UCCC & SPBCBA & SDHG \n COLLEGE OF BCA AND IT.",55,200);

}

}

/*
* <applet code="journal9" width=800 height=800> </applet>
*/
