# Applet
Display name and colors in applet

importjava.awt.*;
public classjournal9extendsApplet{
publicvoidpaint(Graphicsg){
setForeground(Color.red);
g.fillRect(10,10,400,400);
g.setFont(newFont("TimesNewRoman",Font.BOLD,12));g.setColor(Color.yellow);
g.drawString("UCCC&SPBCBA&SDHG\nCOLLEGEOFBCAANDIT.",55,200);
}
}
/*
*<appletcode="journal9"width=800height=800></applet>
*/
