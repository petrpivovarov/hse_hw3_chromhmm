# hse_hw3_chromhmm
## Colab
[ссылка на колаб](https://colab.research.google.com/drive/1uUXhgnoPCbGP2ZsV7fpZS-LaxL2Qzx16?usp=sharing)
## Метки
| Название | Файл                                             |
|----------|--------------------------------------------------|
| H2az     | wgEncodeBroadHistoneGm12878H2azStdAlnRep1.bam    |
| H3k09me3 | wgEncodeBroadHistoneH1hescH3k09me3StdAlnRep1.bam |
| H3k4me1  | wgEncodeBroadHistoneH1hescH3k4me1StdAlnRep1.bam  |
| H3k4me2  | wgEncodeBroadHistoneH1hescH3k4me2StdAlnRep1.bam  |
| H3k4me3  | wgEncodeBroadHistoneH1hescH3k4me3StdAlnRep1.bam  |
| H3k9ac   | wgEncodeBroadHistoneH1hescH3k9acStdAlnRep1.bam   |
| H3k27ac  | wgEncodeBroadHistoneH1hescH3k27acStdAlnRep1.bam  |
| H3k27me3 | wgEncodeBroadHistoneH1hescH3k27me3StdAlnRep1.bam |
| H3k36me3 | wgEncodeBroadHistoneH1hescH3k36me3StdAlnRep1.bam |
| H3k79me2 | wgEncodeBroadHistoneH1hescH3k79me2StdAlnRep1.bam |
## cellmarkfiletable.txt
|Клеточная линия|Гистоновая метка|Файл метки|Контроль-файл|
|--------|----------|--------------|-------------|
| H1hESC | H2az     | H2az.bam     | Control.bam |
| H1hESC | H3k09me3 | H3k09me3.bam | Control.bam |
| H1hESC | H3k4me1  | H3k4me1.bam  | Control.bam |
| H1hESC | H3k4me2  | H3k4me2.bam  | Control.bam |
| H1hESC | H3k4me3  | H3k4me3.bam  | Control.bam |
| H1hESC | H3k9ac   | H3k9ac.bam   | Control.bam |
| H1hESC | H3k27ac  | H3k27ac.bam  | Control.bam |
| H1hESC | H3k27me3 | H3k27me3.bam | Control.bam |
| H1hESC | H3k36me3 | H3k36me3.bam | Control.bam |
| H1hESC | H3k79me2 | H3k79me2.bam | Control.bam |
## Графики из HTML файла
![transitions_10](https://user-images.githubusercontent.com/115037034/229914974-3c7ad2a2-1496-4337-8617-316d35d18735.png)
![emissions_10](https://user-images.githubusercontent.com/115037034/229915038-4c74c4ef-17a4-4de3-a88a-1a712130e5b4.png)
![H1hESC_10_overlap](https://user-images.githubusercontent.com/115037034/229915101-f7d94be4-a722-4adf-a52b-dac47035a1a0.png)
![H1hESC_10_RefSeqTSS_neighborhood](https://user-images.githubusercontent.com/115037034/229915132-a39aa836-ab6a-4d28-902d-6c53ac8157ee.png)
![H1hESC_10_RefSeqTES_neighborhood](https://user-images.githubusercontent.com/115037034/229915167-5a03608f-5478-44a6-9903-6b473f2322fb.png)
## Типы с функциями
### 1-Transcribed
Выражен в основном в H3k27me3. Чаще всего находится в RefSeqTES, реже в ядерной ламине.

![image](https://user-images.githubusercontent.com/115037034/230182754-11573084-9a9f-405a-be68-44b3e1260413.png)
### 2-Transcribed
Характерные метки - H3k27me3, H3k4me1, H3k4me2, H3k4me3. Находится в RefSeqTES, CpGisland, RefSeqExon, RefSeqTSS, реже в других местах

![image](https://user-images.githubusercontent.com/115037034/230184263-134c2b2d-7da8-4b0b-a365-1d2f5e74b102.png)

### 3-Active promoter
Основные метки - H3k4me2, H3k4me3, H3k9ac. Сосредоточен вокруг TSS, встречается в CpGisland, RefSeqExon.

![image](https://user-images.githubusercontent.com/115037034/230184997-11aea509-4437-4c4f-9e7f-5e964839a721.png)

### 4-Weak promoter
Метки: H3k4me2, H3k79me2. Состредоточен недалеко от TSS, находится в RefSeqGene, RefSeqTSS2kb.

![image](https://user-images.githubusercontent.com/115037034/230191714-71de072b-9ec9-40d6-93ae-829249d86fe8.png)

### 5-Weak transcribed
Характерная метка только одна H3k79me2. Находится в RefSeqGene. 

![image](https://user-images.githubusercontent.com/115037034/230192201-e40faf0e-44d6-43ce-8c23-ad8540dd45a1.png)

### 6-Weak enchancer
Характерная метка H3k36me3. Находится в RefSeqGene, RefSeqTES, попадает на экзоны.

![image](https://user-images.githubusercontent.com/115037034/230190696-708fd131-30e7-4fec-947d-44a8c4a5d8bb.png)

### 7-Chromatine
Для состояния характерна одна метка H3k09me3. Приемущественно попадает в ядерную ламину, есть в RefSeqTES.

![image](https://user-images.githubusercontent.com/115037034/230188920-708e9fa6-d842-4ac6-a00f-fe3ffd7665a9.png)

### 8-Repressed
Для состояния нет характерных меток. В основном находится в ядерной ламине, есть в RefSeqTES и RefSeqGene.

![image](https://user-images.githubusercontent.com/115037034/230190247-5c06e77b-c127-4cf3-8a18-9fcc1625d9dc.png)

### 9-Chromatine
H2az - характерная метка для состояния. В основном находится в ядерной ламине.

![image](https://user-images.githubusercontent.com/115037034/230193315-0d06f0b7-941d-4bd9-879e-7224a82816ff.png)

### 10-Transcribed
Несколько меток:  H3k4me1, H3k4me2, H3k27ac. Находится в RefSeqTES, RefSeqGene, на экзонах и интронах.

![image](https://user-images.githubusercontent.com/115037034/230191289-e9302ac5-4f34-4a45-aff7-144e3f63c318.png)


