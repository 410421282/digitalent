# DIGI+ Talent
DIGI+ Talent 跨域數位人才加速躍升計畫

# Overview
本課程將以生物資訊的角度切入，對NGS(Illumina based)基因數據分析提供基本概念與實作分析進行全面介紹。主要目標是讓學員具有理論基礎及獨立的基因組分析操作能力，非常適合初學者。

課程中涵蓋關鍵概念和分析策略。 將探索由現代DNA測序技術帶來的一系列生物學問題，包括序列比對，遺傳變異鑑定，結構變異分析等。

---
# Course lecture slides

* Course overview and Introduction to Linux
* Intruduction to NGS Technologies 
* NGS Data Format and Analysis Flow
* NGS Alignment
* NGS Variant Calling (Germline/Somatic)
* NGS SV/CNV Calling
* NGS Variant Annotation for Clinical

---
# Hands-On

* 計畫代號：ACD109--8
* 計算資源：
  * [NCHC Taiwania 1 (台灣杉一號)](https://iservice.nchc.org.tw/)
  * Node 為 3 CPU core, 4GB RMA
* 使用方式：
  * 採 PBSpro 送 job 進行相關的分析
  * job queue 為 ngscourse
* 軟體安裝路徑
  * `/pkg/biology/`

# Reference Genome
* hg19
* hg38

---
# NGS Tools

* [FASTQC 0.11.9](https://www.bioinformatics.babraham.ac.uk/projects/download.html#fastqc)
* [BWA-0.7.17(r1188)](https://github.com/lh3/bwa)
* [samtools 1.10](https://github.com/samtools/samtools)
* [htslib 1.10.2](https://github.com/samtools/htslib)
* [bcftools 1.10.2](https://github.com/samtools/bcftools)
* [sambamba 0.7.1](https://github.com/biod/sambamba)
* [bedtools2 2.29.2](https://github.com/arq5x/bedtools2)
* [GATK 4.1.8.1](https://github.com/broadinstitute/gatk/releases)
* [vcftools 0.1.16](https://github.com/vcftools/vcftools)
* [JAX-CNV 1.1.0](https://github.com/wanpinglee/JAX-CNV)
* [Annovar (2019Oct24)](https://doc-openbio.readthedocs.io/projects/annovar/en/latest/user-guide/download/)
* [AnnotSV 2.4](https://lbgi.fr/AnnotSV/downloads)

---
# Reference

* 2019 Genomic Epidemiology Workshop
* Applied Computational Genomics Course at UU