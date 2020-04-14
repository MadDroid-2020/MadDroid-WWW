# MadDroid: Characterizing and Detecting Devious Ad Contents for Android Apps

## dataset.csv ##
This file contains information of the dataset we used in our experiment, which is comprised of 40K adwares.
The construction of this dataset resorts to AndroZoo dataset.(https://androzoo.uni.lu)  
The metadata of these apps is contained in the latest list maintained by Androzoo.(https://androzoo.uni.lu/lists)

## map-lib-host.csv ##

This file contains the output mappings between ad libraries and ad hosts in our runtime hooking approach.  
To the best of our knowledge, many of the domains here cannot be found in any ad domain lists.  
Note that this list does not contain all the ad hosts in the Android ecosystem, just the ones appeared in our experiments, since it's iterlatively extracted during the dynamic testing of apps in our dataset. The timeliness of mobile ad hosts should also be considered. Our experiments were performed no later than Sept.2019.  
Therefore, we recommend this list should only be used as a complementary list to other ad host lists.
