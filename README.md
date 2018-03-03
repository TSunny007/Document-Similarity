# Document-Similarity
Using Jaccard-Similarity and MinHashing to determine similarity between two text documents

Semantic similarity forms a central component in many NLP systems, from lexical semantics, to part of speech tagging, to social media analysis. Recent years have seen a renewed interest in developing new similarity techniques. The increased interest has led to hundreds of techniques for measuring semantic similarity.

You can render the notebook online [Here](https://nbviewer.jupyter.org/github/TarunSunkaraneni/Document-Similarity/blob/master/Document%20Similarity.ipynb)
This Notebook explores one of the simplest techniques of investigating document similarity, using Jaccard Similarity and expands onto MinHashing to quickly differentiate between documents.

MinHashing is a technique for quickly estimating how similar two sets are. It was initially used in the AltaVista search engine to detect duplicate web pages and eliminate them from search results.
The original applications for MinHash involved clustering and eliminating near-duplicates among web documents, represented as sets of the words occurring in those documents. Similar techniques have also been used for clustering and near-duplicate elimination for other types of data, such as images: in the case of image data, an image can be represented as a set of smaller subimages cropped from it, or as sets of more complex image feature descriptions.
