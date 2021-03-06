# [Totient maximum](http://projecteuler.net/problem=69)

Euler's Totient function, φ(_n_) [sometimes called the phi function], is used to determine the number of numbers less than _n_ which are relatively prime to _n_. For example, as 1, 2, 4, 5, 7, and 8, are all less than nine and relatively prime to nine, φ(9)=6.

| **_n_** | **Relatively Prime** | **φ(_n_)** | **_n_/φ(_n_)** |
| 2 | 1 | 1 | 2 |
| 3 | 1,2 | 2 | 1.5 |
| 4 | 1,3 | 2 | 2 |
| 5 | 1,2,3,4 | 4 | 1.25 |
| 6 | 1,5 | 2 | 3 |
| 7 | 1,2,3,4,5,6 | 6 | 1.1666... |
| 8 | 1,3,5,7 | 4 | 2 |
| 9 | 1,2,4,5,7,8 | 6 | 1.5 |
| 10 | 1,3,7,9 | 4 | 2.5 |

It can be seen that _n_=6 produces a maximum _n_/φ(_n_) for _n_ ![≤](/Volumes/HDD_KS/source/project_euler/vender/bundle/ruby/2.2.0/gems/euler-manager-0.1.1/config/../data/images/symbol_le.gif) 10.

Find the value of _n_ ![≤](/Volumes/HDD_KS/source/project_euler/vender/bundle/ruby/2.2.0/gems/euler-manager-0.1.1/config/../data/images/symbol_le.gif) 1,000,000 for which _n_/φ(_n_) is a maximum.

