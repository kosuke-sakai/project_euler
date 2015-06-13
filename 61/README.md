# [Cyclical figurate numbers](http://projecteuler.net/problem=61)

Triangle, square, pentagonal, hexagonal, heptagonal, and octagonal numbers are all figurate (polygonal) numbers and are generated by the following formulae:

| Triangle |   | P<sub>3,<i>n</i></sub>=_n_(_n_+1)/2 |   | 1, 3, 6, 10, 15, ... |
| Square |   | P<sub>4,<i>n</i></sub>=_n_<sup>2</sup> |   | 1, 4, 9, 16, 25, ... |
| Pentagonal |   | P<sub>5,<i>n</i></sub>=_n_(3_n_ ![−](/Volumes/HDD_KS/source/project_euler/vender/bundle/ruby/2.2.0/gems/euler-manager-0.1.1/config/../data/images/symbol_minus.gif)1)/2 |   | 1, 5, 12, 22, 35, ... |
| Hexagonal |   | P<sub>6,<i>n</i></sub>=_n_(2_n_ ![−](/Volumes/HDD_KS/source/project_euler/vender/bundle/ruby/2.2.0/gems/euler-manager-0.1.1/config/../data/images/symbol_minus.gif)1) |   | 1, 6, 15, 28, 45, ... |
| Heptagonal |   | P<sub>7,<i>n</i></sub>=_n_(5_n_ ![−](/Volumes/HDD_KS/source/project_euler/vender/bundle/ruby/2.2.0/gems/euler-manager-0.1.1/config/../data/images/symbol_minus.gif)3)/2 |   | 1, 7, 18, 34, 55, ... |
| Octagonal |   | P<sub>8,<i>n</i></sub>=_n_(3_n_ ![−](/Volumes/HDD_KS/source/project_euler/vender/bundle/ruby/2.2.0/gems/euler-manager-0.1.1/config/../data/images/symbol_minus.gif)2) |   | 1, 8, 21, 40, 65, ... |

The ordered set of three 4-digit numbers: 8128, 2882, 8281, has three interesting properties.

1. The set is cyclic, in that the last two digits of each number is the first two digits of the next number (including the last number with the first).
2. Each polygonal type: triangle (P<sub>3,127</sub>=8128), square (P<sub>4,91</sub>=8281), and pentagonal (P<sub>5,44</sub>=2882), is represented by a different number in the set.
3. This is the only set of 4-digit numbers with this property.

Find the sum of the only ordered set of six cyclic 4-digit numbers for which each polygonal type: triangle, square, pentagonal, hexagonal, heptagonal, and octagonal, is represented by a different number in the set.
