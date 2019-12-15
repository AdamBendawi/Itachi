# Itachi
Anime Character design 
from time import *
from random import *
from tkinter import *
tk = Tk()
screen = Canvas(tk, width=1000, height=1000, background="#edd6b7")
screen.pack()



#Eye Detail 1
screen.create_line( 410, 430, 434, 480, 360, 560, 325, 610, fill = "black", smooth = True, width = 5)

#Eye Detail 2 
screen.create_line(615, 436, 603, 490, 650, 532, 713, 592, fill = "black",  smooth = True,width = 5)    

#Face Detail
screen.create_line(478, 594, 478, 706, fill = "black", width = 2)

#Face Detail 2

screen.create_line(558, 492, 548, 614, fill = "black", width = 2, smooth = True)

#HeadBand
screen.create_polygon(0, 0, 176, 306, 330, 340, 500, 361, 699, 340, 895, 306, 1000, 0, fill = "grey",outline = "dark blue", width = 15)

#HeadBand Shadow
screen.create_polygon(285, 9, 285, 100, 279, 200, 279, 320, 225, 310, 212, 200, 208, 100, 210, 9, fill = "#d1cdcd")

#Scratch
screen.create_polygon(1000,100, 702, 100, 550, 104, 472, 106, 430, 110, 370, 104, 300, 104, 240, 100, 0, 100, 0, 87, 200, 87, 300, 85, 400, 92, 430, 95, 500, 90, 540, 90, 600, 81, 750, 81,
                     1000, 81, outline = "black", fill = "#3d3c3c", width = 2)   


#Eye
screen.create_oval(350, 460, 240, 370, fill = "#a10000", outline = "black", width = 4)

#Eye 2
screen.create_oval(700, 460, 815,360, fill = "#a10000", outline = "black", width = 4)

   
##Eye 1 Pupil
screen.create_oval(281, 427, 313 , 402, fill = "black")

#Eye 1 Reflection
screen.create_oval(275, 423, 250, 405, fill = "white", outline = "white")
    
###Eye 2 Shape
##screen.create_polygon(759, 354, 751, 375, 760, 389.5, 776, 400, 785, 412, 786, 431, 773, 414, 762, 412, 753, 415, 738, 422, 722, 425, 705, 416, 730, 410, 736, 396, 737, 380, 742, 364, 750, 356, fill = "black", smooth = True)
##
#Eye 2 Pupil
screen.create_oval(771, 422, 743, 397, fill = "black", width = 3)


#Eye 2 Reflection
screen.create_oval(730, 420, 705, 402, fill = "white", outline = "white")

#Eye Layout
screen.create_line(397, 450, 374, 420, 350, 400, 300, 365, 260, 356, 202, 354, 183, 333, 197, 356, 170, 356, 176, 374, 203, 436, 188, 454,
                   207, 443, 203, 469, 228, 452, 250, 457, 380, 460, fill = "black", width = 5)

#Eye Layout 2
screen.create_line(650, 445, 720, 370, 772, 350, 800, 345, 835, 346,880, 358, 895, 360, 884, 375, 892, 376,
                   850, 425, 824, 455, 812, 460, 692, 460, fill = "black", width = 5)
 

    
#Hair 1 
screen.create_polygon(700, 0, 700, 80, 700, 150, 700, 250, 700, 300, 697, 350 ,692, 400, 688, 450, 684, 500, 680, 550, 675, 600, 668, 650, 661, 700, 652, 750, 645, 790, 640, 790,
                      644, 750, 649, 700, 650, 650, 655, 600, 657, 550, 659, 500, 662, 450, 664, 400, 665, 350, 665, 300, 664, 250, 663, 200, 660, 150, 657, 100, 654, 50, 650, 0, fill = "black")         
#Hair 2
screen.create_polygon(873, 0, 873, 100, 873, 150, 873, 200, 873, 250, 868, 300, 866, 350, 862, 400, 856, 450, 850, 500, 847 , 550, 850, 500, 849, 450, 849, 400, 846, 350, 843 , 300,
                      839, 250, 832, 200, 824, 150, 815, 100, 805, 50 , 800, 0 , fill = "black")
