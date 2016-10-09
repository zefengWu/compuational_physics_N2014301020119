
#吴泽峰  2014301020119


##问题：

*Consider again a decay problem with two types of nuclei A and B,but now suppose that nuclei of type A decay ones of type B,while 
nuclei type of B decay into ones of A.Strictly speaking, this is not a decay process, since it is possible for the type B nuclei to turn
back into type A nuclei. A better analogy would be a resonance in which a system can tunnel or move back and forth between two states A 
and B which have equal energies. The corresponding rate equations are

![](https://github.com/zefengWu/compuational_physics_N2014301020119/blob/master/CodeCogsEqn.png)

 where for simplicity we have assumed that the two types of decay are characterized by the same time constant, tau. Solve this system of
equation for the numbers of nuclei, NA and NB, as functions of time. Consider different initial conditions, such as NA=100, NB=0, etc,
and take tau=1s. Show that your numerical results are consistent with the idea that the system reaches a steady state in which NA and
NB are constant. In such a steady state, the time derivatives dNA/dt and dNB/dt should vanish.

##解决：
*根据这章内容，可得：

![](https://github.com/zefengWu/compuational_physics_N2014301020119/blob/master/1.png)
 
 而可得到：

![](https://github.com/zefengWu/compuational_physics_N2014301020119/blob/master/3.png)

（说明：我们取NA=100,NB=0,tau=1s,time step=0.1)

##代码

![](https://github.com/zefengWu/compuational_physics_N2014301020119/blob/master/temp.py)

输出结果：

![](https://github.com/zefengWu/compuational_physics_N2014301020119/blob/master/figure_1.png)

##分析：

从结果易见得最后NA和NB都趋于一个稳定状态，而且它们变化值变为0.
