# seurat-v5-demo

This workflow is designed to demonstrate Seurat QC with various normalization
and sketching options. Note that this analysis was intended to compare the effect 
of SCT and Log-normalization with or without the 
[sketching](https://www.sciencedirect.com/science/article/pii/S2405471219301528)
method. Sketching was introduced to [Seurat v5](https://satijalab.org/seurat/) to enhance
memory usage when analyzing large datasets.

The current version was scripted based on the beta version of Seurat v5. Therefore,
there may be changes to the up-to-date Seurat v5.


```
$ tree
.
├── README.md
├── sampletable.tsv
└── scripts
    ├── seurat-v5-qc-lognorm-sketch.Rmd
    ├── seurat-v5-qc-lognorm-unsketch.Rmd
    ├── seurat-v5-qc-nosketch.Rmd
    ├── seurat-v5-qc-sct-sketch.Rmd
    ├── seurat-v5-qc-sct-unsketch.Rmd
    ├── seurat-v5-qc-sketch-lognormonly.Rmd
    └── seurat-v5-qc-sketch.Rmd
```


