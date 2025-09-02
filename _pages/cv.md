---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

**Download PDF:** [CV (PDF)](/files/CV.pdf)

---

Education
======
- **Ph.D., Computer Science**, New Jersey Institute of Technology (NJIT), Sep 2022 – May 2026 (expected)  
  Advisor: Prof. David A. Bader • Dissertation: *High-Performance and Scalable Graph Analytics for Real-World Applications* • GPA: 3.88  
- **M.S., Computer Architecture Engineering**, Azad University (Science & Research Branch), Sep 2008 – Feb 2011  
  Thesis: *Topology Control for Multi-Hop Data Traffic in Wireless Sensor Networks*  
- **B.S., Computer Hardware Engineering**, Shahid Beheshti University, Sep 1993 – Sep 1999  

Research Interests
======
High-Performance Computing (HPC); Parallel Graph Algorithms; Graph Neural Networks (GNNs); Graph Representation Learning; Knowledge Graphs.

Research Experience
======
- **Research Assistant, NJIT – Bader Lab** (Sep 2022 – Present)  
  - Developed **HiPerMotif**, **HiPerXplorer**, and **VF2-PS** for scalable motif discovery/subgraph isomorphism (10–100× speedups).  
  - Co-authored **MoMo** (adopted by Harvard, RWTH Aachen, Zuse Institute Berlin, Würzburg) for connectome analysis.  
  - Contributor to **Arkouda-NJIT** (Chapel/HPC ecosystem).  
  - Key Personnel on **NSF** projects: **CCF-2109988**, **CCF-2453324**, **OAC-2402560**; collaboration with UIUC (**OAC-2402559/2402560**).  

- **Earlier Roles (2003–2022)**  
  Consultant/Lecturer in ICT (IT Service Management, BPMS, telecom infrastructure); leadership and R&D across PMG Co., ICTRH, ITRC.

Ongoing Projects
======
- **HiPerXplorer**: parallel k-subgraph enumeration engine (manuscript in prep).  
- **Motif-Augmented Message Passing (MMP)** for GNNs (ongoing).  
- **Combinatorial Multigrid (CMG)** for pooling/unpooling/coarsening in GNNs (ongoing).  
- **NSF OAC Collaborative Project**: *Cyber-Infrastructure for Community Detection, Extraction, and Search in Large Networks* (OAC-2402559/2402560).  
- **On the Optimization of Methods for Establishing Well-Connected Communities* (submitted, 2025).  
- **TempAnom-GNN**: temporal GNNs for real-time fraud/cybersecurity (in progress, 2025).

Awards & Honors
======
- **Outstanding Student Paper Award**, IEEE HPEC 2025 (Best Paper Candidate)  
- **NSF EAGER: High** (stipend supplement, U.S. federal funding)  
- Top Researcher Candidate, ITRC (2017, 2019, 2021)  
- Employee of the Month, PMG Co. (5×, 2019–2022)  
- National Exam Rankings: M.S. Top 0.2% (2008), B.S. Top 0.006% (1993)

Invited Talks & Presentations
======
- **Delivered**: IEEE HPEC 2024; SIAM CSE 2025  
- **Scheduled**: IEEE HPEC 2025; ChapelCon 2025

Professional Service
======
- Program Committee Member & Reviewer: **ACM ICMR 2025**  
- Reviewer: **IEEE HPEC 2023–2025** (assignments via Prof. David Bader); **ACM ICMR** (4 papers)

Teaching & Mentorship
======
- Teaching Assistant, **NJIT** (CS114 Honors)  
- Mentored 3 undergraduates in HPC/GNNs (one co-authored a peer-reviewed paper)  
- Lecturer, **ICT Research Institute** (2010–2019); **Azad University** (2014–2015)

Research Impact & Open Source
======
- Lead developer of **HiPerMotif**, **HiPerXplorer**, **VF2-PS** (open-source).  
- **VF2-PS** adopted in **MoMo** (Harvard, RWTH Aachen, Zuse Institute Berlin, Würzburg).  
- Contributions span **neuroscience (connectomics)**, **HPC frameworks (Arkouda/Chapel)**, **graph learning**, with applications to **bioinformatics, cybersecurity, and fraud detection**.  
- **11 citations, h-index 2** (Google Scholar).

Technical Skills
======
- **Programming & HPC**: Python, C/C++, Chapel, MPI, OpenMP, Parallel Graph Algorithms  
- **Deep Learning**: PyTorch, TensorFlow, PyG, DGL  
- **Graph Learning**: GCN, GraphSAGE, GAT, SIGN, Knowledge Graphs, DiffPool, GraphUNet, MinCutPool, SAGPool, CMGPooling  
- **Other**: Hugging Face, LangChain, FAISS, SQL, AWS, Azure

Publications
======
<div class="wordwrap">
  You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.
</div>

<ul>
{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

Talks
======
<ul>
{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html  %}
{% endfor %}
</ul>

Teaching
======
<ul>
{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>

Service & Leadership
======
- Program committee and peer review for AI/HPC venues; mentoring undergraduate researchers; open-source maintainer.
