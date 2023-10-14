# Cocomo-2-model
COCOMO II (Constructive Cost Model II) is a software cost estimation model developed by Barry Boehm in the 1990s as an extension of his earlier COCOMO model (COCOMO I). COCOMO II is designed to help project managers and software developers estimate the cost, effort, and duration required to develop a software project.

The estimation of effort is done by using object points.

The object point is an indirect software measure that is computed using counts of the number of screens, reports, and components likely to be required to build the application. It is a software estimation technique that focuses on the functional size of a software application.

The procedure to estimate effort is given below.

1.Each object instance is classified into one of three complexity levels.

![image](https://github.com/T-Anushri/Cocomo-2-model/assets/142531710/539f84a8-1f38-43d8-ae1f-4c1f1574e76a)

2.The total object point count is calculated as sum of the product of the original number of object instances by the complexity weight i.e.,

Object points = (Number of screens * complexity weight) + (Number of reports * complexity weight) + (Number of software components * complexity weight)

3.When component/software reuse to be applied, percent of reuse is estimated and object point count is updated as:

New object points = Object points * ((100-reuse%)/100)

4.Productivity rate for different levels of developer experience and development environment maturity is given by the following table:

![image](https://github.com/T-Anushri/Cocomo-2-model/assets/142531710/2c574cfe-4ec1-4ceb-bc9c-ad5ce64d9416)

5.Once the productivity rate has been determined, an estimate of project effort is computed as: 

Estimated effort = New object points/Productivity rate
