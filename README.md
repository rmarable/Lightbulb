# Lightbulb

A single cell RNA-seq analysis pipeline/suite currently focusing on 10X data and time series samples.

Todos:

|part name          | description	             | dependency |	language |	progress |
|:----------------- |:-------------------------- |:---------- |:-------- |:---------------------------|
|LightReader_10X    | read and filter 10X data   |	cellrangerRkit, data.table |	R |	Mostly finished |
|LightCleaner       |	remove outlier and cap expression |	|	R |	Mostly finished |
|LightNorm          |   normalization and spline find     | TSNE   | R     | Mostly finished |
|LightMagic         |	R wrapper for magic   |	Magic |	python |	finished |
|LightTree          |	create lineage tree from LightNorm output       |	|	R |	stable version, need to correct the blocking function |
|LightDE            |   find significantly variable gene bwteen/across lineage | | R | done |
|LightNet           |	build gene interacion network and identify key gene modules |	|	R |	WCGNA in tree  |
|LightPlotSuite |	Plotting functions | |	R |	Partial finished |
