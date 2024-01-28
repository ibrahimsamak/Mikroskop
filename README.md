Verilen görüntüye öncelikli olarak keskinleştirme işlemi uygulayın
Elde edilen görüntüye en uygun eşikleme yöntemini uygulayarak ikili görüntüye dönüştürün.
Çıktı çok sayıda bileşen içeriyorsa, bileşen sayısını azaltmak için morfolojik bir teknik uygulayın, (örneğin bileşen boyutuna göre filtreleme veya erozyon)
Verilen görüntülere Bağlantı bileşen etiketleme (connected component labeling) algoritması uygulayın 
Algılanan bileşenleri/nesneleri farklı renklerle görüntüleyerek sonuçlarınızı gösterin
İlgili her bölge/nesne için alanı, yönü ve daireselliği (Area,orientation, circularity) hesaplayın. 
1: Label = 32
1: Directioin = -1.5065612916306559
1: Circularity = 0.39269908169872414
2: Label = 85
2: Directioin = -0.6577201364502975
2: Circularity = 0.1478396542865785
3: Label = 32
3: Directioin = -1.2005244553568475
3: Circularity = 0.39269908169872414
4: Label = 24
4: Directioin = 1.044818221747218
4: Circularity = 0.5235987755982988
5: Label = 82
5: Directioin = 0.47275615521397696
5: Circularity = 0.15324842212633136
6: Label = 16
6: Directioin = -0.7853981633974483
6: Circularity = 0.7853981633974483
7: Label = 40
7: Directioin = 1.1149434956373614
7: Circularity = 0.3141592653589793
8: Label = 40
8: Directioin = 1.2623747599409971
8: Circularity = 0.3141592653589793
9: Label = 16
9: Directioin = -0.7853981633974483
9: Circularity = 0.7853981633974483
10: Label = 21
10: Directioin = 1.2214664144278067
10: Circularity = 0.5983986006837702
11: Label = 47
11: Directioin = 0.8755525561231426
11: Circularity = 0.26736958753955686
12: Label = 20
12: Directioin = -0.7853981634113874
12: Circularity = 0.6283185307179586
13: Label = 90
13: Directioin = 0.08217803279021883
13: Circularity = 0.13962634015954636
14: Label = 59
14: Directioin = -0.3310082883997613
14: Circularity = 0.21298933244676563
15: Label = 66
15: Directioin = 1.5642664906158594
15: Circularity = 0.19039955476301776
16: Label = 108
16: Directioin = 0.1623972052711125
16: Circularity = 0.11635528346628862
17: Label = 94
17: Directioin = 0.15064611020551946
17: Circularity = 0.13368479376977843
18: Label = 74
18: Directioin = 0.3531303050385011
18: Circularity = 0.16981581911296179
19: Label = 86
19: Directioin = 0.1737726684346074
19: Circularity = 0.14612058853906015
20: Label = 49
20: Directioin = -0.6926633628386646
20: Circularity = 0.2564565431501872
21: Label = 62
21: Directioin = 1.1611565385801326
21: Circularity = 0.2026833970057931


Her bölgenin sınır piksellerini tanımlayın (edge detection) ve alanın çevreye oranını, kompaktlığı (compactness, the ratio of the area to the perimeter) hesaplayın
1: Label = 32
1: ARC = 67.21320307254791
1: Compact = 0.08901243007127879
2: Label = 85
2: ARC = 176.4680358171463
2: Compact = 0.03430020266889435
3: Label = 32
3: ARC = 34.72792184352875
3: Compact = 0.33342814131739945
4: Label = 24
4: ARC = 26.485281229019165
4: Compact = 0.42994403522022967
5: Label = 82
5: ARC = 91.35533821582794
5: Compact = 0.12346841039485212
6: Label = 16
6: ARC = 17.656854152679443
6: Compact = 0.6449160528303446
7: Label = 40
7: ARC = 43.55634891986847
7: Compact = 0.2649518272487941
8: Label = 40
8: ARC = 43.55634891986847
8: Compact = 0.2649518272487941
9: Label = 16
9: ARC = 17.656854152679443
9: Compact = 0.6449160528303446
10: Label = 21
10: ARC = 23.071067690849304
10: Compact = 0.49578544395653823
11: Label = 47
11: ARC = 50.38477599620819
11: Compact = 0.23265321468953798
12: Label = 20
12: ARC = 21.656854152679443
12: Compact = 0.5358572563049142
13: Label = 90
13: ARC = 187.82337403297424
13: Compact = 0.03205923077129443
14: Label = 59
14: ARC = 64.28427052497864
14: Compact = 0.17941239164324344
15: Label = 66
15: ARC = 72.04163002967834
15: Compact = 0.15980366602675744
16: Label = 108
16: ARC = 231.09545266628265
16: Compact = 0.025412700601122988
17: Label = 94
17: ARC = 100.42640602588654
17: Compact = 0.11712291587952799
18: Label = 74
18: ARC = 162.6101714372635
18: Compact = 0.03516787834321346
19: Label = 86
19: ARC = 91.01219248771667
19: Compact = 0.13046954923743387


Öğrenilen bilgiler ile yeni fikirler üretmeye araştırmaya ve tartışmaya olanak sağlayan esnek ve serbest final projeleri için teşekkürlerimi sunarım.

