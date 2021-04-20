# MST-Medical-Data-Clustering

--
ABSTRACT

The rapid advance of biotechnology studies and as probably the most explosively expanding tool for genome analysis, microchips of gene expression have made it possible 
to simultaneously monitor the expression levels of tens of thousands of genes under diﬀerent experimental conditions. Analyzing the gene data, which is produced 
by gene expression profiling, offers potential insight into cellular functions of genes. 
One of the first steps in gene expression analysis is the detection of groups of genes that show similar expression patterns and are activated by similar agents. 
This is a algorithmic problem is known as clustering multi-conditional gene expression data.
A new strategy, which uses the minimum spanning tree (MST) representation of gene expression data, 
is suggested as an alternative to classical clustering algorithms (Hierarchical, K-Means, or SOMs). 
In this paper, we present a comparative study and performance evaluation for the new MST based clustering algorithms. We compare three different algorithms 
(Single linkage, Hierarchical, and Global Optimal) on EXCAVATOR framework by using microarray gene expression data of Saccharomyces cerevisiae and 
different similarity metrics (Euclidean and Pearson correlation).

Keywords: Clustering, microarray gene expression, minimum spanning tree.

ÖZET

Biyoteknoloji çalışmalarının hızlı ilerlemesi ve muhtemelen genom analizi için en patlayıcı şekilde genişleyen araç olan gen ifadesinin mikroçipleri, 
farklı deneysel koşullar altında on binlerce genin ifadesi seviyelerinin aynı anda izlenmesini mümkün kılmıştır. Gen ifadesi profili ile üretilen gen verilerinin analizi, 
genlerin hücresel fonksiyonlarına potansiyel bir bakış sağlar. Gen ifadesi analizindeki ilk adımlardan biri, benzer ifade benzerliği gösteren ve 
benzer ajanlar tarafından aktive edilen gen gruplarının saptanmasıdır. Bu çok koşullu gen ifadesi verilerinin kümelenmesi olarak bilinen algoritmik bir sorundur.

Gen ifade verilerini asgari tarama ağaçları (ATA) şeklinde gösterimlenmesini benimseyen yeni bir strateji, 
klasik kümeleme algoritmalarına (Hierarchical, K-means veya SOMs gibi) alternatif olarak önerilmiştir. 
Bu makalede, ATA esaslı kümeleme algoritmaları için karşılaştırmalı performans değerlendirmeleri sunulmaktadır. 
Saccharomyces cerevisiae türüne ait mikro-dizi gen ifade verisi ve farklı gen benzerlik ölçütleri (Pearson korelasyonu ve Euclidean uzaklığı gibi) kullanılmıştır. 
EXCAVATOR yardımıyla, üç farklı ATA kümeleme algoritması (Single-linkage, Hierarchical, ve Global Optimal) kıyaslanmıştır.

Anahtar kelimeler: Kümeleme, mikro-dizi gen ifadesi, asgari tarama ağaçları


CONCLUSIONS

Although all of the three algorithms adopts similar MST-based clustering approaches, the variation in edge-cutting strategy causes a significant difference in their 
performance on clustering gene expression data. Additionally, each algorithm generates different values of total distance for the constructed MST. 
As it is expected by definition, single-linkage and hierarchical algorithms are much faster than global optimal algorithm while global optimal algorithm is perfectly 
accurate in the most cases. As it is suggested in the previous studies, Pearson correlation performs better as a gene similarity metric in comparison to Euclidean distance.

Based on our study, hierarchical MST is a preferable algorithm with its very fast execution (1 sec) and perfect accuracy (100%) on clustering with 
pre-defined number of clusters. When the number of clusters is undefined, although global optimal MST provides 10% boost in accuracy, it is 10 times slower
than Hierarchical algorithm. In any conditions, with 45% of maximum accuracy, single linkage algorithm seems to be inapplicable on microarray 
gene expression data clustering. As a conclusion, in spite of the fact that MST-based clustering is promising for gene expression analysis; 
its performance is highly dependent on data and edge-cutting strategy.

