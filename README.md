# Fleet Operator

## Introduction

Fleet operator is a demonstration project to illustrate and practice hexagonal architecture designing. The business logic purpose is to simulate usage scenarios on an EV vehicles fleet depending on a sorting criterion used to decide if a vehicle of the fleet must be used or charged at some point.

## About hexagonal architecture

![hexagonal architecture scheme](https://blog.octo.com/wp-content/uploads/2020/06/archi_hexa_06-1024x526.png)

The hexagonal architecture is a designing paradigma which aims to uncouple the business logic (the hexagon) from the user and the server/resources sides. Practically its realized thanks to interface design pattern which allows to reverse server side dependency and weaken both sides coupling defining generic methods and rules to get and parse user inputs and server resources data. For more information see [hexagonal architecture by octo](https://blog.octo.com/architecture-hexagonale-trois-principes-et-un-exemple-dimplementation/).

## Practicing

The root folder contains two child folders. One to refactor to an hexagonal architecture and the other to explore a refactoring. There is multiple ways to do, the proposed refactoring may not be the best one.
