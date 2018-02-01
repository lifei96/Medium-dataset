# An anonymized dataset of 1+ million users in Medium online social network

Understanding Service Integration of Online Social Networks: A Data-Driven Study (full citation below)

Licensed under [Creative Commons Attribution Share Alike 4.0](http://choosealicense.com/licenses/cc-by-sa-4.0/).

## Description

This dataset covers 1,075,983 users in [Medium](https://medium.com/), including social graph and profile/activity data for each user. Usernames are anonymized with numerical IDs. This dataset was collected during August 2016.

## Files

Download links:

* [nodes.txt](https://drive.google.com/file/d/1hfhyg3o9Oi3aXcz5QBZZA3mwn_m02ZEP/view?usp=sharing): Node IDs (0 ~ 1,075,982) used to anonymize the dataset.</br>
Each line in ``nodes.txt`` is an ID for a user.

* [edges.txt](https://drive.google.com/file/d/1YLVO0mj1GPmCAxJRLVxyZnwNF8lxQZZc/view?usp=sharing): Edge list (30,026,896 edges) of the directed social graph.</br>
Each line in ``edges.txt`` is an directed edge. For example, "0 1" means user 0 is following user 1 in Medium.

* [user_data.csv](https://drive.google.com/file/d/1RKYtWKGv99zoOw1mD_TyTVxBQgkh5pWb/view?usp=sharing): Profile/activity data, [cross-site linking options](https://user.informatik.uni-goettingen.de/~ychen/Project_CrossOSN.html) and linked Twitter profile data for each user.</br>
Each row in ``user_data.csv`` is the data of a user. (Several users' data are missing due to errors in crawling process)</br>
Descriptions for each column in ``user_data.csv``:

  * ID: User's anonymized ID.
  * createdAt: Unix timestamp of the user's registration time.
  * followers: Number of followers.
  * following: Number of followings.
  * bio: 1 if the user has a biography, 0 otherwise.
  * posts: Number of posts (articles).
  * responses: Number of responses.
  * recommends: Number of recommends (this function has been replaced by the "claps" function).
  * highlights: Number of highlights.
  * facebook: The cross-site linking option to the user's Facebook account. 1 if the user has enabled it, 0 otherwise.
  * twitter: The cross-site linking option to the user's Twitter account. 1 if the user has enabled it, 0 otherwise.
  * twitter_followers: Number of followers in the user's linked Twitter account.
  * twitter_followings: Number of followings in the user's linked Twitter account.
  * twitter_bio: 1 if the user has a biography in the linked Twitter account, 0 otherwise.
  * twitter_tweets: Number of tweets in the user's linked Twitter account.
  * twitter_likes: Number of likes in the user's linked Twitter account.
  * twitter_lists: Number of lists in the user's linked Twitter account.

## BibTeX

```
@INPROCEEDINGS{Li_PerFoT18, 
author={Fei Li and Yang Chen and Rong Xie and Fehmi Ben Abdesslem and Anders Lindgren}, 
booktitle={2018 IEEE International Conference on Pervasive Computing and Communications Workshops (PerCom Workshops)}, 
title={Understanding Service Integration of Online Social Networks: A Data-Driven Study}, 
year={2018},
}
```
