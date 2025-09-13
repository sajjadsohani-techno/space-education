from random import*

names = input("enter your name please:")
print("welcome",names)

numbers = randint(1,999999)
print(numbers)
codes = input("please enter the code:")

if int(codes) == numbers:
    print("unlock")
else:
    print("locked: the code its not correct")
    exit()

answer = "y"
n = "n"

while answer == "y":
    moon = "moon"
    mars = "mars"
    jupiter = "jupiter"
    sun = "sun"
    
    pick = input("pick up one planet or moon(moon,mars,jupiter,sun):")

    if pick == "moon":
    
        a = input("sey your mass type (a):")
            
        if a == "a":
            my_mass_a = input("sey your mass:")        
            mass_a = float(my_mass_a) * 0.16        
            print("your mass in moon is",mass_a)        
        else:
            print("type erorr: you have to type a")

        b = input("how much you can jump on earth type(b):")
            
        if b == "b":
            jump_a = input("how much you can jump on earth:")
            moon_gravity = 0.16
            moon_jump = float(jump_a) / moon_gravity 
            print("you jump in moon at ",moon_jump)
        else:
            print("type erorr: you have to type b")

        c = input("how much you can run in earth km/h type(c):")

        if c == "c":
            speed_a = input("how much you can run in earth km/h:")
            moon_speed = float(speed_a) * 2.5
            print("your speed in moon is",moon_speed)
        else:
            print("type erorr: you have to type c")

        d = input("how many calories did you burn todey on earth type d:")

        if d == "d":
                calories_a = float(input("how many you burn on earth:"))
                moon_calories = calories_a * 0.165
                print("on the moon it would be about",moon_calories)
        else:
            print("type erorr: you have to type d")


    elif pick == "mars":

        a = input("sey your mass type (a):")

        if a == "a":
            my_mass_b = input("sey your mass:")
            mass_b = float(my_mass_b) * 0.38
            print("your mass in mars is",mass_b)
        else:
            print("type erorr: you have to type a")

        b = input("how much you can jump on earth type(b):")
        
        if b == "b":
            jump_b = input("how much you can jump on earth:")
            mars_gravity = 0.38
            mars_jump = float(jump_b) / mars_gravity
            print("you jump in mars at ",mars_jump)
        else:
            print("type erorr: you have to type b")

        c = input("how much you can run in earth km/h type(c):")

        if c == "c":
            speed_b = input("how much you can run in earth km/h:")
            mars_speed = float(speed_b) * 1.6
            print("your speed in mars is",mars_speed)
        else:
            print("type erorr: you have to type c")

        d = input("how many calories did you burn todey on earth type d:")

        if d == "d":
                calories_b = float(input("how many you burn on earth:"))
                mars_calories = calories_b * 0.38
                print("on the mars it would be about",mars_calories)
        else:
            print("type erorr: you have to type d")


    elif pick == "jupiter":

        a = input("sey your mass type (a):")

        if a == "a":
            my_mass_c = input("sey your mass:")
            mass_c = float(my_mass_c) * 11
            print("your mass in jupiter is",mass_c)
        else:
            print("type erorr: you have to type a")

        b = input("how much you can jump on earth type(b):")
        
        if b == "b":
            jump_c = input("how much you can jump on earth:")
            jupiter_gravity = 11
            jupiter_jump = float(jump_c) / jupiter_gravity
            print("you jump in jupiter at ",jupiter_jump)
        else:
            print("type erorr: you have to type b")

        c = input("how much you can run in earth km/h type(c):")

        if c == "c":
            speed_c = input("how much you can run in earth km/h:")
            jupiter_speed = float(speed_c) * 0.09
            print("your speed in jupiter is",jupiter_speed)
        else:
            print("type erorr: you have to type c")

        d = input("how many calories did you burn todey on earth type d:")

        if d == "d":
                calories_c = float(input("how many you burn on earth:"))
                jupiter_calories = calories_c * 2.34
                print("on the jupiter it would be about",jupiter_calories)
        else:
            print("type erorr: you have to type d")
            

    elif pick == "sun":

        a = input("sey your mass type a:")
        
        if a == "a":
            my_mass_d = input("sey your mass:")
            mass_d = float(my_mass_d) * 27.9
            print("your mass in sun is",mass_d)
        else:
            print("type erorr: you have to type a")

        b = input("how much you can jump on earth type(b):")
        
        if b == "b":
            jump_d = input("how much you can jump on earth:")
            sun_gravity = 27.9
            sun_jump = float(jump_d) / sun_gravity
            print("you jump in sun at ",sun_jump)
        else:
            print("type erorr: you have to type b")

        c = input("how much you can run in earth km/h type(c):")

        if c == "c":
            speed_d = input("how much you can run in earth km/h:")
            sun_speed = float(speed_d) * 0.2
            print("your speed in sun is",sun_speed)
        else:
            print("type erorr: you have to type c")

        d = input("how many calories did you burn todey on earth type d:")

        if d == "d":
                calories_d = float(input("how many you burn on earth:"))
                sun_calories = calories_d * 28
                print("on the sun it would be about",sun_calories)
        else:
            print("type erorr: you have to type d")        
        
    else:
        print("type eroor: you have to type moon mars or jupiter")
        
                                        
    answer = input("do you want to pley again(y,n)")

if n == "n":
    points = input("goodbay,please rate us(very bad , good , amazing) :")
    exit("thank you for rate us")
  
