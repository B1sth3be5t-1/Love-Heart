# Love-Heart
Make sure to change the first set of quotes, and then change the (x-y)%(this number) to the length of the str.

print('\n'.join([''.join([('Dakota&Brian-'[(x-y)%13]if((x*0.05)**2+(y*0.1)**2-1)**3-(x*0.05)**2*(y*0.1)**3<=0 else' ')for x in range(-30,30)])for y in range(15,-15,-1)]))
