# Mobile Security Game Survive

## which  changes i made:
iArr[i] = Integer.valueOf(String.valueOf(id.charAt(i))).intValue() % 4; to: iArr[i] = Integer.parseInt(String.valueOf(id.charAt(i))) % 4;

Toast.makeText(this, "Survived in " + state, 1).show(); to: Toast.makeText(this, "Survived in " + state, Toast.LENGTH_SHORT).show();

Toast.makeText(this, "You Failed ", 1).show(); to: Toast.makeText(this, "You Failed ",  Toast.LENGTH_SHORT).show();

The first thing I did was check what button I needed to click, so I entered 000000000, 111111111, 222222222, 333333333 once.

i saw that 0 is left, 1 is right, 2 is up and 3 is down.

In addition, I checked strings.xml and ran the url and saw that it contains names of countries.

my ID is 318415700 -> 310011300 -> california

## link to video

[https://youtube.com/shorts/Y8egYi_G0gM?si=RRcT5fgsvtpppKYS](https://www.youtube.com/watch?v=opEIYAxd0xw)
