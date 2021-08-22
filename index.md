## GSoC '21 Report | Javed Ali | NRNB | GeneCloudOmics

![img](https://i0.wp.com/loankimrobinson.com/wp-content/uploads/2019/04/R_Shiny.png?fit=490%2C338&ssl=1)

---
**Mentors**<br><br>
Dr. Mohamed Helmy
Thuy Tien Bui

---
**Introduction**<br><br>
The Google summer of code program has been a great and fun learning experience to me over the past months, 
during which I was developing new features to the interactive webapp GeneCloudOmics . 
My project idea was to make the exisiting webapp UI uniform, adding some new features to help the Researchers in analysis. I also
added report generation of the analysis which can be used by Researchers for publication.<br>

---
**What is GeneCloudOmics**<br><br>
It is a web server for transcriptome data analysis and visualization. It supports the analysis of microarray and RNASeq data and performs ten different bio-statistical analyses that cover the common analytics for gene expression data. 
Furthermore, it gives the users access to several bioinformatics tools to perform 12 different bioinformatics analyses on gene/protein datasets.
It is designed as a one-stop server that helps the users perform all tasks through an intuitive graphical user interface (GUI) that waves the hassle of coding, installing tools, packages or libraries and dealing with operating systems compatibility and versioning issues, some of the complications that make data analysis tasks more challenging for biologists. 
GeneCloudOmics is an open-source tool and the website is free and open to all users and there is no login requirement.
GeneCloudOmics provides the user with the following bio-statistical analyses: Pearson and Spearman rank correlations, PCA, k-means and hierarchical clustering, Shannon entropy and noise (square of the coefficient of variation), t-SNE, random forest and SOM analyses.
All analyses include proper high-resolution visualization


---
**Project Goals**<br><br>
##### <u> Done </u>
- [x] Improving UI of the platform.
- [x] Adding missing buttons or UI elemets in the webapp.
- [x] Adding alternate way(copy paste box) of adding the data for Gene/Protein Analysis.
- [x] Adding option to import the data from GEO Database automatically using accession number.
- [x] Adding support of GEO database import for Microarray
- [x] Adding option to download all the analysis as PNG/PDF
- [x] Adding option to add the analysis to a report in pdf format.
- [x] Adding option to download the final report after the analysis.
- [x] Performing SOM analysis for research work.

---
**Contributions to GeneCloudOmics before GSoC:**<br><br>
1. **Added Docker Support**:  #[48](https://github.com/buithuytien/GeneCloudOmics/issues/48)
2. Created & hosted a static webpage for AbioTrans(GeneCloudOmics) on git-pages.([link](https://danijak.github.io/AbioTrans_Docs/))
3. Completed a Manual Test for the GeneCloudOmics using this [Open Source Data]( https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE54695 ) and submitted the corresponding report.

---
**Commits during GSoC period along with Goals**<br><br>
* Adding UI improvements and submit buttons
    * [UI Enhancements](https://github.com/danijak/GeneCloudOmics/commit/8414bbbef5324296d5f5e68aab79369301ce7f3a)
* Adding textbox for accession numbers in gene set and protein set analysis.
    * [Alternate data input](https://github.com/danijak/GeneCloudOmics/commit/12a01c0b3250a425bdeba4306fc9fb1324345c3f)
* Adding GEO Import from Accession Numnber
    * [GEO Import Prototype](https://github.com/danijak/GeneCloudOmics/commit/12a01c0b3250a425bdeba4306fc9fb1324345c3f)
* Adding support for RnaSeq in GEO Import
    * [RnsSeq support](https://github.com/danijak/GeneCloudOmics/commit/6b4c7e504639221c523addbae1b7973f81381c90)
* Adding download of plots in Transcriptome analysis
    * [Download Plots](https://github.com/danijak/GeneCloudOmics/commit/89e7c596dbc4a8f0a65b9226ba073517aa7aff6a)
* Adding download of report as PDF
    * [Download report](https://github.com/danijak/GeneCloudOmics/commit/47357e2d3e0e75c7f72701c44ed850bb06c03339)
 
** Pull Request during gsoc period**<br>
[https://github.com/buithuytien/GeneCloudOmics/pull/61](https://github.com/buithuytien/GeneCloudOmics/pull/61)
    
---
    
**Working Screengrabs:**<br><br>
1. *UI Improvements*<br><br>
 *Before*<br>
 ![sc1](https://user-images.githubusercontent.com/20498499/130141976-beef118d-9539-439a-ac38-cfb530fcb3a1.png)<br>
 *After*<br>
 ![sc2](https://user-images.githubusercontent.com/20498499/130142142-6a1be171-e4e0-422b-ae15-e441a609f400.png)<br><br>
2. *Text Box for Gene/Protien Input* view<br><br>
 *Before*<br>
 ![sc3](https://user-images.githubusercontent.com/20498499/130142468-77e0727f-68fc-438f-b656-06ab80c51e87.png)<br>
 *After*<br>
 ![sc4](https://user-images.githubusercontent.com/20498499/130142556-6a480686-0aa7-40ef-a756-bfc2cb8f8cf7.png)<br><br>
3. *GEO Data Import*<br><br>
 ![sc5](https://user-images.githubusercontent.com/20498499/130142759-9f3d8bbb-f995-4b49-8caa-c3f6b8028c58.png)<br><br>
4. *Dowload PNG/PDF*<br><br>
 ![sc5](https://user-images.githubusercontent.com/20498499/130143097-9046c79e-f895-49da-99e4-56d18e408a36.png)<br><br>
5. *Adding to report*<br><br>
 ![sc6](https://user-images.githubusercontent.com/20498499/130143179-0f880065-281a-4669-b418-267a6e6723ae.png)<br><br>
6. *Genrating Report*<br><br>
 ![sc7](https://user-images.githubusercontent.com/20498499/130273031-0d516579-526b-41ad-b2cc-4f8595c2d3fb.png)
 
---
**Future Aspects**

There are more feature which can be added:  
1. Improve SOM analysis for Research purpose.
2. Add report export options like email or save to drive.


---

### Important Links

- [GeneCloudOmics live portal](http://combio-sifbi.org/GeneCloudOmics/)
- [GeneCloudOmics github repo](https://github.com/buithuytien/GeneCloudOmics)
- [GeneCloudOmics documentation](https://github.com/buithuytien/GeneCloudOmics/blob/master/ABioTrans_UserManual_20190725.pdf)

- [GSoC GeneCloudOmics issue](https://github.com/buithuytien/GeneCloudOmics/issues)
- [GSoC @NRNB](https://nrnb.org/gsoc.html)
- [GSoC @NRNB GitHub](https://github.com/nrnb/GoogleSummerOfCode)
- [NRNB](https://nrnb.org/)

- [GitHub Javed Ali](https://github.com/danijak)
- [GSoC Project Link](https://summerofcode.withgoogle.com/dashboard/project/6244219309522944/overview/)


---

### Contact

- Email: 
**javedali9582@gmail.com**
<p>
<a href="https://www.linkedin.com/in/javed-ali-8aaa45147/" rel="nofollow noreferrer">
  <img src="https://i.stack.imgur.com/gVE0j.png" alt="linkedin"> LinkedIn
</a> &nbsp; 
<a href="https://github.com/danijak" rel="nofollow noreferrer">
  <img src="https://i.stack.imgur.com/tskMh.png" alt="github"> Github
</a>
</p>
 
