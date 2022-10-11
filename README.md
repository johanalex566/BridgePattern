The Bridge Design Pattern
-------------------------
Its purpose is to decouple an abstraction from its 
implementation so that the two can vary independently


What challenges the bridge pattern helps to overcome?

A new requerimient: Discount

The naive approach, Create two new inheritances for each license "MilitaryTowDaysLicense", "SeniorTowDaysLicense" and "MilitaryLifeLongLicense", "SeniorLifeLongLicense" in the last gerarchy shown on the image

Problem 
1: Exponential growth of complexity
2: Domain knowledge duplication
![image](https://user-images.githubusercontent.com/40399697/194780305-841f3421-f95a-4b20-99aa-02e73393c5ae.png)

How to solve it.

Applying the Bridge pattern

1: Split the class hierarchy
We are going to replace all these subclasses with a new class hierarchy


Pluralsight
By Vladimir Khorikov
