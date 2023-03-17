# Interstate Highway Code
''' highway = int(input('What is the number of your interstate highway? '))
if 1 < highway < 100: #primary highway
    if highway % 2 == 0: #determining if even or odd
        print('The highway is primary highway I-',{highway}, 'and it travels east-west.')
    else:
        print('The highway is primary highway I-', {highway}, 'and it travels north-south.')
elif 999 >= highway >= 100: #auxilary highway
    primaryhigh = highway % 100 #divides highway to get the primary highway number
    if primaryhigh == 00: #accounting for numbers that end in 00
        print('Invalid highway number.')
        quit()
    direction = 'north-south' if primaryhigh % 2 == 1 else 'east-west' #if odd it runs north/south if even runs east/west and defines it as a variable in 'direction'
    print('the auxilary highway I-', {highway}, 'runs', {direction}, 'and is part of the I-', {primaryhigh}, 'interstate highway system.')
else:
    print('That is not a valid interstate highway number.')
    
[Main Page](https://github.com/JesseMorrison12/IT-1000-Midterm/blob/main/README.md)
