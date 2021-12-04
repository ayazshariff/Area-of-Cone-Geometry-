# Area-of-Cone-Geometry-
#Area of Cone (3D)

#python code to find area of cone

#cone has two area, 1 base 2 lateral surface area

import math

h = 20 #cm

r = 10 #cm

b = 3.142 * (r**2)

l = math.sqrt((h^2) + (r^2))

a = b + l

print("Area of Cone Base and Lateral area:", a)
