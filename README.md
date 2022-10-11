The Bridge Design Pattern
-------------------------
Its purpose is to decouple an abstraction from its 
implementation so that the two can vary independently

Best definition

Its purpose is to split a class hierarchy through composition to reduce coupling


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

![image](https://user-images.githubusercontent.com/40399697/194983086-59329483-b91c-4365-a914-378a0761b7ae.png)

Now our code no DRY violation (Don't repeat yourself)
Simplified the code


Complexity emerges from coupling, coupling is connections between code elements

![image](https://user-images.githubusercontent.com/40399697/194982390-4eff832e-aa39-40ba-87e9-31dd8076557c.png)

With Bridge pattern therefore achieved high cohesion among elements of each aspect and loose coupling between the aspects of themselves.

We ave replaced connection multiplication with connection addition.



Pluralsight
By Vladimir Khorikov
