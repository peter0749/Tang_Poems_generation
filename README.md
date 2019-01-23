# Tang_Poems_generation
唐詩煉成 使用 WGAN-div

### samples

#### samples 1:

不限制格律

batch size=64, 13000 次迭代:

一行為獨立一首五言絕句

```
春女書自邊，今塵入作去。寒獨不客語，我時朝鐵飛。
本池人言語，惟事獨雲人。上何大言東，路出見月池。
一風雙何草，深江但獨知。塵我時行人，年我頼歲此。
自死仁不敬，香書向草石。山過月花千，在木自古中。
大玉水高池，但時照書聲。一死紅限子，爲日上清人。
大年後問江，新亭中第世。莫來春草識，有轉早亦飛。
出年如願雲，得然遠月書。已人時池物，頼已大氣是。
一聞公早落，池月得無去。花香人色上，無欲遠東石。
```

#### samples 1:

限制格律（平仄）

batch size=64, 13000 次迭代:

兩行為獨立一首五言絕句

詩的下一行是它對應的平仄

```
月石天如主，如風可不香。今知無可月，誰月可無來。
仄仄平平仄，平平仄仄平。平平平仄仄，仄仄仄平平。
月子月如人，如風可無可。不可月如人，如頭可月可。
仄仄仄平平，平平仄平仄。仄仄仄平平，平平仄平仄。
不石無可主，如風可不來。不須無可月，無不可人人。
仄仄平平仄，平平仄仄平。仄平平仄仄，平仄仄平平。
月子千可主，如頭一不香。不然無可事，不月可無人。
仄仄平平仄，平平仄仄平。平平平仄仄，仄仄仄平平。
不可人可時，白月可風可。不可天來頭，可月問無可。
仄仄平仄平，仄仄仄平仄。仄仄平平平，仄仄仄平仄。
九如不可時，可月如頭可。月可月如頭，可月如無可。
平平仄仄平，仄仄平平仄。仄仄仄平平，仄仄平平仄。
月石無如主，如風一不身。不須無可事，誰月可無人。
仄仄平平仄，平平仄仄平。仄平平仄仄，平仄仄平平。
無石無可主，如頭可不香。不知無可月，不月正無如。
平仄平平仄，平平仄仄平。平平平仄仄，仄仄仄平平。
```
