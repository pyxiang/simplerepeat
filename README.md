## Simplerepeat Sequence Annotation Tool for Sniffles  
A simple simplerepeat sequence annotation tool for sniffles SV result.
### Usage
>python3 simplerepeat_anno.py `<`vcf`>` `<`outfile`>` `<`bp`>` `<`dataset`>`  

>usage:simplerepeat_anno.py [options]  

>simplerepeat sequence annotation for sniffles vcf


>optional arguments:   
> `<`vcf`>`         &nbsp;sniffles vcf file  
> `<`outfile`>`     &nbsp;output filename including path  
> `<`bp`>`          &nbsp;set the range of sequence  
> `<`dataset`>`     &nbsp;the segmentduplication sequence that you refer

### Work Flow

1. Input the sniffles SV result and range of the chrmosome position 

2. If the range of the chromosome of sniffles result is overlapped by dataset, the result will be annotated   

3. Output the annotated result 


### Reference Dataset  
dataset was downloaded form [http://hgdownload.soe.ucsc.edu/goldenPath/hg19/database/gap.txt.gz](http://hgdownload.soe.ucsc.edu/goldenPath/hg19/database/simpleRepeat.txt.gz)




