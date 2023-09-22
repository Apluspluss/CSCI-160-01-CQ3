Runtime analysis for Mini-Max:

The program has two separate loops which both have constant time work within them. Thus, they are O(n) each. The sorting algorithm is unknown, so I cannot determine its compleity. 
Disregarding this the time complexity 2n = O(n).

Rationale for Hackerrank in String for partical credit:

I added a parameter for the hackerrank string (hr). As my base case, I had if the hackerrank string was empty, return "YES. Then if it wasn't empty, I did if (!s.contains(hr.charAt(0))) return "NO". Else return hr.substing(1, hr.length()-1. I ran into an incompatible types error during the (!s.contains(hr.charAt(0))) portion which I don't understand. I believe the theory behind this should work aside from the multiple letters issue.

