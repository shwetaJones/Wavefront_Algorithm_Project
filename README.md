# Wavefront_Algorithm_Project

## Course: 02-604 "Fundamentals of Bioinformatics" at Carnegie Mellon University

### Collaborators: Shweta Jones and William Hsu

### Instructor: Phillip Compeau

_Paper Source: Marco-Sola, S., Moure, J. C., Moreto, M., & Espinosa, A. (2020). Fast gap-affine pairwise alignment using the wavefront algorithm. Bioinformatics, 37(4), 456–463. https://doi.org/10.1093/bioinformatics/btaa777_

**Link to Presentation Slides:** https://docs.google.com/presentation/d/1EIdQzFRV8Bvw3WYCRyEBJU_5q1sJ3XvzQNUvVfGktM8/edit?usp=sharing

In the domain of bioinformatics, sequence alignment stands as a fundamental task essential for deciphering the structure and function of biological molecules. Whether comparing DNA sequences to study genetic variation or analyzing protein sequences to understand their evolutionary relationships, efficient and accurate alignment algorithms play a pivotal role in extracting meaningful insights from biological data.
In the cases of longer sequences, such as those outputted by Oxford Nanopore or Pacbio where long reads tend to be between 10 kilobases to 1 megabase long, alignment with traditional dynamic programming methods can be unrealistic due to how computationally expensive these approaches are. Hence, an understanding of better algorithms for alignment is becoming more relevant. 
The wavefront algorithm was initially proposed and created as an exact gap affine algorithm for pairwise alignment in 2020. At its essence, sequence alignment involves identifying regions of similarity between two sequences by inserting gaps and mismatches to maximize their resemblance. Traditional alignment algorithms, such as dynamic programming approaches like Needleman-Wunsch and Smith-Waterman, suffer from high computational complexity, especially when dealing with large sequences or multiple alignments. It takes the traditional affine model and makes a more space and time-efficient alignment of two strings. The algorithm takes the affine alignment which has a runtime complexity of O(n2) and space complexity of O(n2) to O(ns) and O(s2), respectively. 
The Wavefront Algorithm for sequence alignment presents a fresh perspective by leveraging its efficient exploration strategy to navigate the space of possible alignments. Unlike conventional methods that compute alignment scores for all possible alignments in a matrix, the Wavefront Algorithm dynamically expands from an origin point, systematically exploring in a wave-like fashion in the alignment space. It dynamically adjusts the alignment path based on local similarities and differences between sequences.
In this final project, we implement, explain, and evaluate the Wavefront Algorithm for sequence alignment. We aim to demonstrate its effectiveness in accurately aligning sequences while maintaining computational efficiency. Through experimentation and comparative analysis with traditional alignment algorithms, we seek to unveil the potential of the Wavefront Algorithm as a valuable tool in bioinformatics research and sequence analysis.
