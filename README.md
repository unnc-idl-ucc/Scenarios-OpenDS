# Scenarios-OpenDS
An intial release of scenario generations of OpenDS

Motivation
============

We use OpenDS to simulate a more realistic driving scenario. In order to better cater to our research, we need to build some specific driving scenarios.

Introduction
============

This project aims to build scenarios for OpenDS framework. We upload some scenarios we build, some needed models and scnen files. We divide the scenarios into manual driving and automatic driving. There are four manual driving tasks, each with different parameter settings, such as the number of roads. There are six driving styles for autopilot tasks, each with three different speed scenes. We also add some road conditions that may be encountered such as being overtaken by others. 

Goal
============

In this project, we want to use different parameter settings to simulate different driving situation. We also add some cars and pedestrians to make the scenario more realistic. Automated driving scenarios at different speeds can lead to better and more accurate results for research.

Design_Choices
============

For the manual driving task, We take the number of lanes, the speed limit and the number of road vehicles as variables to build scenarios which is helpful for our research. The auto driving task take the driving style and the average speed of the vehicle as variables. For each scenario, we add three main events and when people run these task, Their action data will be recorded for future research.
