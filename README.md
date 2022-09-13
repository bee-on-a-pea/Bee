# Bee
#Write a python program to read three coefficients of a quadratic equation  AX2 + BX + C = 0 and find the roots of the equation 

# Getting our inputs

A = float(input('Enter value for coefficient A: '))
B = float(input('Enter value for coefficient B: '))
C = float(input('Enter value for coefficient C: '))

#Quadratic Calculation 

inside_calculations = (B ** 2)-(4 * A * C)      
Root_1 = (-B + (inside_calculations**0.5) )/ (2 * A) #first approach: done so that calculation does 
                                                                            #not get too complicated


Root_2 = (-B - (((B ** 2)-(4 * A * C) )** 0.5)) / (2 * A)   #second approach

#Outputting our values
print('\n Your coefficient A value is:',A,'\n Your coefficient B value is:', B,'\n Your coefficient C value is:' , C )
print (' Your Root values are:', Root_1 , 'and ', Root_2)
