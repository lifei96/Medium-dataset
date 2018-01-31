# An anonymized dataset of 1+ million users in [Medium](https://medium.com/) online social network

Understanding Service Integration of Online Social Networks: A Data-Driven Study (full citation below)

Licensed under [Creative Commons Attribution Share Alike 4.0](http://choosealicense.com/licenses/cc-by-sa-4.0/).

## Description

This dataset covers 1,075,983 users in [Medium](https://medium.com/), including social graph and activity data for each user. Usernames are anonymized with numerical IDs.

## Files

Download links:

* [nodes.txt](https://drive.google.com/file/d/1hfhyg3o9Oi3aXcz5QBZZA3mwn_m02ZEP/view?usp=sharing): Node IDs (0 ~ 1,075,982) used to anonymize the dataset.</br>
Each line in ``nodes.txt`` is an ID for a user.

* [edges.txt](https://drive.google.com/file/d/1YLVO0mj1GPmCAxJRLVxyZnwNF8lxQZZc/view?usp=sharing): Edge list (30,026,896 edges) of the directed social graph.</br>
Each line in ``edges.txt`` is an directed edge. For example, "0 1" means user 0 is following user 1 in Medium.

* [user_data.csv]()

## BibTeX

```
@INPROCEEDINGS{Li_PerFoT18, 
author={Fei Li and Yang Chen and Rong Xie and Fehmi Ben Abdesslem and Anders Lindgren}, 
booktitle={2018 IEEE International Conference on Pervasive Computing and Communications Workshops (PerCom Workshops)}, 
title={Understanding Service Integration of Online Social Networks: A Data-Driven Study}, 
year={2018},
}
```
