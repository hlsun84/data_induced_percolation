# data_induced_percolation
This repository contains data we used in support of our work entitled "Indirect influence in social networks and the associated induced percolation model".

The files "collaboration_chaos.txt", "collaboration_pt.txt", and "collaboration_EPLDS.txt" provide the dataset of collaboration networks in three pairs of fields, they are Chaos vs. Complex Networks, Phase Transitions vs. Complex Networks, and Electrical Properties of Low-dimensional Structures vs. Optical Properties of Low-dimensional Structures (hereinafter referred to as EPLDS vs. OPLDS). The Carbon Nanotubes vs. Graphene dataset is large, therefore it is diveded into two files: "collaboration_nano.txt" and "collaboration_nano_2.txt". The file "get_result.m" provides the Matlab code to get our main result from these .txt files.

In each file, the five columns are the preset ID of the paper, the publication year of the paper, the field of the paper, the number of authors of the paper, and the preset author ID. For easier handling of the data, the 1st to 4th columns are repeated for <#column 4> times. Only the publications during the years 1999-2007 (2009-2017 for the fourth pair) are included. The field of the paper is marked as 1 (old) or 2 (new). The papers which have PACS numbers of both the old and new fields are removed to avoid ambiguity. For the fifth column, the author ID corresponds to his/her name, i.e. we do not recognize the author's different names in different articles, nor do we distinguish between different authors with the same name.
