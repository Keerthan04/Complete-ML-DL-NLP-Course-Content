## Learn from the pdf the equation of line and also here learn
we can write the eqn of line as 
y=mx+c
ax+by+c=0
by+c = -ax
by = -ax-c
y=(-a/b)x -(c/b) which is same of y=mx+c

another we can write as 
w1x1+w2x2+b = 0
w(trans)x+b=0 where w is a matrix with w1 and w2 coeff for each and then can multiply matrix and get and x is alos a matrix with x1,x2,x3

with respect to a 3D there is a plane like there and eqn we can get using
w1x2+w2x2+w3x3+b = 0
w(trans)x+b=0 so w is matrix with 3x1 as w1,w2,w3

so if a nD plane also we can write as same 
wTx+b=0 with w and x being to n as nD
if the straight line passes through the origin then b is 0 in all so 
we get 

the plane is represented by pi(like pi symbol)
wTx=0(eqn of line passing through origin)
so equation of a plane same pass through origin will be wTx=0(same as line just high dimension like 3d)

wTx is same like doing dot product as w.x
w.x = mag(w)*mag(x)*cos(tita) = 0
(mag is magnitude)

when theta is 90 cos0 is 0 

so if we have a line(plane) then w is a vector which is perpendicular to plane at 90degree and x are cordinates on plane 


so if plane also w is perpendiculat to the plane 


so w is vector always perpendicular to line or plane and equation is 
wTx=0(when passing through the origin of line and plane)

## Distance of a point from a plane(IMP FOR SVM)
if we have a plane with wTx=0 passes through origin and w vector perpendicular is there 
and we have two points 
S and S(dash)  (x1,x2,x3...xn)(both on diff sides of the plane) then the distance bewtnween these S and plane is calculated by formula

d = wTS/mag(w)  the mag(w)=root of (all w ka)
wTS=mag(w)mag(S)cos0
so if we take w and S joining line the angle between it is always less than 90 so cos0 is +ve value so the value of 
d is always +ve value(i.e wTS is always +ve)

so d(dash) using S(dash) w is in opp direction to S(dash) for this 0 is alway greater than 90 and less than 180 so the d is always -ve 

# IMP
so any point above plane is +ve distance
and any point below plane is -ve distane

# Instace vs Model Based Learning(Learning of the Model)
for use case we do ML model which are based on 2 types
1.Instance based learning 
2.Model based learning
in Instance based learning,model depends on the data and surrounding and makes output for the new one ex:KNN

for model based learning ,from the available data patterns is found then generalization for it is done then does predicts for new data

The difference between both is there in the pdf