I am a Ph.D. Student in **integrated photonics** at **MIT**, working with [Dirk Englund](https://www.rle.mit.edu/qp/). My research interests are large scale and high speed  silicon photonic systems with low energy consumption. In particular, I am focused on demonstrating these systems on applications such as deep learning computation and Ising machines.<br>

I received my Bachelors of Science and Masters of Engineering Degrees both from MIT in 2018 and 2019 respectively. Earlier projects I have been involved in proposed using balanced homodyne detection as a means of computing vector-vector dot products.



## <i class="fa fa-chevron-right"></i> Education

<table class="table table-hover">
  <tr>
    <td class="col-md-3"> 2019 - 2024 (Expected) </td>
    <td>
        <strong>Ph.D. in Electrical Engineer and Computer Science </strong>
        <br>
      MIT (Cambridge, MA)
    </td>
  </tr>
  <tr>
    <td class="col-md-3"> 2018 - 2019 </td>
    <td>
        <strong>M.Eng. in Electrical Engineering and Computer Science</strong>
        <br>
      MIT (Cambridge, MA)
    </td>
  </tr>
  <tr>
    <td class="col-md-3"> 2014 - 2018</td>
    <td>
        <strong>B.Sc. in Electrical Engineering and Computer Science</strong>
        <br>
      MIT (Cambridge, MA)
    </td>
  </tr>
  <tr>
    <td class="col-md-3"> 2010 - 2014</td>
    <td>
      <strong> Associates in Arts and Associates in Science </strong>
      <br>
      Brunswick Community College (Supply, NC)
    </td>
  </tr>
</table>

## <i class="fa fa-chevron-right"></i> Notable Awards and Fellowships
<table class="table table-hover">
<tr>
  <td class='col-md-2'>2019</td>
  <td>
   Nation Sciecne Foundation Graduation Research Fellowships Program Recipient
    <!--  -->
  </td>
</tr>
  
<tr>
  <td class='col-md-2'>2014</td>
  <td>
    Brunswick Community College President's Award (2014) for Highest GPA in graduating class (acquired at same time as high school diploma)
  </td>
</tr>

</table>

## <i class="fa fa-chevron-right"></i> Research Projects and Publications <a href=""><i class="fa fa-code-fork" aria-hidden="true"></i></a>

<a href="https://scholar.google.com/citations?user=xQ3bAK0AAAAJ&hl=en" class="btn btn-primary" style="padding: 0.3em;">
  <i class="ai ai-google-scholar"></i> Google Scholar
</a>
<table class="table table-hover">
<tr>
<td class="col-md-3"><a href='https://www.nature.com/articles/s41598-021-82543-3' target='_blank'><img src="images/publications/SCOT.png"/></a> </td>
<td>
    <strong>Freely scalable and reconfigurable optical hardware for deep learning</strong><br>
    L. Bernstein*#, <strong>A. Sludds*#</strong>, R. Hamerly, V. Sze, J. Emer, D. Englund <br>
     *Equal Contribution, #Corresponding Author<br>
    Nature Scientific Reports <br>
    [5] 
[<a href='javascript:;'
    onclick='$("#abs_demetcisantorella").toggle()'>abstract</a>] [<a href='https://www.nature.com/articles/s41598-021-82543-3' target='_blank'>paper</a>] <br>
    
<div id="abs_demetcisantorella" style="text-align: justify; display: none" markdown="1">
As deep neural network (DNN) models grow ever-larger, they can achieve higher accuracy and solve more complex problems. This trend has been enabled by an increase in available compute power; however, efforts to continue to scale electronic processors are impeded by the costs of communication, thermal management, power delivery and clocking. To improve scalability, we propose a digital optical neural network (DONN) with intralayer optical interconnects and reconfigurable input values. The path-length-independence of optical energy consumption enables information locality between a transmitter and a large number of arbitrarily arranged receivers, which allows greater flexibility in architecture design to circumvent scaling limitations. In a proof-of-concept experiment, we demonstrate optical multicast in the classification of 500 MNIST images with a 3-layer, fully-connected network. We also analyze the energy consumption of the DONN and find that digital optical data transfer is beneficial over electronics when the spacing of computational units is on the order of >10μm.
</div>
</td>
</tr>


<tr>
<td class="col-md-3"><a href='https://www.biorxiv.org/content/10.1101/2020.06.13.149195v1' target='_blank'><img src="images/publications/alignment.png"/></a> </td>
<td>
    <strong> Unsupervised Manifold Alignment for Single-Cell Multi-Omics Data</strong><br>
    R. Singh#, <strong>P. Demetci</strong>, G. Bonora, V. Ramani, C. Lee, H. Fang, Z. Duan, X. Deng, J. Shendure, C. Disteche and W. Stafford Noble#<br>
     #Corresponding Authors<br>
    Proceedings of the 11th ACM International Conference on Bioinformatics, Computational Biology, and Health Informatics (ACM BCB 2020)<br>
    
    [4] 
[<a href='javascript:;'
    onclick='$("#abs_singhdemetci").toggle()'>abstract</a>] [<a href='https://dl.acm.org/doi/10.1145/3388440.3412410' target='_blank'>paper</a>] <br>
    
<div id="abs_singhdemetci" style="text-align: justify; display: none" markdown="1">
Integrating single-cell measurements that capture different properties of the genome is vital to extending our understanding of genome biology.This task is challenging due to the lack of a shared axis across datasets obtained from different types of single-cell experiments. For most such datasets, we lack corresponding information among the cells (samples) and the measurements (features). In this scenario, unsupervised algorithms that are capable of aligning single-cell experiments are critical to learning an in silico co-assay that can help draw correspondences among the cells.Maximum mean discrepancy-based manifold alignment (MMD-MA) is such an unsupervised algorithm. Without requiring correspondence information, it can align single-cell datasets from different modalities in a common shared latent space, showing promising results on simulations and a small-scale single-cell experiment with 61 cells.However, it is essential to explore the applicability of this method to larger single-cell experiments with thousands of cells so that it can be of practical interest to the community.In this paper, we apply MMD-MA to two recent datasets that measure transcriptome and chromatin accessibility in ~2000 single cells. To scale the runtime of MMD-MA to a more substantial number of cells, we extend the original implementation to run on GPUs. We also introduce a method to automatically select one of the user-defined parameters, thus reducing the hyperparameter search space. We demonstrate that the proposed extensions allow MMD-MA to accurately align state-of-the-art single-cell experiments.
</div>

</td>
</tr>


<tr>
<td class="col-md-3"><a href='https://www.iscb.org/cms_addon/conferences/ismb2020/proceedings.php' target='_blank'><img src="images/publications/HAPLEX.png"/></a> </td>
<td>
    <strong>Combinatorial and statistical prediction of gene expression from haplotype sequence</strong><br>
    B. Alpay*, <strong>P. Demetci*</strong> Sorin Istrail, and Derek Aguiar# <br>
     *Equal Contribution, #Corresponding Author<br>
     Bioinformatics (Oxford Press) vol.36, Supplement_1, p:i194-i202. 2020 <br>
    Proceedings of the 27th International Conference on Intelligent Systems for Molecular Biology (ISMB 2020)<br>
    
    [3] 
[<a href='javascript:;'
    onclick='$("#abs_alpaydemetci").toggle()'>abstract</a>] [<a href='https://www.iscb.org/cms_addon/conferences/ismb2020/proceedings.php' target='_blank'>paper</a>] <br>
    
<div id="abs_alpaydemetci" style="text-align: justify; display: none" markdown="1">
Genome-wide association studies (GWAS) have discovered thousands of significant genetic effects on disease phenotypes.By considering gene expression as the intermediary between genotype and disease phenotype, eQTL studies have interpreted many of these variants by their regulatory effects on gene expression. However, there remains a considerable gap between genotype-to-gene expression association and genotype-to-gene expression prediction. Accurate prediction of gene expression enables gene-based association studies to be performed post-hoc for existing GWAS, reduces multiple testing burden, and can prioritize genes for subsequent experimental investigation.In this work, we develop gene expression prediction methods that relax the independence and additivity assumptions between genetic markers. First, we consider gene expression prediction from a regression perspective and develop the HAPLEXR algorithm which combines haplotype clusterings with allelic dosages. Second, we introduce the new gene expression classification problem, which focuses on identifying expression groups rather than continuous measurements; we formalize the selection of an appropriate number of expression groups using the principle of maximum entropy. Third, we develop the HAPLEXD algorithm that models haplotype sharing with a modified suffix tree data structure and computes expression groups by spectral clustering. In both models, we penalize model complexity by prioritizing genetic clusters that indicate significant effects on expression. We compare HAPLEXR and HAPLEXD with three state-of-the-art expression prediction methods and two novel logistic regression approaches across five GTEx v8 tissues. HAPLEXD exhibits significantly higher classification accuracy overall; HAPLEXR shows higher prediction accuracy on approximately half of the genes tested and the largest number of best predicted genes ($r^2>0.1$) among all methods.
We show that variant and haplotype features selected by HAPLEXR are smaller in size than competing methods (and thus more interpretable) and are significantly enriched in functional annotations related to gene regulation. These results demonstrate the importance of explicitly modelling non-dosage dependent and intragenic epistatic effects when predicting expression.
</div>

</td>
</tr>

<tr>
<td class="col-md-3"><a href='https://jb.asm.org/content/early/2019/07/03/JB.00259-19/figures-only?versioned=true' target='_blank'><img src="images/publications/ecoli.png"/></a> </td>
<td>
    <strong>Rapid accumulation of motility-activating mutations in resting liquid culture of <em>Escherichia coli</em></strong><br>
    D. Parker*, <strong>P.Demetci*</strong>, and G.W. Li# <br>
     *Equal Contribution,  #Corresponding Author<br>
    Journal of Bacteriology, 2019<br>
    
    [2] 
[<a href='javascript:;'
    onclick='$("#abs_parkerdemetci").toggle()'>abstract</a>] [<a href='https://jb.asm.org/content/early/2019/07/03/JB.00259-19/figures-only?versioned=true' target='_blank'>paper</a>] <br>
    
<div id="abs_parkerdemetci" style="text-align: justify; display: none" markdown="1">
Expression of motility genes is a potentially beneficial but costly process in bacteria. Interestingly, many isolate strains of _Escherichia coli_ possess motility genes but have lost the ability to activate them in conditions in which motility is advantageous, raising the question of how they respond to these situations. Through transcriptome profiling of strains in the _E. coli_ single-gene knockout Keio collection, we noticed drastic upregulation of motility genes in many of the deletion strains as compared to its weakly motile parent strain (BW25113). We show that this switch to a motile phenotype is not a direct consequence of the genes deletec, but is instead due to a variety of secondary mutations that increase the expression of the major motility regulator, FlhDC. Importantly, we find that this switch can be reproduced by growing poorly motile _E. coli_ strains in non-shaking liquid medium overnight but not in shaking liquid medium. Individual isolates after the non-shaking overnight incubations acquired distinct mutations upstream of the _flhDC_ operon, including different insertion sequence (IS) elements and, to a lesser extent, point mutations. The rapid sweep in the non-shaking population shows that poorly motile strains can quickly adapt to a motile lifestyle by genetic rewiring. 
</div>
</td>
</tr>

<tr>
<td class="col-md-3"><a href='https://ieeexplore.ieee.org/abstract/document/7757463' target='_blank'><img src="images/publications/blank.png"/></a> </td>
<td>
    <strong>Internalization and externalization in the classroom: How do they emerge and why is it important?</strong><br>
     <strong>P.Demetci</strong>, C. Nichols, Y. V. Zastavker, J. D. Stolk, A. Dillon, M. D. Gross.<br>
    IEEE, 2016<br>
    FIE Conference, 2016<br>
    
    [1] 
[<a href='javascript:;'
    onclick='$("#abs_demetcinichols").toggle()'>abstract</a>] [<a href='https://ieeexplore.ieee.org/abstract/document/7757463'  target='_blank'>paper</a>] <br>  
<div id="abs_demetcinichols" style="text-align: justify; display: none" markdown="1">
“I felt so dumb, and it's not fair that I cannot grasp this information to save my life, and other people can with no problem.” Why do some students feel empowered in the classroom, and feel they have control over their own learning, while others do not? Our qualitative investigation is a part of a larger mixed-methods study about students' situational motivations in introductory STEM courses. We used grounded theory to analyze students' responses to surveys about emotion, course relevance, and motivation. We investigated two emergent phenomena we called “internalization” and “externalization.” Our definitions of these are based on a student's perception of who or what influences the outcomes of their activities: the students themselves, or external factors such as the instructor, peers, or the educational system as a whole. Our findings indicate that (1) internalization correlates with cognitive autonomy, students' perception of course content having high personal relevance, and group projects in project-based learning environments; and (2) externalization correlates with lecture-based environments and students' perceptions of lack of personal relevance in the course content. Our analyses suggest that project-based learning environments may serve to empower students, but only when course content is found to be relevant.
</div>
</td>
</tr>
</table>

## <i class="fa fa-chevron-right"></i> Professional Experience
<table class="table table-hover">
<tr>
  <td class='col-md-3'>June 2020 - Sep 2020</td>
  <td><strong>Microsoft Research: Genomics</strong>, Research Intern (Redmond, WA)</td>
</tr>
<tr>
</tr>
<tr>
  <td class='col-md-3'>June 2017 - August 2018</td>
  <td><strong>Massachusetts Institute of Technology</strong>, Research Support Associate (Cambridge, MA)</td>
</tr>
<tr>
  <td class='col-md-3'>Jan 2016 - Oct 2016</td>
  <td><strong>Design That Matters</strong>, Student Engineer (Salem, MA)</td>
</tr>
<tr>
  <td class='col-md-3'>Jan 2015 - Dec 2015</td>
  <td><strong>Daktari Diagnostics</strong>, Student Engineer (Cambridge, MA)</td>
</tr>
</table>



## <i class="fa fa-chevron-right"></i> Invited Talks, and Conferences Presentations
<ins>Presenters underlined</ins>,  Equal contribution denoted with: *

<table class="table table-hover">
  <tr>
  <td class='col-md-1'>2020</td>
  <td><strong>ICML Workshop on Computational Biology (Poster & Spotlight Presentation) </strong>  [Acceptance Rate: 21%]<br>
    Gromov-Wasserstein Optimal Transport to Align Single-Cell Multi-Omics Data  <br>
  <strong><ins>P Demetci*</ins></strong> [spotlight], <ins>R Santorella*</ins> [poster], B Sandstede, W Stafford Noble, R Singh</td>
</tr>
<tr>
  <td class='col-md-1'>2020</td>
  <td><strong>ISMB Proceedings (Oral Presentation) </strong> [Acceptance Rate: 19%]<br>
   Combinatorial and statistical prediction of gene expression from haplotype sequence  <br>
  <ins>B Alpay*</ins>, <strong>P Demetci*</strong>, S Istrail, D Aguiar</td>
</tr>
<tr>
  <td class='col-md-1'>2020</td>
  <td><strong>ISMB (Oral & Poster Presentation)</strong> [Acceptance Rate: 25%] <br>
    Gromov-Wasserstein Optimal Transport to Align Single-Cell Multi-Omics Data  <br>
    <ins><strong>P Demetci </strong></ins> [poster], <ins>R Santorella*</ins> [oral], B Sandstede, W Stafford Noble, R Singh</td>
</tr>
<tr>
  <td class='col-md-1'>2020</td>
  <td><strong>Brown Unconference on Computational Intelligence and Applications (Invited Talk)</strong> <br>
    Gromov-Wasserstein Optimal Transport to Align Single-Cell Multi-Omics Data  <br>
  <strong><ins>P Demetci*</ins></strong>, R Santorella*, B Sandstede, W Stafford Noble, R Singh</td>
</tr>
<tr>
  <td class='col-md-1'>2019</td>
  <td><strong>CCV-Con (Invited Talk @ Brown University) </strong> <br>
    Biologically Annotated Neural Networks for Multi-scale Genomic Association Discovery  <br>
  <ins><strong>P Demetci</strong></ins>, W Cheng, G Darnell, S Ramachandran, L Crawford</td>
</tr>
<tr>
  <td class='col-md-1'>2016</td>
  <td><strong>FIE (Oral Presentation) </strong> [Acceptance Rate: 48%] <br>
    Internalization and externalization: How do they emerge and why is it important?  <br>
  <ins><strong>P Demetci</strong></ins>, <ins>C Nichols</ins>, Y V Zastavker, J D Stolk, A Dillon, M D Gross</td>
</tr>
<tr>
  <td class='col-md-1'>2016</td>
  <td><strong>NEMPET (Poster Presentation) </strong> <br>
    Bioinformatic Comparison of Phototrophic Communitiesthat Degrade Cellulose and Fix Nitrogen  <br>
  <ins><strong>P Demetci</strong></ins>, M Sheets, A Knapp, Linda Amaral-Zettler, Jean Huang</td>
</tr>
<tr>
  <td class='col-md-1'>2015</td>
  <td><strong>Closing the Gap (Oral Presentation) </strong> <br>
    Project EyeHelper: Assistive Navigation for Blind Shopping  <br>
  <ins><strong>P Demetci</strong></ins>, <ins>A Johnnson</ins>, <ins>M Ruehle</ins>, P Ruvolo</td>
</tr>
</table>


## <i class="fa fa-chevron-right"></i> Teaching Experience
<table class="table table-hover">
<tr>
  <td class='col-md-1'>Spring 2019</td>
  <td><strong>Control Theory</strong> (6.302 @ MIT)<br>
  Teaching Assistant and Laboratory Assistant: wrote and graded assignments, held recitations and office hours. Assisted in weekly lab assignments.</td>
</tr>
  
<tr>
  <td class='col-md-1'>Fall 2018</td>
  <td><strong>Graduate Electromagnetics</strong> (6.630 @ MIT)<br>
   Teaching Assistant: graded assignments, assisted students in the laboratory.</td>
</tr>
  
<tr>
  <td class='col-md-1'>Spring 2018</td>
  <td><strong>Undergraduate Electromagnetics</strong> (6.013 @ MIT)<br>
   Teaching and Laboratory Assistant: graded assignments, assisted students in the laboratory.</td>
</tr>
  
<tr>
  <td class='col-md-1'>IAP 2018, 2017, 2016</td>
  <td><strong>Introduction to Signals and Systems <strong> (6.058 @ MIT)<br>
   Instructor for month long intensive signals and systems course. Created lectures and coursework.</td>
</tr>
  
<tr>
  <td class='col-md-1'>Fall 2017</td>
  <td><strong>Machine Learning <strong> (6.036 @ MIT)<br>
   Lab Assistant: Helped assisting laboratory instruction. </td>
</tr>
  
<tr>
  <td class='col-md-1'>Fall 2017</td>
  <td><strong>Circuits and Electronics <strong> (6.002 MIT)<br>
   Lab Assistant: Helped assisting laboratory instruction. </td>
</tr>
    
<tr>
  <td class='col-md-1'>Fall 2017</td>
  <td><strong>Circuits and Electronics <strong> (6.002 MIT)<br>
   Lab Assistant: Helped assisting laboratory instruction. </td>
</tr>
    
<tr>
  <td class='col-md-1'>Spring 2017, Summer 2016</td>
  <td><strong>Control Theory <strong> (6.302 MIT)<br>
   Lab Assistant: Helped assisting laboratory instruction. Summer course was via EdX deployed to hundreds of students worldwide.</td>
</tr>
    
<tr>
  <td class='col-md-1'>Fall 2016, 2017</td>
  <td><strong>Introduction to Digital Electronics <strong> (6.072 MIT)<br>
   Instructor: Created course material and lectures. Managed laboratory sections for 10 students. Introduced labs based on FPGA boards.</td>
</tr>
    
</table>

## <i class="fa fa-chevron-right"></i> Skills
<table class="table table-hover">
  
<tr>
  <td class='col-md-2'>Integrated Photonic Design</td>
  <td>
    I have fabricated and tested several large scale silicon photonic chips in commercial CMOS pilot line foundries. Several of these systems have hundreds of active photonic devices which are used simultaneously. 
    
    Tools:
    Proficient: Lumerical FDTD, Lumerical Mode, Synopsys Optisim
    Moderate experience: Lumerical Charge, Lumerical Heat, Synopsys RSOFT
  </td>
</tr>
  
<tr>
  <td class='col-md-2'>Packaging</td>
  <td>
    Create multiple custom packages for silicon photonic ICs that are capable of of supporting high frequency (>20GHz) signals with many (>200) bond wires with a high degree of mechanical and temperature stability (<0.01 degrees drift over weeks timescales).
  </td>
</tr>
  
<tr>
  <td class='col-md-2'>Fabrication</td>
  <td>
    Fabrication experience in university fabrication facilities (MIT NANO) doing deposition, photolithography and etching to create mechanical, electrical, and optical devices.
  </td>
</tr>
  
<tr>
  <td class='col-md-2'>Analog Circuit Design</td>
  <td>
    Created multiple analog systems included a custom highly sensitive optical receiver with 220fF of capacitance.
  </td>
</tr>
  
<tr>
  <td class='col-md-2'>Programming Languages</td>
  <td>
    Very proficient: Python
    Moderate experience: C++, Matlab
  </td>
</tr>
  
<tr>
<td class='col-md-2'>Software Tools</td>
<td>
  Very Proficient: NumPy, Pandas, SciPy, Matplotlib
</td>
</tr>
  
<tr>
<td class='col-md-2'>Operating Systems</td>
<td>
  Linux, Windows, OSX
</td>
</tr>
</table>
