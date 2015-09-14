##PAGE DIMENSION CALCULATIONS
###Page sizes for various Beamer aspect ratios
Beamer:  
Ratio    Option   Width(cm)   Height(cm)  
16:10    1610     16.00       10.00  
16:9     169      16.00        9.00  
14:9     149      14.00        9.00  
5:4      54       12.50       10.00  
4:3      43       12.80        9.60  
3:2      32       13.50        9.00  

###PPT:
Ratio    Option   Width(cm)   Height(cm)  
16:9     -        25.4        14.3  

---

###Math time  
**Ratio Check:**  
25.4/14.3 = 1.77622377622377622377  
16/9      = 1.77777777777777777777  
PPT only 16:9 to 3 significant figures.  
3 Sig. Fig. used for rest of template.  
  
**Logo dimensions in PPT (16:9):**  
1.40cm x 4.75cm   
4.75/25.4 = 0.187 * paper width wide  
Aspect ratio in PPT 1.40/4.75 = 0.295  
  
**Logo dimensions in Beamer (16:9):**  
Logo width = 4.75/25.4*16.0 = 2.99cm  
Logo height = 1.40/14.3*9.0 = 0.881cm  
Aspect ratio in beamer = 0.881/2.99 = 0.295 = PPT. YAY MATHS!  
  
**Large Rectangle dimensions in PPT (16:9):**  
2.00cm x 5.50cm  
Aspect ratio in PPT = 2.00/5.50 = 0.364  
Relative width to logo = 5.50/4.75 = 1.16 larger (or logo is 0.864 smaller)  
Relative height to logo = 2.00/1.40 = 1.43 larger (or logo is 0.700 smaller)  
  
**Large Rectangle dimensions in Beamer (16:9):**  
Rectangle width = 5.50/25.4*16.0 = 3.46cm  
Rectangle height= 2.00/14.3*9.0 = 1.26 cm  
Aspect ratio in Beamer = 1.26/3.46 = 0.364 = PPT. YAY MATHS!  
Relative width to logo = 3.46/2.99 = 1.16 larger (or logo is 0.864 smaller) = PPT. YAY MATHS!  
Relative height to logo = 1.26/0.881 = 1.43 larger (or logo is 0.700 smaller) = PPT. YAY MATHS!  
  
###OK, summary time.  
We'll set the dimensions of the larger rectangle in the bottom right corner. All other dimensions (smaller   rectangle, logo/brand mark) will be set from there.
  
**Large Rectangle dimensions as a fraction of paperwidth/height:**  
Large rectangle width in Beamer = 3.46cm = 0.216\paperwidth  
Large rectangle height in Beamer = 1.26cm = 0.140\paperheight  
  
**Logo dimensions as a fraction of large rectangle dimensions:**  
Logo width in beamer = 2.99cm = 0.864\@UOWlargerectangle@width  
We don't need to define the logo height as the aspect ratio is constant.  
  
Thus far this had been for 16:6 aspect ratio All dimensions for the other aspect ratios will be set   proportionally from these.  