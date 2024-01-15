# Plant-pathway-annotations
（整理的不同植物的GO和KEGG注释）

# 注释与整理流程
## KEGG注释:使用KEGG官方三种注释工具（ "https://www.genome.jp/tools/kofamkoala/ "）进行注释，然后整理删除重复。然后从“https://www.genome.jp/kegg-bin/get_htext?ko00001.keg”获取KO以及pathway信息。并进行合并。
## GO注释

# 结果文件结构
## annotations --- 所有注释结果存放文件夹
### (spacename)_(release）--- 某物种某版本的注释结果存放文件夹
## 以下是KEGG注释结果
#### (spacename)_(release)_KofamKOALA.txt --- 某物种某版本的KofamKOALA注释结果
#### (spacename)_(release)_BLASTKOALA.txt --- 某物种某版本的BLASTKOALA注释结果
#### (spacename)_(release)_GhostKOALA.txt --- 某物种某版本的GhostKOALA注释结果
#### (spacename)_(release)_CDS_KEGG.txt --- 某物种某版本的转录本的KO注释结果
#### (spacename)_(release)_GENE_KEGG.txt --- 某物种某版本的基因的KO注释结果

