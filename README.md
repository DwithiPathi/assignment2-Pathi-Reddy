# Dwithi Reddy Pathi Reddy
## McDonald's
It is called as fast food restaurant.Good **ambience** ,delicious food and have nice drink menu.Restaurant is maintained very clean with all the safety procedures,**clean bathrooms** and good space to sprawl.
-----------------------
# Directions from Airport to McDonald's
1. Kansas International Airport
2. Address : 150 NW Barry Rd, Kansas City, MO 64155
3. Directions:
    1. Head south on N College Dr toward Centennial Dr
    2. Continue onto University Dr
    3. Turn left onto US-59 N/US-71 BUS N,continue straight
    4. Turn right after McDonald's destination will be on the left.
* Menu
    * Chicken
    * Sandwiches
* Fries

go to the next file [page](Aboutme.md)local to the repo.

-----
# Sports and Recreation
|Name of the sport|Location|Amount to be paid|
|---|---|---:|
|Shuttle|Missouri|$15|
|Base Ball|Maryville|$25|
|Basket Ball|kansas|$10|
|Cricket|Illinios|$15|
------
# Quotes
> Your smile makes me smile -*Atticus*<br>
> Laugh louder, smile binger, love longer - *William Shakespeare*
------
# Code Fencing
Data available via computers are often of enormous size,and thus,it is significantly important and necessary to invent time & space-efficient methods to process them.Most of such data are,in fact,stored and manipulated as strings.String matching is most fundamental in string processing.<br>
Refer this link for more detail study<https://www.semanticscholar.org/paper/String-Processing-Algorithms-%E7%A8%B2%E6%B0%B8-Inenaga/aa555b049626f76b43b31550102a0923c4fc88a7>
~~~
    {
        long long compute_hash(string const& s) {
    const int p = 31;
    const int m = 1e9 + 9;
    long long hash_value = 0;
    long long p_pow = 1;
    for (char c : s) {
        hash_value = (hash_value + (c - 'a' + 1) * p_pow) % m;
        p_pow = (p_pow * p) % m;}
    return hash_value;
}
}
~~~
Refer this link for more detail study<https://cp-algorithms.com/string/string-hashing.html>
