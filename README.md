**Петропавловский Андрей**  
**Клеточная линия: Hsmm**  
Контроль: (HsmmControlStdAlnRep1.bam / wgEncodeBroadHistoneHsmmControlStdAlnRep1.bam)

| Гистоновая метка | Файл         |
|------------------|--------------|
| H2az             | H2az.bam      |
| H3k27ac          | H3k27ac.bam  |
| H3k27me3         | H3k27me3.bam |
| H3K36me3         | H3k36me3.bam |
| H3K4me1          | H3k4me1.bam  |
| H3K4me2          | H3k4me2.bam  |
| H3K4me3          | H3k4me3.bam  |
| H3K79me2         | H3k79me2.bam |
| Ctcf             | Ctcf.bam     |
| Ezh239875        | Ezh239875.bam|
  
Collab: [тык](https://colab.research.google.com/drive/1QK_wtkZ4-mdD0wsDZsg7TlhymI_eGqvM?usp=sharing)  

## Картинки
![image](https://user-images.githubusercontent.com/49417479/160264119-120b72fd-a3f8-4452-ab1c-d94580c0db08.png)
![image](https://user-images.githubusercontent.com/49417479/160264135-7ded79e6-271d-45c0-a4ae-5b0952b9c533.png)  
Во всем геноме наиболее встречаемым состоянием является 2е. Можем заметить, что с терминацией транскрипции в основном связано 3 состояние, а с началом 9е. Для cpg остравков наиболее частым состоянием является 9, также как и для экзонов.  
Можно сделать вывод, что 9 тип - это промоторы
![image](https://user-images.githubusercontent.com/49417479/160264162-25231067-7ec2-4e08-b094-274e921157ad.png)
![image](https://user-images.githubusercontent.com/49417479/160264183-0528066e-fc1b-4100-9b23-8b4d4a7342fd.png)
![image](https://user-images.githubusercontent.com/49417479/160264196-228ee080-1b0b-49d2-a853-1d2202d861c1.png)

## Эпигенетические типы
| #  | название                  | описание                                                           |
|----|---------------------------|--------------------------------------------------------------------|
| 1  | Repressed heterochromatin | Ассоциируется с Lamina                                             |
| 2  | Repressed heterochromatin | Ассоциируется с % genome и Lamina                                  |
| 3  | Exon                      | Активность в H3k36me3, совпадает с экзоном, геном и TES            |
| 4  | Transcribed gene          | Попадает на метки H3k79me2 и H3k36me3, совпадает с активным геном  |
| 5  | Transcribed gene          | Попадает на H3k79me2                                               |
| 6  | Weak enchancer            | Ассоциируется с TES и попадает на попадает на H3k4me1              |
| 7  | Enchancer                 | Активен на H3k4me1, H3k4me2,H3k27ac, H2az                          |
| 8  | Weak Enchancer            | Активен на H3k4me1, H3k4me2 и H2az                                 |
| 9  | Promoter                  | Активен на метках, которые вроде связаны с промоторами             |
| 10 | Transcriptional factor    | Ассоциируется Ctcf и с Lamina                                      |

![image](https://user-images.githubusercontent.com/49417479/160305858-fc7f67d2-7dc3-437a-9e45-50710b7cc302.png)

