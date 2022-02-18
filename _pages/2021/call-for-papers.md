---
title: "Call for papers"
permalink: /2021/call-for-papers/
layout: single
classes: wide
header:
  overlay_color: "#000"
  overlay_filter: "0.1"
  overlay_image: /assets/images/banner.jpg
---

## Workshop on Human Evaluation of NLP Systems (HumEval)
### EACL’21, Kiev, Ukraine, 19th April 2021
### <https://humeval.github.io>
### First Call for Papers

The HumEval Workshop invites the submission of long and short papers on substantial, original, and unpublished research on all aspects of human evaluation of NLP systems, both intrinsic and extrinsic, including but by no means limited to NLP systems whose output is language.

### Invited Speakers

Margaret Mitchell \
Lucia Specia, UCL, UK 

### Important Dates

Dec 2, 2020: First Call for Workshop Papers\
Jan 4, 2021: Second Call for Workshop Papers (with new dates)\
Feb 1, 2021: Third Call for Workshop Papers\
Feb 15, 2021: Workshop Papers Due Date (11.59 pm UTC-12)\
Mar 22, 2021: Notification of Acceptance\
Apr 1, 2021: Camera-ready papers due\
Apr 7, 2021: EACL [early registration](https://2021.eacl.org/registration/) deadline\
Apr 19, 2021: HumEval Workshop

All deadlines are 11.59 pm UTC-12

### Workshop Topic and Content

Human evaluation plays a central role in NLP, from the large-scale crowd-sourced evaluations carried out e.g. by the WMT workshops, to the much smaller experiments routinely encountered in conference papers. Moreover, while NLP embraced automatic evaluation metrics from BLEU ([Papineni et al, 2001](https://www.aclweb.org/anthology/P02-1040.pdf)) onwards, the field has always been acutely aware of their limitations ([Callison-Burch et al., 2006](https://www.aclweb.org/anthology/E06-1032.pdf); [Reiter and Belz, 2009](https://www.aclweb.org/anthology/J09-4008.pdf); [Novikova et al., 2017](https://www.aclweb.org/anthology/D17-1238.pdf); [Reiter, 2018](https://www.aclweb.org/anthology/J18-3002.pdf)), and has gauged their trustworthiness in terms of how well, and how consistently, they correlate with human evaluation scores ([Over et al., 2007](https://doi.org/https://doi.org/10.1016/j.ipm.2007.01.019); [Gatt and Belz, 2008](https://www.aclweb.org/anthology/W08-1108); [Bojar et al., 2016](https://doi.org/10.18653/v1/W16-2301); [Shimorina, 2018](https://arxiv.org/pdf/1805.11474.pdf); [Ma et al., 2019](https://www.aclweb.org/anthology/W19-5302/); [Mille et al., 2019](https://doi.org/10.18653/v1/D19-6301); [Dušek et al., 2020](https://doi.org/https://doi.org/10.1016/j.csl.2019.06.009)). 

Yet there is growing unease about how human evaluations are conducted in NLP. Researchers have pointed out the less than perfect experimental and reporting standards that prevail ([van der Lee et al., 2019](https://www.aclweb.org/anthology/W19-8643.pdf)). Only a small proportion of papers provide enough detail for reproduction of human evaluations, and in many cases the information provided is not even enough to support the conclusions drawn. More than 200 different quality criteria (Fluency, Grammaticality, etc.) have been used in NLP  ([Howcroft et al., 2020](https://www.aclweb.org/anthology/2020.inlg-1.23)). Different papers use the same quality criterion name with different definitions, and the same definition with different names. As a result, we currently do not have a way of determining whether two evaluations assess the same thing which poses problems for both meta-evaluation and reproducibility assessments ([Belz et al., 2020](https://www.aclweb.org/anthology/2020.inlg-1.24.pdf)). 

Reproducibility in the context of automatically computed system scores has recently attracted a lot of attention, against the background of a troubling history ([Pedersen, 2008](https://www.aclweb.org/anthology/J08-3010.pdf); [Mieskes et al., 2019](https://doi.org/10.26615/978-954-452-056-4_089)), where reproduction is perceived as failing in 24.9% of cases for own results, and in 56.7% for another team’s ([Mieskes et al., 2019](https://doi.org/10.26615/978-954-452-056-4_089)). Initiatives have included the Reproducibility Challenge ([Pineau et al., 2019](https://zenodo.org/record/3158244/files/article.pdf), [Sinha et al., 2020](https://zenodo.org/record/3818627/files/article.pdf)); the Reproduction Paper special category at COLING'18; the reproducibility programme at NeurIPS'19 comprising code submission, a reproducibility challenge, and the ML Reproducibility checklist, also adopted by EMNLP'20 and AAAI'21; and the REPROLANG shared task at LREC'20 ([Branco et al., 2020](https://www.aclweb.org/anthology/2020.lrec-1.680)). 

However, reproducibility in the context of system scores obtained via human evaluations has barely been addressed at all, with a tiny number of papers (e.g. [Belz & Kow, 2010](https://www.aclweb.org/anthology/W10-4201.pdf); [Cooper & Shardlow, 2020](https://www.aclweb.org/anthology/2020.lrec-1.686.pdf)) reporting attempted reproductions of results. The developments in reproducibility of automatically computed scores listed above are important, but it is concerning that not a single one of the initiatives and events above addresses human evaluations. E.g. if a paper fully complies with all of the NeurIPS'19/EMNLP'20 reproducibility criteria, any human evaluation results reported in it may not be reproducible to any degree, simply because the criteria do not address human evaluation in any way. 

With this workshop we wish to create a forum for current human evaluation research and future directions, a space for researchers working with human evaluations to exchange ideas and begin to address the issues that human evaluation in NLP currently faces, including aspects of experimental design, reporting standards, meta-evaluation and reproducibility. We invite papers on topics including, but not limited to, the following:

* Experimental design for human evaluations
* Reproducibility of human evaluations
* Ethical considerations in human evaluation of computational systems
* Quality assurance for human evaluation 
* Crowdsourcing for human evaluation
* Issues in meta-evaluation of automatic metrics by correlation with human evaluations
* Alternative forms of meta-evaluation and validation of human evaluations
* Comparability of different human evaluations
* Methods for assessing the quality of human evaluations
* Methods for assessing the reliability of human evaluations
* Work on measuring inter-evaluator and intra-evaluator agreement
* Frameworks, model cards and checklists for human evaluation
* Explorations of the role of human evaluation in the context of Responsible AI and Accountable AI
* Protocols for human evaluation experiments in NLP

We welcome work on the above topics and more from any subfield of NLP (and ML/AI more generally), with a particular focus on evaluation of systems that produce language as output. We explicitly encourage the submission of work on both intrinsic and extrinsic evaluation.

### Paper Submission Information
#### Long Papers: 

Long papers must describe substantial, original, completed and unpublished work. Wherever appropriate, concrete evaluation and analysis should be included.
Long papers may consist of up to eight (8) pages of content, plus unlimited pages of references. Final versions of long papers will be given one additional page of content (up to 9 pages) so that reviewers' comments can be taken into account.
Long papers will be presented orally or as posters as determined by the programme committee. Cecisions as to which papers will be presented orally and which as posters will be based on the nature rather than the quality of the work. There will be no distinction in the proceedings between long papers presented orally and as posters.

#### Short Papers:

Short paper submissions must describe original and unpublished work. Short papers should have a point that can be made in a few pages. Examples of short papers are a focused contribution, a negative result, an opinion piece, an interesting application nugget, a small set of interesting results.
Short papers may consist of up to four (4) pages of content, plus unlimited pages of references. Final versions of short papers will be given one additional page of content (up to 5 pages) so that reviewers' comments can be taken into account.
Short papers will be presented orally or as posters as determined by the programme committee. While short papers will be distinguished from long papers in the proceedings, there will be no distinction in the proceedings between short papers presented orally and as posters.
Review forms will be made available prior to the deadlines. For more information on applicable policies, see the [ACL Policies for Submission, Review, and Citation](https://www.aclweb.org/portal/content/new-policies-submission-review-and-citation).

### Multiple Submission Policy

HumEval’21 allows multiple submissions. However, if a submission has already been, or is planned to be, submitted to another event, this must be clearly stated in the submission form.

### Ethics Policy

Authors are required to honour the ethical code set out in the [ACL Code of Ethics](https://www.aclweb.org/adminwiki/index.php?title=ACL_Resolutions#March_5.2C_2020).
The consideration of the ethical impact of our research, use of data, and potential applications of our work has always been an important consideration, and as artificial intelligence is becoming more mainstream, these issues are increasingly pertinent. We ask that all authors read the code, and ensure that their work is conformant to this code. Where a paper may raise ethical issues, we ask that you include in the paper an explicit discussion of these issues, which will be taken into account in the review process. We reserve the right to reject papers on ethical grounds, where the authors are judged to have operated counter to the ACL Code of Ethics, or have inadequately addressed legitimate ethical concerns with their work.

### Paper Submission and Templates

Submission is electronic, using the Softconf START conference management system. For electronic submission of all papers, please use: <https://www.softconf.com/eacl2021/HumEval2021>. Both long and short papers must be anonymised for double-blind reviewing, must follow the [ACL Author Guidelines](https://www.aclweb.org/adminwiki/index.php?title=ACL_Author_Guidelines), and must use the EACL’21 templates. You can find the EACL-2021 LaTeX template [on overleaf](https://www.overleaf.com/latex/templates/eacl-2021-proceedings-template/jprrhhtnbrrm) or [download the zip file](https://2021.eacl.org/downloads/eacl2021-templates.zip).

### Organisers

Anya Belz, University of Brighton, UK\
Shubham Agarwal, Heriot Watt University, UK\
Yvette Graham, Trinity College Dublin, Ireland\
Ehud Reiter, University of Aberdeen, UK\
Anastasia Shimorina, Université de Lorraine / LORIA, France

### PC Members

Mohit Bansal, UNC Chapel Hill, US\
Saad Mahamood, Trivago, DE\
Kevin B. Cohen, University of Colorado, US\
Nitika Mathur, University of Melbourne, Australia\
Kees van Deemter, Utrecht University, NL\
Margot Mieskes, UAS Darmstadt, DE\
Ondrej Dusek, Charles University, Czechia\
Emiel van Miltenburg, Tilburg University, NL\
Karën Fort, Sorbonne University, France\
Margaret Mitchell, Google, US\
Anette Frank, University of Heidelberg, DE\
Mathias Mueller, University of Zurich, CH\
Claire Gardent, CNRS/LORIA Nancy, France\
Malvina Nissim, Groningen University, NL\
Albert Gatt, Malta University, Malta\
Juri Opitz, University of Heidelberg, DE\
Dimitra Gkatzia, Edinburgh Napier University, UK\
Ramakanth Pasunuru, UNC Chapel Hill, US\
Helen Hastie, Heriot-Watt University, UK\
Maxime Peyrard, EPFL, CH\
David Howcroft, Heriot Watt University, UK\
Inioluwa Deborah Raji, Ai Now Institute, US\
Jackie Chi Kit Cheung, McGill University, Canada\
Verena Rieser, Heriot Watt University, UK\
Samuel Läubli, University of Zurich, CH\
Samira Shaikh, UNC, US\
Chris van der Lee, Tilburg University, NL\
Lucia Specia, UCL, UK\
Nelson Liu, Washington University, US\
Wei Zhao, TU Darmstadt, DE\
Qun Liu, Huawei Noah’s Ark Lab, China\
Behnam Hedayatnia, Amazon, US

### Contact Information

<humeval.ws@gmail.com>

<https://humeval.github.io>
