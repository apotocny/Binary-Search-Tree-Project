# Binary-Search-Tree-Project

[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

------------------------------------------------------------------------------------------------------------------------------------------------------
Cevap : [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] ----------> Root 5 kabul edersek;

                      5 (S1)                        -----> STEP 1  : Root 5 olarak kabul edip dizimizi yerleştirelim.
                  /           \                     -----> STEP 2  : 7, 5'den büyük olduğu için sağ tarafa yazarız.
                 /             \                    -----> STEP 3  : 2, 5'den küçük olduğu için sol tarafa yazarız.
               2 (S3)            7 (S2)             -----> STEP 4  : 6, 7'den küçük olduğu için sol tarafa yazarız.
              /    \             /   \              -----> STEP 5  : 9, 7'den büyük olduğu için sağ tarafa yazarız.
             /      \           /     \             -----> STEP 6  : 0, 2'den küçük olduğu için sol tarafa yazarız.
            0 (S6)   4 (S7)   6 (S4)   9 (S5)       -----> STEP 7  : 4, 2'den büyük olduğu için sağ tarafa yazarız.
             \      /           \     /             -----> STEP 8  : 8, 6'dan büyük olduğu için sağ tarafa, 9'dan küçük olduğu için sol tarafa yazarız.
              \    /             \   /              -----> STEP 9  : 3, 0'dan büyük olduğu için sağ tarafa, 4'den küçük olduğu için sol tarafa yazarız.
                3 (S9)             8 (S8)           -----> STEP 10 : 1, 3'den küçük olduğu için sol tarafa yazarız.
                /                                   
               /                                    
              1 (S10)                               
