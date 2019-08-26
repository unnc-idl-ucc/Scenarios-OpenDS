# Scenarios-OpenDS
An intial release of scenario generations of OpenDS.
Building scenario does not require a programming language such as Java，Each scenario contains 5 xml files.

## Motivation

We use OpenDS to simulate a more realistic driving scenario. In order to better cater to our research, we need to build some specific driving scenarios.

## Introduction

This project aims to build scenarios for OpenDS framework. We upload some scenarios we build, some needed models and scnen files. We divide the scenarios into manual driving and automatic driving. There are four manual driving tasks, each with different parameter settings, such as the number of roads. There are six driving styles for autopilot tasks, each with three different speed scenes. We have also added some road conditions such as being overtaken by rear vehicles. 

## Goal

In this project, we want to use different parameter settings to simulate different driving situation. We also add some cars and pedestrians to make the scenario more realistic. Automated driving scenarios at different speeds can lead to better and more accurate results for research.

## Design_Choices

For manual driving tasks, we take the number of lanes, the speed limit, and the number of road vehicles as variables to build the scenarios. The automated driving task take the driving style and the average speed of the vehicle as variables. For each scenario, we add three main events and when people run these tasks, their action data will be recorded for future research.

## Contributors

[Shuolei Wang](https://github.com/ShuoleiWang), [Zilin Song](https://github.com/ZilinSONG), mentored by [Xiangjun Peng](https://github.com/Shiangjun)
