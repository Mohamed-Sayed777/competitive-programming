# Map & Set


### Notes:
 - When erasing a number X in multiset, it will DELET All elements that have value equal to X, for example: `set.erase(X)`
 
 - You can only erase one element by find the iterator of an element that have value X : `Set.erase(Set.find(X))`. 
 
 - In some problems, you might get time limit by using Unordered_map, read this blog for more Info : [Unordered_map vs map, which one should I use when? - Codeforces]
 (https://codeforces.com/blog/entry/104332)  
 - Instead of Using `set<int> :: iterator it = set.begin()`, you can use `auto it = s.begin()` 
 
 - Using `lower_bound(Set.begin(), Set.end(), Value)` might time limit, instead you can use `Set.lower_bound(Value)`, read comments of this blog for more Info : [STL set vs map time complexity - Codeforces](https://codeforces.com/blog/entry/22074)
 
 - Session Code : [ Ideone.com](https://ideone.com/14nswp)
 
### Resources:

###### Blogs
 - [(Optional) Introduction to Sets & Maps · USACO Guide](https://usaco.guide/bronze/intro-sets?lang=cpp)
 -  https://medium.com/curio/runtime-analysis-sets-vs-maps-vs-sorting-cffc3d10d0d7
 -  https://www.geeksforgeeks.org/set-vs-map-c-stl/
###### Videos
- Adel Naseem Playlist - https://www.youtube.com/watchv=4hhz69S15wU&list=PLCInYL3l2AainAE4Xq2kdNGDfG0bys2xp
-  Map : https://youtu.be/PqyEHjApE-c?si=MpOsGhNL6xX1Z1hG
-  Set : https://youtu.be/czZ4F0R0ZTI?si=nOO4OwvYaF4LE27W
-  Compare function : https://youtu.be/_9Rrq0q51BQ?si=SP7fByOmz-96ejU3
###### Sheet
- 
###### Problems
- [Problem - A - Codeforces](https://codeforces.com/contest/2/problem/A) // challenging
- [CSES - Sum of Two Values](https://cses.fi/problemset/task/1640)
- [Problem - 1703B - Codeforces](https://codeforces.com/problemset/problem/1703/B)
- [Problem - A - Codeforces](https://codeforces.com/group/cH1gNFjW0S/contest/345146/problem/A)
- [Problem - E - Codeforces](https://codeforces.com/group/cH1gNFjW0S/contest/345146/problem/E)
