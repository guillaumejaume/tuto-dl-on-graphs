
# Tutorial to learn the basics of deep learning on graphs

## Schedule

| Time        | Title                                
|-------------|--------------------------------------|
| 30mn | Introduction to ML on graphs and GNNs |
| 15mn | Hands-on part 1: Predicting Molecular Properties |
| 30mn | Hands-on part 2: Link Prediction on a Knowledge Graph |
| 15mn | Discussion, references and closing remarks |

## Requirements

This tutorial is designed for everyone who would like to learn the basics of deep learning on graph-structured data and Graph Neural Networks (GNN). The tutorial will provide an introduction to key concepts and recent developments in the field of machine learning on graphs and will guide the participants to design their first deep learning pipeline that can operate on graph-structured data.  

### Setup

**We strongly suggest to setup your machine prior to the tutorial (ideally the day before)** following the instructions. Should you incur into any issue, please do not hesitate to contact (me) [Guillaume](mailto:gja@zurich.ibm.com).

Installation with Conda:

- Setup conda on your machine (if not already done). 
    - On [Windows](https://docs.conda.io/projects/conda/en/latest/user-guide/install/windows.html)
    - On [MacOS](https://docs.conda.io/projects/conda/en/latest/user-guide/install/macos.html)
    - On [Linux](https://docs.conda.io/projects/conda/en/latest/user-guide/install/linux.html)
- Create the conda environment:

```console
conda env create -f environment.yml
```

Activate it:

```console
conda activate graphml-env
```

### Relevant papers

- **How powerful are Graph Neural Networks?** [Arxiv](https://arxiv.org/abs/1810.00826).

A theoretical analysis of graph neural networks. Great starting point to understand what GNNs can and cannot do. Since, many papers have proposed deeper analysis of the expressive power of GNNs. 

- **Modeling Relational Data with Graph Convolutional Networks** [Arxiv](https://arxiv.org/abs/1703.06103).

The first GNN designed to operate on Knowledge Graphs that was able to beat the state-of-the-art (better than DistMult, ComplEx, Rotate, etc...)

- **Benchmarking Graph Neural Networks** [Arxiv](https://arxiv.org/abs/2003.00982).

The most up-to-date (as of Sept 2020) paper that is properly benchmarking the most popular Graph Neural Networks architectures on a variety of datasets. 

Participants that would like more graph-related references can refer to the [graph-neural-networks-roadmap](https://github.com/guillaumejaume/graph-neural-networks-roadmap). A more up-to-date list can be found [here](graph-based-deep-learning-literature).

## Organisers and tutors

- [Guillaume Jaume](https://researcher.watson.ibm.com/researcher/view.php?person=zurich-GJA), IBM Research Zürich

