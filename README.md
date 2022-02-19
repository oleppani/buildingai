# Classifying public decision-making cases with AI

Final project for the Building AI course

## Summary

The First step is to download municipalities decision-making board's agendas and minutes from websites and store data into CSV-file. The second step is to create classes for cases. The third step is to classify couple of hundred cases as a teaching material. The fourth step is to create AI code for classifying cases. The fifth step is to run AI classifying.


## Background

Which problems does your idea solve? How common or frequent is this problem? What is your personal motivation? Why is this topic important or interesting?

This is how you make a list, if you need one:
* What kind of cases are decided in decision-making boards?
* What kind of cases are the most common?
* What kind of cases are the most rarest?


## How is it used?

Describe the process of using the solution. In what kind situations is the solution needed (environment, time, etc.)? Who are the users, what kinds of needs should be taken into account?

The classifying will be used when new agendas and minutes are published, approximately once a week. The users for the results of process are journalists, municipalities officers, board members and citizens. Filtering cases by selecting different categories should be possible for the users and overall statistics should be available too. 


## Data sources and AI methods
Where does your data come from? Do you collect it yourself or do you use data collected by someone else?

The data will be collected from municipalities websites by myself.

Here's some examples:
[City of Tampere](https://tampere.cloudnc.fi/fi-FI)
[City of Pori](https://pori.cloudnc.fi/fi-FI)
[City of Järvenpää](https://jarvenpaa.cloudnc.fi/fi-FI)


| Syntax      | Description |
| ----------- | ----------- |
| Caseid      | Officia ID  |
| Casetext    | Text        |
| Decision    | Text        |
| Header      | Title       |
| Preparer    | Name        |
| Board       | Decider     |
| Proposal    | Text        |

Used method is classifying method.

## Challenges

What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?

Classifying is maybe not 100% right and the results should be evaluated before using them in important tasks-

## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on?

Next phase can be forecasting decisions from agendas proposal text. Teaching materials can be collected from agendas and minutes from same meetings.


## Acknowledgments

