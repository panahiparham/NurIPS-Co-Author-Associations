# NurIPS Co-Author Associations

## Abstract
With the rapid advancement of science, the volume of published research papers is growing exponentially making the task of searching and finding relevant articles especially difficult for students and researchers. Another issue is the increased complexity in the relationships between papers, their references, and their authors. This study focuses on using the A-priori algorithm to find frequent co-authors of papers and then extract pair-wise association rules between them. These tasks are performed on the NurIPS papers database. 

## Purpose 
This project aims to find interesting relationships between Researchers publishing papers in the Neural Information Processing Systems Journal. In particular we are interested in three questions:
  1. Who are the most published NIPS authors and their publications?
  2. Which groups of researchers have published several papers together?
  3. Which frequent authors, have always colaborated with a specific co-author?

The purpose of this work is to better understand the research landscape of Deep Learning and ease the process of finding interesting researchers and papers.


## Overview of Project
 * Extracting data
    - Web scraping with beautifulSoup
    - Hashing and storing paper and author names to disk
 * A-priori Algorithm for frequent pair mining
    - Implementing 2 pass A-priori
    - Implementing general multi-pass A-priori
 * Association Mining
    - Generating association rules
    - Perfect implications
 * Discussion
    - Confidence vs. Interestingness
    - Future work
    - Final note


 <em>
 </br>
This work is designed as the final project for "<a href="https://github.com/panahiparham/Algorithms-for-Data-Science-at-SBU">Algorithms for Datascience</a>" class offered at Shahid Beheshti University in Fall 2021.</br>
<b>Instructor</b>: <a href="http://facultymembers.sbu.ac.ir/katanforoush/">Dr. Ali Katanforoush</a></br>
<b>Student</b>: <a href="https://github.com/panahiparham">Parham Mohammad Panahi</a>(student id: 400422166)
 </em>
