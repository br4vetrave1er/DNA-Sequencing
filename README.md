# DNA Sequencing
![Image]()
DNA is a macromolecule consisting of two strands that twist around a common axis in a shape called a double helix. The double helix looks like a twisted ladder—the rungs of the ladder are composed of pairs of nitrogenous bases (base pairs), and the sides of the ladder are made up of alternating sugar molecules and phosphate groups.

Molecules of DNA range in length from hundreds of thousands to millions of base pairs. The smallest chromosome in the human genome, Chromosome 21, has around 48 million base pairs.

A genome is an organism's complete set of genetic instructions. Each genome contains all of the information needed to build that organism and allow it to grow and develop.

As a data-driven science, genomics extensively utilizes machine learning to capture dependencies in data and infer new biological hypotheses. Nonetheless, the ability to extract new insights from the exponentially increasing volume of genomics data requires more powerful machine learning models. By efficiently leveraging large data sets, deep learning has reconstructed fields such as computer vision and natural language processing. It has become the method of preference for many genomics modeling tasks, including predicting the influence of genetic variation on gene regulatory mechanisms such as DNA receptiveness and splicing.

So here, we will understand DNA structure and how machine learning can be used to work with DNA sequence data.

Pre requisits:

1. **Biopython** : It is a collection of python modules that provide functions to deal with DNA, RNA & protein sequence operations such as reverse complementing of a DNA string, finding motifs in protein sequences, etc. It provides a lot of parsers to read all major genetic databases like GenBank, SwissPort, FASTA, etc.

```python
pip install biopython
```

2. **Squiggle** : It is a software tool that automatically generates interactive web-based two-dimensional graphical representations of raw DNA sequences. Built with ease of use in mind, Squiggle implements several prior sequence visualization algorithms and introduces novel visualization methods designed to maximize human usability.

```python
pip install Squiggle
```

![Image] (/home/indefinate/Downloads/DNA-Sequence-Machine-learning-master/3eee0b_fe5700c77ee54081b7ced60a753bd4a3~mv2.webp)

DNA sequence data usually are contained in a file format called “fasta” format. Fasta format is simply a single line prefixed by the greater than symbol that contains annotations and another line that contains the sequence:

***“AAGGTGAGTGAAATCTCAACACGAGTATGGTTCTGAGAGTAGCTCTGTAACTCTGAGG”***

Usage:

```python
python main.py
```
