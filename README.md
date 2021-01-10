# valid-edges-graph
Find valid edges (follow) in a graph of users created from a collection of twitter users

## Introduction
Supervised learning binary classification task. A group of users from twitter who are interconneced to different degrees is used to creat a graph. The edges of the graph represent the unidirectional action of following a given user. Some edges are removed from the orginal network and they are used as ground truth to train Machine Learning classifiers. The training instances that account for false edges are created as random pairs with at least one followed/following user in common.

## Technologies
* Python 3
* networkx
* Sklearn

## Launch
Python notebook

## Sources
Twitter
