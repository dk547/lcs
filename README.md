lcs
===

Find the longest common substring in the set of strings

Program is using suffix arrays and the long common prefix algorithms:
 Simple Linear Work Suﬃx Array Construction by Juha K¨arkk¨ainen and Peter Sanders
 (http://www.cs.helsinki.fi/u/tpkarkka/publications/icalp03.pdf)
 Linear-Time Longest-Common-Prefix Computation in Suﬃxx Arrays by Toru Kasai and others
 (http://www.cs.iastate.edu/~cs548/references/linear_lcp.pdf)

use:
 $ echo -e "3\nabacaba\nmycabarchive\nacabistrue" | ./lcs
 cab

@author Vasily Bespalov
git https://github.com/dk547/lcs
