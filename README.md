Guidelines and template for the student paper competition for the Copper Mountain Conference on Multigrid Methods.

# How to Use this Template

The file `paper-template.tex` should be used as a template for a student paper submission.  The first step is to rename this file to
```bash
cp paper-template.tex LASTNAME_FIRSTNAME_paper.tex
```

The template is based on the latest SIAM article class, which is detailed here: [https://www.siam.org/Publications/Journals/About-SIAM-Journals/Information-for-Authors](https://www.siam.org/Publications/Journals/About-SIAM-Journals/Information-for-Authors).  The paper should conform to the SIAM documentclass as outlined here: [https://www.siam.org/Portals/0/Macros/Standard/docsiamart.pdf](https://www.siam.org/0/Macros/Standard/docsiamart.pdf).

To obtain SIAM article class, download `siamart171218.cls` at the link [https://www.siam.org/Portals/0/Macros/Standard/siamart171218.cls](https://www.siam.org/Portals/0/Macros/Standard/siamart171218.cls) or by
```bash
wget https://www.siam.org/Portals/0/Macros/Standard/siamart171218.cls
```

In addition, obtain the SIAM bibliographic style file `siamplain.bst` at the link [https://www.siam.org/Portals/0/Macros/Standard/siamplain.bst](https://www.siam.org/Portals/0/Macros/Standard/siamplain.bst) or by
```bash
wget https://www.siam.org/Portals/0/Macros/Standard/siamplain.bst
```

Next, be sure to follow the specific steps below, including the writing guidelines.  The numbering can be found in the comments of `paper-template.tex`.

# Specific Lines to Change in the TeX File

1. Preamble and packages

  Add packages such as `tikz` that are required to build the paper.  Take care to only include packages that conform to the SIAM article class.

2. Paper title

  Add the paper title.

3. Student Name

  Add *only* your name, i.e., The Author, a.k.a The Student.

4. Student Address

  Add your university address.

5. Acknowledge funding or other resources

  You may acknowledge funding here.

6. Collaborators, such as advisor or research collaborators

  Add your advisor(s) or close collaborators that helped guide you in your research.  This is most likely a full author list should you develop this submission into a journal article.

7. Keywords that describe the paper

  Please add descriptive keywords that may help in the review process.

# Guidelines for Writing
