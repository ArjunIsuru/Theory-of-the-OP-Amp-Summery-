# Theory-of-the-OP-Amp-Summery-

*Uses of IC 741 - Operational Amplifier*

_1.) As a Voltage comparator_

If we enter two inputs to the IC ( V1,V2)

Then We know  that the basics theory of IC...

V out = A [ (V+) - (V-)] = ± Vs

If V+  = V1 
    V-   = V2

If V1 > V2 then the Output will be +Vs

And If the output will be - Vs then 
V1 < V2...

That is the method how can compare the Voltages ...

_2.) For Non- Inverting Amplifier_

Using Golden Rules about IC...

Then
V+ = V- and the current into the IC can be neglected 

Then, 
V In = I R1

V Out = I ( R1 + R2)

V Out / V In = 1 + R2/R1

Then You can multiply a number by a constant...
And you can amplify non invertingly voltages...
And the maximum Value and the minimum outputs are +Vs and -Vs respectively...

_3.) Inverting Amplifiers_

Like the second one...We can prove that,

0- V In = I R1

V Out - 0 = I R2


V Out / V In = -R2/R1 

Now you can multiply a number by a minus number...

And you can Amplify and Invert a Voltage...

Such as:-

V= V0 Sin wt  to  V= V' Sin ( -wt)

V = V0 Tan wt  to  V= V' Tan (-wt)

V = V0 Cos wt  to
V = V' Cos ( pi - wt)


_4.) Voltage Follower_

This is using for repeating the same signal...

Using Golden Rules   

V+ = V-

V Out= V In


_5.) Inverting Summing Amplifier_


This is used for summing the Voltages as numbers with inverting...

Using Golden Rules,

I1 = V1/R1

I2 = V2/R2

I3 = V3/R3
.....
.....
.....

In = Vn/Rn

Now Using Kirchoff's Laws
£I = I1 + I2 +……… + In = V1/R1 + V2/R2 +……… + Vn/Rn 

0 - V Out = £I Rf

V Out = - Rf ( V1/R1 + V2/R2 +……… + Vn/Rn )

Examples:- 
V1 Sin (wt) and V2 Sin (w' t) to,

V out = - V3 Sin (w"  t)

_6.) Differential Amplifier_

Using potential Division and 1st  Golden Rule...

V+ = V2 R4/ (R3 + R4)

Then V+ = V-

Now,

[V1 - V2 R4/ (R3 + R4) ]/R1 = [ V2 R4/ (R3 + R4)  - V Out]/ R2

V Out = [V2 R4/ (R3 + R4)  (1 + R2/R1) ] -   [V1 R2/R1]

This is a difficult mathematical operator with IC's...

If R1 = R3 and R2 = R4

Then V out new =  (R2/R1) (V2- V1)

That shows that this Circuit can amplify the voltages continuously between  +Vs and -Vs...

_7.) Differentatior Amplifier_
 
This Circuit can do Differentation...

If C = capacitiance of the Capacitior
   R = Value of the Resistor...

 V out = R C (d Vin/dt) 

This can be proved using dt for a capacitior... That has a long proof...
So I don't mention it in this... 
This is proved  without using the First golden rule..
So We cannot ignore the Current through IC...
This can be used for Scientific Calculators and doing other tasks in any field ...

(Simple proof:- 
For the capacitior 

I =C d(V In-0) /dt

For the resistor,

I =(0- V Out)/R

Now,
V Out = -RC d(V In)/dt)

For Examples :-

V= V0 Sin wt    to
V = -RC V0 Cos wt


V = V0 Tan wt   to
V = -RC V0 Sec^2 (wt)
 
_8.) Intergrator Amplifier_

This can be used for intergrating the difficultive Functions...

For this we use C capacitior and a R Resistor...
Like the method Which can prove the Differentator Circuit this is also an difficult and long proof...

So I write only the Function...

V Out = -1/RC | V In dt

(Simple proof:- 
For the capacitior 

I =C d(V Out - 0) /dt

For the resistor,

I =(0- V In)/R

Now,
V Out = -1/RC | (V In )dt

For examples:-

V=  V0 Sin wt   to  V =  -1/RC V0 Cos wt 


V = V0 Tan wt   to
V = -1/RC V0  ln (Sec (wt))

*Arjun (Isuru) 🍁✨*
