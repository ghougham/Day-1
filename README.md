biofam)
(head(biofam))
data(biofam)

biofam.seq <-seqdef(biofam[,10:25])
seqIplot(biofam.seq, sortv = "from.end")
seqIplot(biofam.seq,)
seqfplot(biofam.seq,)
seqdplot(biofam.seq,)
print(biofam.seq[1:2,],)
print(biofam.seq[1:2,], format="SPS")


> 
> help(biofam)
> (head(biofam))
     idhous   sex birthyr    nat_1_02 plingu02                        p02r01
1167  66891   man    1943 Switzerland   german Protestant or Reformed Church
514   28621   man    1935 Switzerland   german                Roman Catholic
1013  57711 woman    1946 Switzerland   french   no denomination or religion
275   17501   man    1918 Switzerland   german                Roman Catholic
2580 147701   man    1946 Switzerland   german                Roman Catholic
773   44171   man    1927 Switzerland  italian                Roman Catholic
                                       p02r04                                    cspfaj
1167 religious celebrations and family events                       other self-employed
514                               once a week                       other self-employed
1013               only for family ceremonies                       other self-employed
275                               once a week                            top management
2580               only for family ceremonies                                      <NA>
773                                     never unqualified non-manual and manual workers
                       cspmoj a15 a16 a17 a18 a19 a20 a21 a22 a23 a24 a25 a26 a27 a28 a29 a30  wp00tbgp
1167      other self-employed   0   0   0   0   0   0   0   0   0   3   6   6   6   6   6   6 1053.3687
514                      <NA>   0   1   1   1   1   1   1   1   1   1   1   3   6   6   6   6  855.4339
1013 intermediate professions   0   0   0   0   0   0   0   1   1   1   1   1   3   6   6   6  575.2052
275                      <NA>   0   0   0   0   0   1   1   1   1   1   1   1   1   1   1   1 1527.3920
2580                     <NA>   0   0   0   0   0   1   1   1   1   1   1   1   1   6   6   6  796.1827
773                      <NA>   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0 1072.4348
      wp00tbgs
1167 0.9348480
514  0.7591841
1013 0.5104855
275  1.3555362
2580 0.7065995
773  0.9517689
> data(biofam)
> 
> biofam.seq <-seqdef(biofam[,10:25])
 [>] 8 distinct states appear in the data: 
     1 = 0
     2 = 1
     3 = 2
     4 = 3
     5 = 4
     6 = 5
     7 = 6
     8 = 7
 [>] state coding:
       [alphabet]  [label]  [long label] 
     1  0           0        0
     2  1           1        1
     3  2           2        2
     4  3           3        3
     5  4           4        4
     6  5           5        5
     7  6           6        6
     8  7           7        7
 [>] 2000 sequences in the data set
 [>] min/max sequence length: 16/16
> seqIplot(biofam.seq, sortv = "from.end")
> seqIplot(biofam.seq,)
> seqfplot(biofam.seq,)
> seqdplot(biofam.seq,)
> print(biofam.seq[1:2,],)
     Sequence                       
1167 0-0-0-0-0-0-0-0-0-3-6-6-6-6-6-6
514  0-1-1-1-1-1-1-1-1-1-1-3-6-6-6-6
> print(biofam.seq[1:2,], format="SPS")
    Sequence                
[1] (0,9)-(3,1)-(6,6)       
[2] (0,1)-(1,10)-(3,1)-(6,4)

> 
> help(biofam)
> (head(biofam))
     idhous   sex birthyr    nat_1_02 plingu02                        p02r01
1167  66891   man    1943 Switzerland   german Protestant or Reformed Church
514   28621   man    1935 Switzerland   german                Roman Catholic
1013  57711 woman    1946 Switzerland   french   no denomination or religion
275   17501   man    1918 Switzerland   german                Roman Catholic
2580 147701   man    1946 Switzerland   german                Roman Catholic
773   44171   man    1927 Switzerland  italian                Roman Catholic
                                       p02r04                                    cspfaj
1167 religious celebrations and family events                       other self-employed
514                               once a week                       other self-employed
1013               only for family ceremonies                       other self-employed
275                               once a week                            top management
2580               only for family ceremonies                                      <NA>
773                                     never unqualified non-manual and manual workers
                       cspmoj a15 a16 a17 a18 a19 a20 a21 a22 a23 a24 a25 a26 a27 a28 a29 a30  wp00tbgp
1167      other self-employed   0   0   0   0   0   0   0   0   0   3   6   6   6   6   6   6 1053.3687
514                      <NA>   0   1   1   1   1   1   1   1   1   1   1   3   6   6   6   6  855.4339
1013 intermediate professions   0   0   0   0   0   0   0   1   1   1   1   1   3   6   6   6  575.2052
275                      <NA>   0   0   0   0   0   1   1   1   1   1   1   1   1   1   1   1 1527.3920
2580                     <NA>   0   0   0   0   0   1   1   1   1   1   1   1   1   6   6   6  796.1827
773                      <NA>   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0   0 1072.4348
      wp00tbgs
1167 0.9348480
514  0.7591841
1013 0.5104855
275  1.3555362
2580 0.7065995
773  0.9517689
> data(biofam)
> 
> biofam.seq <-seqdef(biofam[,10:25])
 [>] 8 distinct states appear in the data: 
     1 = 0
     2 = 1
     3 = 2
     4 = 3
     5 = 4
     6 = 5
     7 = 6
     8 = 7
 [>] state coding:
       [alphabet]  [label]  [long label] 
     1  0           0        0
     2  1           1        1
     3  2           2        2
     4  3           3        3
     5  4           4        4
     6  5           5        5
     7  6           6        6
     8  7           7        7
 [>] 2000 sequences in the data set
 [>] min/max sequence length: 16/16
> seqIplot(biofam.seq, sortv = "from.end")
> seqIplot(biofam.seq,)
> seqfplot(biofam.seq,)
> seqdplot(biofam.seq,)
> print(biofam.seq[1:2,],)
     Sequence                       
1167 0-0-0-0-0-0-0-0-0-3-6-6-6-6-6-6
514  0-1-1-1-1-1-1-1-1-1-1-3-6-6-6-6
> print(biofam.seq[1:2,], format="SPS")
    Sequence                
[1] (0,9)-(3,1)-(6,6)       
[2] (0,1)-(1,10)-(3,1)-(6,4)


