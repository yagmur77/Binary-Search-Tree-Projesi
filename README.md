# Binary-Search-Tree-Projesi
ŞABLONU DAHA NET GÖREBİLMEK İÇİN KOD KISMINDAN METNİ OKUMANIZI TAVSİYE EDERİM.
*[7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.

Örnek: root x'dir. root'un sağından y bulunur. Solunda z bulunur vb.

1) Öncelikle rootu belirleyelim. İlk eleman olan 7 root olur.
2) İkinci eleman 5, 7den küçük olduğu için sol alt ağaca eklenir.
                 7
                /
               5   
3) Üçüncü eleman olan 1 ise hem 5ten hem 7den küçük olduğu için 5in sol alt ağacına eklenir.
                 7
                /
               5   
              /
             1
4) Dördüncü elemanımız 8, 7den büyük olduğu için sağ alt ağaca eklenir.
                 7
                / \
               5   8
              /
             1
5) Beşinci eleman 3, 1den büyük 5ten küçük olduğu için 1in sağ alt ağacına gelir.
                 7
                / \
               5   8
              /
             1
              \
               3
6) Altıncı eleman olan 6, 5ten büyük 7den küçük olduğu için 5in sağ alt ağacına gelir.
                 7
                / \
               5   8
              / \
             1   6
              \
               3
7) Yedinci eleman olan 0, 1den küçük olduğu için 1in sol alt ağacına eklenir.
                 7
                / \
               5   8
              / \
             1   6
            / \
           0   3
8) Sekizinci eleman 9 ise 8den büyük olduğu için sağ alt ağacına gelir.
                 7
                / \
               5   8
              / \    \
             1   6     9
            / \
           0   3
9) Dokuzuncu eleman 4 ise 3ten büyük olduğu için sağ alt ağaca gelir.
                 7
                / \
               5   8
              / \    \
             1   6     9
            / \
           0   3
                \
                 4
10) Onuncu eleman 2 ise 3ten küçük 1den büyük olduğu için 3ün sol alt ağacına eklenir.
                 7
                / \
               5   8
              / \    \
             1   6     9
            / \
           0   3
              /  \
             2    4
