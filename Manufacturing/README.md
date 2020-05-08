#  CAE analysis
>Here is our report on the work undertaken

The main goal was to make static stress and dynamic load analysis in CAD system

## Introduction 
When designing mechanical objects we often want them to be just adequately sturdy. We want make mechanism in such a way to reduce chances of breakage, don’t allow tool to be too whimpy 

By simulating static stress we are going to strip down unnecessary parts and reinforce weak-points BEFORE sending them to production

We applied forces, taken from 2 assignment - dynamic of mechanism. There will be links to previous results

>Problems faced: all computation for CAE analysis take a LOT of time, thus, analysis of all cases and solution of different problems took a vast amount of our life

## Static Stress
Firstly, we applied forces to 3D model created in previous assignment. We choose configuration, in which bear force is the greatest. It is a point when the tip reaches the lowest point - when maximum force acts on bear, it should be crushed


### There are problems, that we faced: 
* the tip is severely deformed, due to the reason, that bear force is applied to end of link is big. Here you can see deflection and of tool tip. There also is a video with deflection process. Also all links in mechanism are insufficiently tortified, thus, we need to strengthen them somehow

<img src="./images/t1.png" width="400">
<img src="./images/t2.png" width="400">
<img src="./images/l1.png" width="400">
 
 >  How we decieded to solve it? We decieded that to make the link and tip more lasting, we need to strandthen the mechanism

  

* gears are to narrow, original width does not allow to withstand attached moments. We assumed that it is possibe to reduce deflection increacing the width of gears, but teeth deflection steel exis
<img src="./images/m1.png" width="400">
<img src="./images/m2.png" width="400">
<img src="./images/b1.png" width="400">

 > That is why we decieded not only to make wheels wider, but also increase theeth size
 
 
