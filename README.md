# Lottery-EDA

[![License](http://img.shields.io/badge/license-MIT-green.svg?style=flat)](https://github.com/Solvve/Lottery-EDA/blob/master/LICENSE.txt)
[![Python 3.7](https://img.shields.io/badge/python-3.7-blue.svg)](https://www.python.org/downloads/release/python-378/)
[![Solvve](https://img.shields.io/badge/made%20in-solvve-blue)](https://solvve.com/)


## Description

<img src="https://solvve.com/wp-content/uploads/2020/08/drew-beamer-qzWwb2UdGhE-unsplash-min-1-min-1-min-1-1024x683.jpg" style="width:50%"></img>

Four digits lottery exploratory data analysis.

Fairness of a lottery presumes that any number has the same opportunity to become a winning one. When numbers are not equally distributed it signals that numbers are not random. Subsequently, it means that the process is consciously or by some unknown pitfall is rigged to draw certain numbers more often than the others. Thus, the lottery is not fair.

The first step is to figure out how random are the winning numbers. To assess their randomness machine learning experts run primarily statistical analysis. The goal is to see if the numbers meet the criteria of uniform distribution, meaning that each and every number has the same odds to be drawn.

There are several criteria to measure this uniform randomness: extreme points criteria, Foster-Stuart criteria, and Spearman’s rank correlation coefficient. They help to understand if there are any features of the time series pointing out to patterns in what numbers win more often.

The second step is to identify distribution. This is yet another way of looking at what numbers tend to win more often and what numbers are less common in the winning sequences. There are three ways to identify distribution: by histogram, by [skew](https://en.wikipedia.org/wiki/Skewness) and [kurtosis](https://en.wikipedia.org/wiki/Kurtosis), and by [probability grid](https://en.wikipedia.org/wiki/Probability_plot). All of them help to visualize the data and locate anomalies.
