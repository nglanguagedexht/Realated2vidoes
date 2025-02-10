```
$> firefox 10.10.179.25
$> burpsuite
$> hashid 8f14e45fceea167a5a36dedd4bea2543
$> hashid 6512bd43d9caa6e02c990b0a82652dca
$> python3 ~/tools/Decodify/dcode 6512bd43d9caa6e02c990b0a82652dca
$> python3 ~/tools/Decodify/dcode 45c48cce2e2d7fbdea1afc51c7c6ad26
$> echo -n "9" | md5sum
$> for i in `seq 0 100`;do echo -n "$i" | md5sum;done > hashed.txt
$> cat hashed.txt| cut -d " " -f 1
$> cat hashed.txt| cut -d " " -f 1 > hashedudated.txt
$> code hashedudated.txt
$> ffuf -request http.req -request-proto http -w hashedudated.txt
$> ffuf -request http.req -request-proto http -w hashedudated.txt -fs 632
```
