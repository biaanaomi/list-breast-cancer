# List-Databases-Breast-Cancer


<div align="center">
  <img  width="350" height="350" src="https://miro.medium.com/max/1200/1*2QVeenJ2bdiA_9N8qvPiPA.png" width="350" alt="Breat Cancer">
	<br>
	<br>
	<p>
		<a href="https://www.cdc.gov/cancer/breast/basic_info/what-is-breast-cancer.htm">
			<b>What Is Breast Cancer?</b>
		</a>
	</p>
	<br>
</div>
<br/>

Repositório responsável em listar bancos de dados disponíveis para imagens de cancêr de mama!

## Datasets
Nome | Tipo | Quantidade | Especificação relacionada
:------------: | ------------------------ | ------------ | -
[Mammo](https://www.mammoimage.org/databases/) | Lista com vários datasets 
[BCSC: Digital Mammography Dataset](https://www.bcsc-research.org/data/mammography_dataset)| Diagnosis | 20,000 | This dataset does not include images. Some women contribute multiple examinations to the data. Mammogram assessment, subsequent breast cancer diagnosis within one year, age, family history of breast cancer, breast density, use of hormone therapy, body mass index, history of biopsy, receipt of prior mammography, and presence of comparison films.
[Breast Ultrasound Images Dataset (Dataset BUSI)](https://scholar.cu.edu.eg/?q=afahmy/pages/dataset)| Ultrasound (US) | 780 |  Women in ages between 25 and 75 years old. This data was collected in 2018. The number of patients is 600 female patients. average image size of 500*500 pixels. All images are classified as normal, benign and malignant in PNG.[Data](https://scholar.cu.edu.eg/?q=afahmy/pages/dataset) in [Article - Dataset of breast ultrasound images](https://www.sciencedirect.com/science/article/pii/S2352340919312181)
[CBIS-DDSM](https://wiki.cancerimagingarchive.net/display/Public/CBIS-DDSM)| Mammography  | 2,620 | Normal, benign, and malignant cases with verified pathology information. A case consists of between 6 and 10 files. Normal, cancer, benign and benign without callback
[Kaggle - Breast Cancer Wisconsin](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data) | Diagnosis | 357 benign, 212 malignant | Predict whether the cancer is benign or malignant. Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image.
[Lapimo BancoWeb](http://lapimo.sel.eesc.usp.br/lapimo/drupal/?q=node/8)| Mammography | 1.436 | Imagens, testes e avaliação comparativa de esquemas computadorizados de auxilio ao diagnóstico (CADs). A base contem imagens de vários hospitais, com grande variedade de laudos
[Mini-MIAS](http://peipa.essex.ac.uk/info/mias.html)| Mammography | 322  |  Class of abnormality present. Class of abnormality present. Severity of abnormality; Licence agreement 
[UFF Mammography Image Databases](http://www.ic.uff.br/~aconci/mam/frameex1.htm)| Mammography | ~70 cases | Benignos e Malignos. As imagens não são pré-processadas ou comprimidas.



## Datasets Genomic
Nome | Tipo | Quantidade de imagens | Especificação relacionada
:------------: | ------------------------ | ------------ | -
[NIH - Data Types Collected by TCGA](https://www.cancer.gov/about-nci/organization/ccg/research/structural-genomics/tcga/using-tcga/types)| Todos os cânceres | 20,000 tumor and normal samples

##Comando para instalar arquivos, diretórios inteiro html

'''wget -r -np http://www.ic.uff.br/~aconci/mam/'''

Ele fará o download de todos os arquivos e subpastas no diretório ddd
-r : recursivamente
-np: não vai para diretórios superiores

##Comandos para usar ftp e acessar diretorios

```
ncftp figment.csee.usf.edu
   cd pub/DDSM/cases/cancers/cancer_03
   get -R case1000
```
Ele fará conexão/login com ftp, acessar a pasta de interesse e obter o diretorio 
