# straight-line
print('the points lie on the same line ')
x1=int(input('x1 = '))
y1=int(input('y1 = '))
x2=int(input('x2 = '))
y2=int(input('y2 = '))
x3=int(input('x3 = '))
y3=int(input('y3 = '))
x4=int(input('x4 = '))
y4=int(input('y4 = '))
s1=y2-y1/x2-x1
s2=y3-y2/x3-x2
s3=y4-y3/x4-x3
if s1== s2 == s3:
	print('it is a straight line')
else:
	print('it is not on a straight line')
