The Bridge Design Pattern
-------------------------
Its purpose is to decouple an abstraction from its 
implementation so that the two can vary independently

Best definition

Its purpose is to decouple an abstraction from its implementation so that the can vary independently


What challenges the bridge pattern helps to overcome?

A new requerimient: Discount

The naive approach, Create two new inheritances for each license "MilitaryTowDaysLicense", "SeniorTowDaysLicense" and "MilitaryLifeLongLicense", "SeniorLifeLongLicense" in the last gerarchy shown on the image

Problem 
1: Exponential growth of complexity
2: Domain knowledge duplication
![image](https://user-images.githubusercontent.com/40399697/194780305-841f3421-f95a-4b20-99aa-02e73393c5ae.png)

How to solve it.

Applying the Bridge pattern

1: Split the class hierarchy,
we are going to replace all these subclasses with a new class hierarchy

![image](https://user-images.githubusercontent.com/40399697/194981571-bd3e7f1b-1dd3-4b00-acce-8ef12b031761.png)

Now our code no DRY violation (Don't repeat yourself)
Simplified the code

The bridge pattern replaces complexity mmultiplication with complexity addition.

Complexity emerges from coupling, coupling is connections between code elements

![image](https://user-images.githubusercontent.com/40399697/194982390-4eff832e-aa39-40ba-87e9-31dd8076557c.png)

With Bridge pattern therefore achieved high cohesion among elements of each aspect and loose coupling between the aspects of themselves.

We ave replaced connection multiplication with connection addition.



Pluralsight
By Vladimir Khorikov
