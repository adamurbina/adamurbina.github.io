---
layout: post
title:      "My Favorite Array Method"
date:       2018-08-31 16:50:12 +0000
permalink:  my_favorite_array_method
---


It’s surprising how many methods are baked into Ruby arrays. I think one of my favorite little tricks is “subtracting” one array from another, or that’s at least how I think about it. For instance you can do [“a”, “b”, “c”] - [“b”, “d”, “e”] => [“a”, “c”] since “b” is common to both arrays and is sort of “subtracted” from the original array. Whenever I see something like this, I can just tell that one day it will be useful. If you take the second array [“b”, “d”, “e”] and apply the uniq method (in case there are duplicates) and then subtract it from the first array, and then add them together you get an array of unique elements in two arrays. 