#Hair 3
screen.create_polygon(200, 0, 197, 50, 193, 100, 188, 150, 183, 200, 178, 250, 169, 300, 161, 350, 159, 400, 156, 450, 155, 500, 153, 550, 150, 600, 153, 650, 155, 700, 168, 750, 148, 750,
                      145, 700, 140, 650, 138, 600, 135, 550, 135, 500, 135, 450, 137, 400, 137, 350, 140, 300, 143, 250, 145, 200, 145, 150, 150, 100, 150, 50, 154, 0, fill = "black")
#Hair 4
screen.create_polygon(873, 0 , 873, 50, 873, 100, 885, 150, 891, 200, 895, 250, 898, 300, 901, 350, 904, 400, 905, 450, 907, 500, 910, 550, 909, 600, 909, 650, 907, 700, 907, 750, 948, 750, 948, 700, 952, 650, 956, 600, 958, 550, 960, 500, 961, 450, 960, 400, 960, 350, 964, 400,
                      969, 450, 974, 500, 976, 550, 982, 600, 986, 650, 988, 700, 988, 750, 1000, 750, 1000, 0, fill = "black")

#Hair 5
screen.create_polygon(200, 0, 155, 50, 155, 100, 146, 150, 146, 200, 146, 250, 146, 300, 146, 350, 146, 400, 128, 450, 121, 500, 114, 550, 111, 600, 107, 650,
                      101, 700, 100, 750, 0, 750, 0, 500, 5, 450, 8, 400, 10, 350, 18, 300, 23, 250, 28, 200, 33, 150, 38, 100, 45, 50, 48, 0, fill = "black")    
#Hair 6
screen.create_polygon(48, 0, 48, 50, 48, 500, 0, 500, 0, 0, fill = "black")

#Hair 7
screen.create_polygon(355, 0, 347, 100, 342, 200, 336, 300, 333, 400, 341, 500, 351, 600, 374, 700, 383, 730, 370, 700, 344, 600, 325, 500, 313, 400, 306, 350 ,302, 300, 300, 200, 300, 100, 303, 0, fill = "black")
 

#Hair Shadow 1
screen.create_polygon(22, 0, 20, 50, 17, 100, 16, 150, 14, 200, 11, 250, 11, 300, 9, 350, 6, 400, 5, 450, 0, 500, 0, 0, fill = "#252626")

#Hair Shadow 2
screen.create_polygon(104, 0, 101, 50, 91, 100, 84, 150, 76, 200, 70, 250, 63, 300, 60, 350, 52, 400, 49, 450, 45, 500, 42, 550, 40, 600, 42, 750, 0,
                      750, 0, 500, 10, 400, 18, 300, 28, 200, 39, 100, 48, 0, fill = "#252626")       

#Hair Shadow 3
screen.create_polygon(190, 0, 178, 100, 167, 200, 156, 300, 148, 400, 146, 500, 149, 600, 154, 700, 155, 750, 147, 750, 145, 700, 140, 600, 136, 500, 136, 400, 140, 300, 145, 200, 150, 100, 155, 0, fill = "#252626")

#Hair Shadow 4
screen.create_polygon(320, 0 , 310, 100, 309, 200, 311, 300, 318, 400, 327, 500, 325, 500, 313, 400, 303, 300, 298, 200, 300, 100, 303, 0, fill = "#252626")     

#Hair Shadow 5
screen.create_polygon(675, 0, 676, 100, 676, 200, 674, 300, 670, 400, 666, 500, 662, 600, 658, 610, 655, 600, 660, 500, 664, 400, 664, 300, 662, 200, 658, 100, 651, 0, fill = "#252626")

#Hair Shadow 6
screen.create_polygon(860, 0 , 860, 100, 852, 210, 834, 100, 820, 0, fill = "#252626")

 
#Coat
screen.create_polygon(0,704,  7, 704, 7, 706, 12, 706, 12, 708, 32, 708, 32, 711, 59, 711, 182, 754, 360,754, 360, 780, 640, 780, 750, 780,
                      800, 770, 900, 730, 1000, 710, 1000, 1000, 0, 1000, 0, 0, fill = "#1a1a1a")




###Grid lines
##spacing = 50
##
##for x in range(0, 1000, spacing): 
##    screen.create_line(x, 25, x, 1000, fill="white")
##    screen.create_text(x, 5, text=str(x), font="Times 9", anchor = N, fill = "white")
##
##for y in range(0, 1000, spacing):
##    screen.create_line(25, y, 1000, y, fill="white")
##    screen.create_text(5, y, text=str(y), font="Times 9", anchor = W, fill = "white")
##
##screen.update()
