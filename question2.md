# student 2's answer to question 2

**Q2** Assign variables to the individual component of you favourite gene (e.g prometer, 5'UTR, start codon, exon1, intron ,exon2 , stop codon ,3'UTR). print the entire gene by using the string concatenation operator on the standart output! Note: feel free to create a fictional gene sequence by randomly filling in the components.

```
promoter = "ATTGGGCCTTTTGGGAAAACCTTTTTAAGGAGA"
5_prime_UTR = "GGTTTTAAAGGGATTTTAACC"
start_codon = "ATG"
exon1 = "GGGCCCCTTTAAAAGGCTTCTCT"
intron = "TTTTGGGGGAAACCGTGTGAAAAA"
exon2 = "AAATTGGGGCCCTGTGAAAACCCCCC"
stop_codon = "TAG"
3_prime_UTR = "GGGAAACCTTTTTAAAGCTCTCTCTC"

my_fav_gene = promoter + 5_prime_UTR + start_codon + exon1 + \
              intron + exon2 + stop_codon + 3_prime_UTR
              
print("my favourite gene sequence is as follows:")
print(my_fav_gene)
```
