# exercise11
***
###Abstract
In this assignment, we are going to investigate problems associated with the motion fo hyperion and three body motions. As before, first we will see some visualized simulations. Then, we will gain more insights into the three body problem, and discuss the factors which would affect the celestial motions,and how the influence would be reflected by the Lyapunove exponent.
***
###Background
####Problem 4.19 
>Study the behavior of our mode for Hyperion for different initial conditions.Estimate the Lyapunov exponent from calculations of delta_theta,such as those shown in Figure 4.19.Examine this exponent varies as a function of the eccentricity of the orbit.

####Problem 4.20
>Our results for hte divergence of the two trajectories in the chaotic reime, shown on the right in Figure 4.19 are complicated by the way we dealt with the angle theta. In Figure 4.19, we followed the practice employed in Chapter 3 and restrict theta to the range -pi to pi,since angles outside this range are equivalent to the range -pi to pi, since angles outside theis range are equivalent to angles within it. However,when during the course of a calculation the angle passed out of htis range and is when "reset" this shows up in the results for delta theta as as discontinuous jump. Repeated the calculation of delta theta as in Fig 4.19, but do not restrict theta in this range. What is the origin of these but the smaller and more frequent dips will remain.
***
###Exercise

####visualizations
#####First, is the three body problem
![earth](https://github.com/LuxAsteria/test3/blob/master/k%3D1%20earth.gif)
when m=mass of jupiter

when it comes to 10m, the change of trajectory is not as conspicous as it's shown under the following condition.

![img](https://github.com/LuxAsteria/test3/blob/master/k%3D100%20erth.gif)
when it comes to 100m

#####Second, the influence of Jupiter on the asteriods(the same order as before)

![ast](https://github.com/LuxAsteria/test3/blob/master/k%3D1.gif)

![ast](https://github.com/LuxAsteria/test3/blob/master/k%3D10%20ast.gif)

![ast](https://github.com/LuxAsteria/test3/blob/master/k%3D100%20ast.gif)

[for code please click here](https://github.com/LuxAsteria/exercise11/blob/master/code)

####Level 1:the Leyapunov exponent of the motion(how omega change)

![hy](https://github.com/LuxAsteria/test3/blob/master/omega.png)
![hy](https://github.com/LuxAsteria/test3/blob/master/omega2.png)

####Level 2: how delta_theta change with the initial state:

When alpha(the coefficient of modification of relativity) is 0

![img](https://github.com/LuxAsteria/test3/blob/master/deltatheta.png)

![img](https://github.com/LuxAsteria/test3/blob/master/delta.png)

When alpha is 0.0001

![img](https://github.com/LuxAsteria/test3/blob/master/theta_t.png)

![img](https://github.com/LuxAsteria/test3/blob/master/theta_t2.png)

When alpha is 0.0008

![img](https://github.com/LuxAsteria/test3/blob/master/屏幕快照%202016-12-01%20下午8.16.23.png)

![ing](https://github.com/LuxAsteria/test3/blob/master/屏幕快照%202016-12-01%20下午8.16.00.png)

Then, the influence of eccentricity on theta

![img](https://github.com/LuxAsteria/test3/blob/master/屏幕快照%202016-12-01%20下午8.25.10.png)

![img](https://github.com/LuxAsteria/test3/blob/master/屏幕快照%202016-12-01%20下午8.25.36.png)

####three body problem--trajectories of earth(with no relativity)

![i](https://github.com/LuxAsteria/test3/blob/master/屏幕快照%202016-12-04%20上午9.31.01.png)

![i](https://github.com/LuxAsteria/test3/blob/master/屏幕快照%202016-12-04%20上午9.30.40.png)

![i](https://github.com/LuxAsteria/test3/blob/master/屏幕快照%202016-12-04%20上午9.30.23.png)

###three body problem--trajactories of earth (with relativity)

![i](https://github.com/LuxAsteria/test3/blob/master/屏幕快照%202016-12-04%20上午9.31.50.png)

![i](https://github.com/LuxAsteria/test3/blob/master/屏幕快照%202016-12-04%20上午9.32.36.png)

![i](https://github.com/LuxAsteria/test3/blob/master/屏幕快照%202016-12-04%20上午9.33.08.png)

###Jupiter's effect on asteroid

![o](https://github.com/LuxAsteria/test3/blob/master/屏幕快照%202016-12-04%20上午9.34.07.png)

![i](https://github.com/LuxAsteria/test3/blob/master/屏幕快照%202016-12-04%20上午9.34.50.png)

[for code please click here](https://github.com/LuxAsteria/exercise11/blob/master/code)
***
###Conclusion
In conclusion, we find that when the mass of jupiter is large enough, the motion of earth (or astroid) will dramaticly change, which means it will goes into an extreme unstable. And the motion of hyperion, it is sensitive to the initial state, and will apparently change if we set the original state different.
***
###Acknowledge

[1]Computational Physics, Edition 2, Nicholas J.Giordano & Hisao Nakanishi
***

##PS:ALL Rights Reserved
