# OnlineAssesment - Fleet Scheduling
Online Assesment to complete the charge scheduler of the car fleet.

Main logic is in the file - ChargeSchedule.java . It contains one test case in the main method.
Various test cases are added to test case file  - ChargeScheduleTest.java

There werre multiple solutions, In this approach I chose to charge the cars with higher percentage first because, to maximize the numbers of cars that can finish charging to full before the endtime.

Picked the first available charger. If two or more chargers were available, I chose the one with higer charging power.
