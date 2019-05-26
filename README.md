## Heterogeneous Information Network Datasets

### Download links

[DBLP (Google Drive)](https://drive.google.com/open?id=1YG9VR3vd6ewtMhdrcNXF5T_WTbx6MwYK): 601.4MB
<br>
[SLAP (Google Drive)](https://drive.google.com/open?id=1mIcLcxyg3WZApq6a4fIlADyU42WQKeGB): 295.8MB
<br>
[ACM (Google Drive)](https://drive.google.com/open?id=16R7ewS9cb5Bci7ClC0Ao1IYQmWPb-lHs): 752.1MB
<br>
[IMDB (Google Drive)](https://drive.google.com/open?id=1tqzNDkbZWGoG-vpM_M2X-EqRoPT1rp9k): 94.3MB

### Datasets information

| Dataset | # Nodes    |Node types                             | Meta-paths                                            | # Meta-path instances| # Labels | # Features |
|:-------:|:----------:|:-------------------------------------:|:-----------------------------------------------------:|:------------------:|:--------:|:----------:|
| DBLP    | 14475(A)   | Author(A)<br>Paper(P)<br>Conference(C)| APA<br>APCPA                                          | 40269<br>19445349  | 4        | 5000<sup>+</sup>       |
| SLAP    | 20419(G)   | Gene(G)<br>Gene Ontology(O)<br>Pathway(P)<br>Compound(C)<br>Tissue(T)<br>Gene Family(F)<br>Disease(D) | GTG<br>GFG<br>GDG<br>GPG<br>GOG<br>GG<br>GDCDG | 303487<br>582741<br>7494<br>416462<br>3185779<br>172248<br>18095 | 15 | 2695 |
| ACM     | 12499(P)   | Paper(P)<br>Author(A)<br>Proceeding(O)<br>Institute(I)<br>Conference(C) | PAP<br>PAIAP<br>POP<br>POCOP<br>PP | 91662<br>13303015<br>700386<br>7849967<br>30621                 | 11 | 8000 |
| IMDB<sup>*</sup>    | 18352(M)   | Movie(M)<br>Actor(A)<br>Actress(E)<br>Director(D)                   | MAM<sup>?</sup><br>MDM<sup>?</sup><br>MEM<sup>?</sup> | 63659<sup>?</sup><br>1085810<sup>?</sup><br>565443<sup>?</sup><br> | 9 | 1000 |

### Notice
* <sup>*</sup> Multiple label dataset.
* <sup>?</sup> Not sure which meta-path is corresponding to which number of meta-path instances.
* <sup>+</sup> Use `nltk.corpus.stopwords` and extract the bag-of-word representation.
* For `DBLP`, `SLAP` and `ACM`, please refer to the paper [Meta Path-Based Collective Classification in Heterogeneous Information Networks](https://arxiv.org/pdf/1305.4433.pdf).
* For `IMDB`, please refer to the paper [Column Networks for Collective Classification](https://arxiv.org/pdf/1609.04508.pdf).
