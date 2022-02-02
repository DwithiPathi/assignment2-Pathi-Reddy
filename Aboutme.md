# Dwithi Reddy Pathi Reddy
dwithi is completely down to earth and sweet and kind.She is usually very sweet person and protective when it comes to her friends.Out of anyone any guy would be lucky to be with her or even have her as a best friend.You'll fall in love as soon as you meet.She'll leave you coming back for more;wanted by many.can't be wholly defined in few words because she's so close to perfection that any words for her just won't be good enough.
This is the diagram of Ranveer Singh drawn by Dwithi ![Ranveer Sigh pencil sketch](C:\Users\s546908\Desktop\webapps-repos\assignment2-Pathi-Reddy)
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
Data available in/via computers are often of enormous size, and thus, it is significantly important and necessary to invent timeand space-efficient methods to process them. Most of such data are, in fact, stored and manipulated as strings. String matching is most fundamental in string processing, where the problem is to examine whether or not a pattern string p occurs in a text string w. There are two cases to consider; p is fixed and w is flexible, and vise versa
Refer this link for more detail study[StringProcessing](https://www.semanticscholar.org/paper/String-Processing-Algorithms-%E7%A8%B2%E6%B0%B8-Inenaga/aa555b049626f76b43b31550102a0923c4fc88a7)
~~~
    {
        long long compute_hash(string const& s) {
    const int p = 31;
    const int m = 1e9 + 9;
    long long hash_value = 0;
    long long p_pow = 1;
    for (char c : s) {
        hash_value = (hash_value + (c - 'a' + 1) * p_pow) % m;
        p_pow = (p_pow * p) % m;
    }
    return hash_value;
}

    }
~~~
Refer this link for more detail study[code](https://cp-algorithms.com/string/string-hashing.html)