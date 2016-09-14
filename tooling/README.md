# Go Data Science Tooling, Packages, Libraries, etc.

This is a curated list of well-maintained and actively developing tools, packages, libraries, etc. related to doing data science with Go.

[Classification](README.md#classification)
[Clustering](README.md#clustering)  
[CSV](README.md#csv)  
[General data munging](README.md#general-data-munging)  
[General purpose machine learning](README.md#general-purpose-machine-learning)  
[Graphs](README.md#graphs)  
[JSON](README.md#json)  
[Matrices/Linear Algebra](README.md#matriceslinear-algebra)
[Neural Networks](README.md#neural-networks)  
[NLP](README.md#nlp)  
[Plotting/dashboarding](README.md#plottingdashboarding)  
[Probability/statistics](README.md#probabilitystatistics)  
[Regression](README.md#regression)
[Web Scraping](README.md#web-scraping)  

## Classification

- [github.com/jbrukh/bayesian](https://github.com/jbrukh/bayesian) - Naive Bayes classification.
- [github.com/datastream/libsvm](https://github.com/datastream/libsvm) - libsvm golang version derived work based on LIBSVM 3.14.

## Clustering

- [github.com/salkj/kmeans](https://github.com/salkj/kmeans) - A ready-to-use naive kmeans package for Go.

## CSV

- [encoding/csv](https://golang.org/pkg/encoding/csv/) - Stdlib CSV functionality.
- [github.com/go-hep/csvutil](https://github.com/go-hep/csvutil) - A set of types and funcs to deal with CSV data files in a somewhat convenient way.
- [github.com/go-hep/csvutil/tree/master/csvdriver](https://github.com/go-hep/csvutil/tree/master/csvdriver) - A CSV library for `databases/sql`.

## General data munging

- [github.com/kniren/gota](https://github.com/kniren/gota) - Dataframes.

## General purpose machine learning

- [github.com/sjwhitworth/golearn](https://github.com/sjwhitworth/golearn) - GoLearn is a 'batteries included' machine learning library for Go.
- [github.com/cdipaolo/goml](https://github.com/cdipaolo/goml) - `goml` is a machine learning library written entirely in Golang which lets the average developer include machine learning into their applications.
- [github.com/xlvector/hector](https://github.com/xlvector/hector) - Golang machine learning lib. Currently, it can be used to solve binary classification problems. 

## Graphs

- [github.com/gyuho/goraph](https://github.com/gyuho/goraph) - Package goraph implements graph data structure and algorithms.
- [github.com/gonum/graph](https://github.com/gonum/graph) - This is a generalized graph package for the Go language.
- [github.com/cayleygraph/cayley](https://github.com/cayleygraph/cayley) - Cayley is an open-source graph inspired by the graph database behind Freebase and Google's Knowledge Graph.

## JSON

- [encoding/json](https://golang.org/pkg/encoding/json/) - Stdlib json functionality.
- [github.com/tidwall/gjson](https://github.com/tidwall/gjson) - A Go package the provides a very fast and simple way to get a value from a json document.
- [github.com/pquerna/ffjson](https://github.com/pquerna/ffjson) - ffjson generates static MarshalJSON and UnmarshalJSON functions for structures in Go. 

## Matrices/Linear Algebra

- [github.com/gonum/lapack](https://github.com/gonum/lapack) - A collection of packages to provide LAPACK functionality for the Go programming language.
- [github.com/gonum/blas](https://github.com/gonum/blas) - A collection of packages to provide BLAS functionality for the Go.
- [github.com/gonum/matrix](https://github.com/gonum/matrix) - This is a matrix package for the Go language.

## Neural Networks

- [github.com/tleyden/neurgo](https://github.com/tleyden/neurgo) - Neural Network toolkit in Go.
- [github.com/fxsjy/gonn](https://github.com/fxsjy/gonn) - GoNN is an implementation of Neural Network in Go Language, which includes BPNN, RBF, PCN.
- [github.com/NOX73/go-neural](https://github.com/NOX73/go-neural) - Neural network implementation on golang.

## NLP

- [github.com/advancedlogic/go-freeling](https://github.com/advancedlogic/go-freeling) - This is a partial port of Freeling 3.1 (http://nlp.lsi.upc.edu/freeling/).
- [github.com/endeveit/enca](https://github.com/endeveit/enca) - This is a minimal cgo bindings for libenca.
- [github.com/Lazin/go-ngram](https://github.com/Lazin/go-ngram) - N-gram index for Go.
- [github.com/reiver/go-porterstemmer](https://github.com/reiver/go-porterstemmer) - A native Go clean room implementation of the Porter Stemming Algorithm.
- [github.com/blevesearch/segment](https://github.com/blevesearch/segment) - A Go library for performing Unicode Text Segmentation as described in Unicode Standard Annex #29.
- [https://github.com/kljensen/snowball](https://github.com/kljensen/snowball) - A Go (golang) implementation of the Snowball stemmer for natural language processing.

## Plotting/dashboarding

- [github.com/gonum/plot](https://github.com/gonum/plot) - An API for building and drawing plots.
- [github.com/gigablah/dashing-go](https://github.com/gigablah/dashing-go) - A port of dashing for real-time dashboarding.

## Probability/statistics

- [github.com/gonum/stat](https://github.com/gonum/stat) - Statistics package for Go.
- [github.com/montanaflynn/stats](https://github.com/montanaflynn/stats) - A statistics package with common functions that are missing from the Golang standard library.

## Regression

- [github.com/sajari/regression](https://github.com/sajari/regression) - Multivariable linear regression.
- [github.com/glycerine/zettalm](https://github.com/glycerine/zettalm) - Go code to build linear regression models on zettabytes of data.

## Web Scraping

- [github.com/yhat/scrape](https://github.com/yhat/scrape) - A simple, higher level interface for Go web scraping.
- [github.com/cathalgarvey/sqrape](https://github.com/cathalgarvey/sqrape) - Simple Query Scraping with CSS and Go Reflection.
