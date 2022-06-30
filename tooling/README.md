# Go Data Science Tooling, Packages, Libraries, etc.

This is a curated list of well-maintained and developing tools, packages, libraries, etc. related to doing data science with Go.

- [Arithmetic](README.md#arithmetic)
- [Bioinformatics](README.md#bioinformatics)
- [Classification](README.md#classification)
- [Clustering](README.md#clustering)
- [CSV](README.md#csv)
- [Distributed Data Analysis/Pipelining](README.md#distributed-data-analysispipelining)
- [Geospatial](README.md#geospatial)
- [General data munging](README.md#general-data-munging)
- [General purpose machine learning](README.md#general-purpose-machine-learning)
- [Graphs](README.md#graphs)
- [JSON](README.md#json)
- [I/O](README.md#io)
- [Matrices/Linear Algebra](README.md#matriceslinear-algebra)
- [Neural Networks](README.md#neural-networks)
- [NLP](README.md#nlp)
- [Non-SQL Database Interactions](README.md#non-sql-database-interactions)
- [Parquet](README.md#parquet)
- [Plotting/dashboarding](README.md#plottingdashboarding)
- [Probability/statistics/experiments](README.md#probabilitystatisticsexperiments)
- [Recommendation Systems/Engines](README.md#recommendation-systems)
- [Regression](README.md#regression)
- [SQL-like Database Interactions](README.md#sql-like-database-interactions)
- [Time Series](README.md#time-series)
- [Web Scraping](README.md#web-scraping)

Also, this space includes a list of proposed packages that would fill certain gaps in the ecosystem or provide enhanced functionality.

[Proposed](README.md#proposed)

## Arithmetic

- [math](https://golang.org/pkg/math/) - Stdlib math functions.
- [math/cmplx](https://golang.org/pkg/math/cmplx/) - Package cmplx provides basic constants and mathematical functions for complex numbers.
- [gonum.org/v1/gonum/floats](https://godoc.org/gonum.org/v1/gonum/floats) - A set of helper routines for dealing with slices of float64.
- [gonum.org/v1/gonum/optimize](https://godoc.org/gonum.org/v1/gonum/optimize) - This is an optimization package for the Go language.
- [go-hep.org/x/hep/fit](https://go-hep.org/x/hep/fit) - a WIP package to provide easy fitting models and curve fitting functions.

## Bioinformatics

- [github.com/biogo](https://github.com/biogo) - a bioinformatics library collection for Go
- [github.com/ExaScience/elprep](https://github.com/ExaScience/elprep) - a high-performance tool for preparing sequence alignment/map files in sequencing pipelines
- [github.com/MG-RAST/AWE](https://github.com/MG-RAST/AWE) - a workload management system for bioinformatic workflow applications.
- [github.com/kelvins/chronobiology](https://github.com/kelvins/chronobiology) - Go package that provides functions for the study of biological temporal rhythms.

## Classification

- [github.com/jbrukh/bayesian](https://github.com/jbrukh/bayesian) - Naive Bayes classification.
- [github.com/datastream/libsvm](https://github.com/datastream/libsvm) - libsvm golang version derived work based on LIBSVM 3.14.
- [github.com/barnjamin/randomforest](https://github.com/barnjamin/randomforest) - Random Forest classification
- [github.com/rikonor/go-ann](https://github.com/rikonor/go-ann) - Approximate k-Nearest Neighbor search.

## Clustering

- [github.com/salkj/kmeans](https://github.com/salkj/kmeans) - A ready-to-use naive kmeans package for Go.
- [github.com/mpraski/clusters](https://github.com/mpraski/clusters) - Go implementations of several clustering algoritms (k-means++, DBSCAN, OPTICS), as well as utilities for importing data and estimating optimal number of clusters.

## CSV

- [encoding/csv](https://golang.org/pkg/encoding/csv/) - Stdlib CSV functionality.
- [go-hep.org/x/hep/csvutil](https:///go-hep.org/x/hep/csvutil) - A set of types and funcs to deal with CSV data files in a somewhat convenient way.
- [go-hep.org/x/hep/csvutil/csvdriver](https://go-hep.org/x/hep/csvutil/csvdriver) - A CSV library for `databases/sql`.
- [github.com/dinedal/textql](https://github.com/dinedal/textql) - Execute SQL against structured text like CSV or TSV.
- [github.com/shuLhan/dsv](https://github.com/shuLhan/dsv) - The Go library for working with delimited separated value (DSV).
- [github.com/frictionlessdata/tableschema-go](github.com/frictionlessdata/tableschema-go) - [Schema](https://github.com/danielfireman/resources) inference and table-based tooling (e.g., for working with CSV).
- [github.com/j0hnsmith/csvplus](https://github.com/j0hnsmith/csvplus) CSV data to/from slices of structs (with types).

## Distributed Data Analysis/Pipelining

- [github.com/pachyderm/pachyderm](https://github.com/pachyderm/pachyderm) - Distributed data pipelining and data versioning built on containers http://pachyderm.io.
- [github.com/chrislusf/glow](https://github.com/chrislusf/glow) - Glow is an easy-to-use distributed computation system written in Go, similar to Hadoop Map Reduce, Spark, Flink, Storm, etc.
- [github.com/chrislusf/gleam](https://github.com/chrislusf/gleam) - Another go based distributed execution system.
- [github.com/flowbase/flowbase](https://github.com/flowbase/flowbase) - A Flow-based Programming inspired micro-framework for Go (Golang) http://flowbase.org.
- [github.com/ExaScience/pargo](https://github.com/ExaScience/pargo) - Provides functions and data structures for expressing parallel algorithms in Go
- [github.com/scipipe/scipipe](https://github.com/scipipe/scipipe) - A Scientific workflow system written in pure Go (Golang) inspired by Flow-based Programming http://scipipe.org.
- [github.com/matryer/vice](https://github.com/matryer/vice) - Go channels at horizontal scale (powered by message queues).

## Geospatial

- [github.com/golang/geo](https://github.com/golang/geo) - S2 geometry library in Go
- [github.com/twpayne/go-geom](https://github.com/twpayne/go-geom) - Efficient geometry types, encoding and decoding (GeoJSON, IGC, KML, WKB, WKT), and 2D geometry functions.
- [github.com/twpayne/go-gpx](https://github.com/twpayne/go-gpx) - Read and write GPX documents
- [github.com/twpayne/go-kml](https://github.com/twpayne/go-kml) - Convenience methods for creating and writing KML documents
- [github.com/twpayne/go-polyline](https://github.com/twpayne/go-polyline) - Google Maps Polyline encoding and decoding

## General data munging

- [github.com/elves/elvish](https://github.com/elves/elvish) - A shell (bash alternative) supporting working with pipelines of structured objects - not just text - and a more natural scripting syntax.
- [github.com/kniren/gota](https://github.com/kniren/gota) - Dataframes.
- [github.com/Shixzie/ly](https://github.com/Shixzie/ly) - A very flexible and easy to use pkg to work with DataFrames aimed at ML.
- [github.com/gopherdata/gophernotes](https://github.com/gopherdata/gophernotes) - Go kernel for Jupyter notebooks.
- [github.com/kevinschoon/fit](https://github.com/kevinschoon/fit) - Toolkit for exploring and manipulating datasets.
- [github.com/shuLhan/tabula](https://github.com/shuLhan/tabula) - a Go library for working with rows, columns, or matrix (table), or in another terms working with dataset.
- [neugram.io](https://neugram.io) - a programming language written in Go, designed for data munging.

## General purpose machine learning

- [github.com/chewxy/gorgonia](https://github.com/chewxy/gorgonia) - Provides the necessary primitives for creating and executing neural networks and machine learning algorithms.
- [github.com/sjwhitworth/golearn](https://github.com/sjwhitworth/golearn) - GoLearn is a 'batteries included' machine learning library for Go.
- [github.com/cdipaolo/goml](https://github.com/cdipaolo/goml) - `goml` is a machine learning library written entirely in Golang which lets the average developer include machine learning into their applications.
- [github.com/xlvector/hector](https://github.com/xlvector/hector) - Golang machine learning lib. Currently, it can be used to solve binary classification problems.
- [github.com/shuLhan/go-mining](https://github.com/shuLhan/go-mining) - Small Golang library that contains classifiers (CART, Random Forest, Cascaded Random Forest, and KNN) and resampling (SMOTE and LN-SMOTE).
- [github.com/galeone/tfgo](https://github.com/galeone/tfgo) - Tensorflow + Go, the gopher way.
- [github.com/ctava/tfcgo](https://github.com/ctava/tfcgo) - Bridging the gap between go and the Tensorflow c++ framework.
- [github.com/pa-m/sklearn](https://github.com/pa-m/sklearn) - (WIP) port of bits of sklearn to Go.

## Graphs

- [github.com/dgraph-io/dgraph](https://github.com/dgraph-io/dgraph) - Fast, Distributed Graph Database [dgraph.io](https://dgraph.io)
- [github.com/gyuho/goraph](https://github.com/gyuho/goraph) - Package goraph implements graph data structure and algorithms.
- [gonum.org/v1/gonum/graph](https://godoc.org/gonum.org/v1/gonumgraph) - This is a generalized graph package for the Go language.
- [github.com/cayleygraph/cayley](https://github.com/cayleygraph/cayley) - Cayley is an open-source graph inspired by the graph database behind Freebase and Google's Knowledge Graph.

## JSON

- [encoding/json](https://golang.org/pkg/encoding/json/) - Stdlib json functionality.
- [github.com/tidwall/gjson](https://github.com/tidwall/gjson) - A Go package the provides a very fast and simple way to get a value from a json document.
- [github.com/pquerna/ffjson](https://github.com/pquerna/ffjson) - ffjson generates static MarshalJSON and UnmarshalJSON functions for structures in Go.

## I/O

- [gonum.org/v1/hdf5](https://godoc.org/gonum.org/v1/hdf5) - CGo bindings to `HDF5`.
- [github.com/sbinet/npyio](https://github.com/sbinet/npyio) - Read/Write access to `.npy` data files.
- [github.com/sbinet/go-arff](https://github.com/sbinet/go-arff) - Read/Write access to `ARFF` data files.

## Matrices/Arrays/Linear Algebra

- [gonum.org/v1/gonum/lapack](https://godoc.org/gonum.org/v1/gonum/lapack) - A collection of packages to provide LAPACK functionality for the Go programming language.
- [gonum.org/v1/gonum/blas](https://godoc.org/gonum.org/v1/gonum/blas) - A collection of packages to provide BLAS functionality for the Go.
- [gonum.org/v1/gonum/mat](https://godoc.org/gonum.org/v1/gonum/mat) - This is a matrix package for the Go language.
- [github.com/akualab/narray](https://github.com/akualab/narray) - A multidimensional array package optimized with Go assemby.

## Neural Networks

- [github.com/tleyden/neurgo](https://github.com/tleyden/neurgo) - Neural Network toolkit in Go.
- [github.com/fxsjy/gonn](https://github.com/fxsjy/gonn) - GoNN is an implementation of Neural Network in Go Language, which includes BPNN, RBF, PCN.
- [github.com/NOX73/go-neural](https://github.com/NOX73/go-neural) - Neural network implementation on golang.
- [github.com/milosgajdos83/gosom](https://github.com/milosgajdos83/gosom) - Self-organizing maps in Go
- [github.com/made2591/go-perceptron-go](https://github.com/made2591/go-perceptron-go) - A single level perceptron classifier.

## NLP

- [github.com/advancedlogic/go-freeling](https://github.com/advancedlogic/go-freeling) - This is a partial port of Freeling 3.1 (http://nlp.lsi.upc.edu/freeling/).
- [github.com/endeveit/enca](https://github.com/endeveit/enca) - This is a minimal cgo bindings for libenca.
- [github.com/Lazin/go-ngram](https://github.com/Lazin/go-ngram) - N-gram index for Go.
- [github.com/reiver/go-porterstemmer](https://github.com/reiver/go-porterstemmer) - A native Go clean room implementation of the Porter Stemming Algorithm.
- [github.com/blevesearch/segment](https://github.com/blevesearch/segment) - A Go library for performing Unicode Text Segmentation as described in Unicode Standard Annex #29.
- [github.com/cdipaolo/sentiment](https://github.com/cdipaolo/sentiment) - Simple, Drop In Sentiment Analysis in Golang.
- [https://github.com/kljensen/snowball](https://github.com/kljensen/snowball) - A Go (golang) implementation of the Snowball stemmer for natural language processing.
- [github.com/sajari/word2vec](https://github.com/sajari/word2vec) - word2vec is a Go package which provides functions for querying word2vec models.
- [github.com/jlubawy/go-gcnl](https://github.com/jlubawy/go-gcnl) - This package can be used to easily access the Google Cloud Natural Language API.
- [github.com/olebedev/when](https://github.com/olebedev/when) - A natural language date/time parser with pluggable rules.
- [github.com/kampsy/gwizo](https://github.com/kampsy/gwizo) - Simple Go implementation of the Porter Stemmer algorithm with powerful features.
- [github.com/Shixzie/nlp](https://github.com/Shixzie/nlp) - General purpose any-lang Natural Language Processor that parses the data inside a text and returns a filled model.
- [github.com/abadojack/whatlanggo](https://github.com/abadojack/whatlanggo) - Natural language detection for Go.
- [github.com/ynqa/word-embedding](https://github.com/ynqa/word-embedding) - Word Embeddings: the full implementation of word2vec, GloVe in Go
- [https://github.com/jdkato/prose](https://github.com/jdkato/prose) - prose is a library written in pure Go that supports tokenization, segmentation, part-of-speech tagging, and named-entity extraction.

## Non-SQL Database Interactions

- [gopkg.in/mgo.v2](https://labix.org/mgo) - mgo (pronounced as mango) is a MongoDB driver for the Go language.
- [github.com/gocql/gocql](https://github.com/gocql/gocql) - A fast and robust Cassandra client for the Go programming language.
- [github.com/go-redis/redis](https://github.com/go-redis/redis) - Redis client for Golang.
- [github.com/garyburd/redigo](https://github.com/garyburd/redigo) - Go client for Redis.
- [github.com/tsuna/gohbase](https://github.com/tsuna/gohbase) - Pure Go HBase client.
- [github.com/colinmarc/hdfs](https://github.com/colinmarc/hdfs) - Pure Go HDFS client.

## Parquet

- [github.com/xitongsys/parquet-go](https://github.com/xitongsys/parquet-go) - Go version of Read/Write parquet file.

## Plotting/dashboarding

- [gonum.org/v1/plot](https://godoc.org/gonum.org/v1/plot) - An API for building and drawing plots.
- [github.com/gigablah/dashing-go](https://github.com/gigablah/dashing-go) - A port of dashing for real-time dashboarding.
- [github.com/mmcloughlin/globe](https://github.com/mmcloughlin/globe) - Globe wireframe visualizations.
- [github.com/ajstarks/svgo](https://github.com/ajstarks/svgo) - Go Language Library for SVG generation.

## Probability/statistics/experiments

- [gonum.org/v1/gonum/stat](https://godoc.org/gonum.org/v1/gonum/stat) - Statistics package for Go.
- [github.com/montanaflynn/stats](https://github.com/montanaflynn/stats) - A statistics package with common functions that are missing from the Golang standard library.
- [github.com/URXtech/planout-golang](https://github.com/URXtech/planout-golang) - (Multi Variate Testing) Interpreter for Planout code written in Go.
- [github.com/peleteiro/bandit-server](https://github.com/peleteiro/bandit-server) - Bandit-server is a Multi-Armed Bandit api server which needs no configuration neither persistent store.
- [github.com/dgryski/go-topk](https://github.com/dgryski/go-topk) - A "filtered space saving" streaming topk algorithm.
- [github.com/dgryski/go-kll](https://github.com/dgryski/go-kll) - An implementation of KLL sketch for "Almost Optimal Streaming Quantiles."
- [github.com/dgryski/go-linlog](https://github.com/dgryski/go-linlog) - Linear-log bucketing and histograms.
- [github.com/dgryski/go-rbo](https://github.com/dgryski/go-rbo) - Computes the rank-biased overlap for two sorted result sets.

## Recommendation Systems

- [github.com/jbochi/facts](https://github.com/jbochi/facts) - Matrix Factorization based recsys in Golang. Because facts are more important than ever.
- [github.com/rlouf/birdland](https://github.com/rlouf/birdland) - A battle-tested recommendation library written in Go.

## Regression

- [github.com/sajari/regression](https://github.com/sajari/regression) - Multivariable linear regression.
- [github.com/glycerine/zettalm](https://github.com/glycerine/zettalm) - Go code to build linear regression models on zettabytes of data.

## SQL-like Database Interactions

- [databases/sql](https://golang.org/pkg/database/sql/) - Package sql provides a generic interface around SQL (or SQL-like) databases.
- [github.com/Boostport/avatica](https://github.com/Boostport/avatica) - Apache Phoenix/Avatica driver for Go's `database/sql` package.
- [github.com/lib/pq](https://github.com/lib/pq) - A pure Go postgres driver for Go's `database/sql` package.
- [github.com/go-pg/pg](https://github.com/go-pg/pg) - Fast PostgreSQL client and ORM.
- [github.com/jackc/pgx](https://github.com/jackc/pgx) - A pure Go PostgreSQL driver that offers performance gains and more features while remaining `database/sql` compatible.
- [github.com/go-sql-driver/mysql](https://github.com/go-sql-driver/mysql) - A MySQL-Driver for Go's `database/sql` package.
- [github.com/mattn/go-sqlite3](https://github.com/mattn/go-sqlite3) - sqlite3 driver conforming to the built-in `database/sql` interface.
- [github.com/lukasmartinelli/pgclimb](https://github.com/lukasmartinelli/pgclimb) - Export data from PostgreSQL into different data formats (JSON, JSON Lines, CSV, XLSX, XML) or use a Golang templates
- [github.com/lukasmartinelli/pgfutter](https://github.com/lukasmartinelli/pgfutter) - Import CSV and JSON into PostgreSQL the easy way
- [github.com/omniscale/imposm3](https://github.com/omniscale/imposm3) - Import OpenStreetMap data into PostgreSQL/PostGIS database

## Time Series

- [github.com/influxdata/influxdb](https://github.com/influxdata/influxdb) - an open source time series database.
- [github.com/dgryski/go-holtwinters](https://github.com/dgryski/go-holtwinters) - An implementation of Holt-Winters forecasting.
- [github.com/dgryski/go-tsz](https://github.com/dgryski/go-tsz) - A time series compression algorithm from Facebook's Gorilla paper.
- [github.com/dgryski/go-timewindow](https://github.com/dgryski/go-timewindow) - Counters over sliding windows.

## Web Scraping

- [github.com/yhat/scrape](https://github.com/yhat/scrape) - A simple, higher level interface for Go web scraping.
- [github.com/cathalgarvey/sqrape](https://github.com/cathalgarvey/sqrape) - Simple Query Scraping with CSS and Go Reflection.
- [github.com/PuerkitoBio/goquery](https://github.com/PuerkitoBio/goquery) - Gives you easy access to the HTML structure of a page and enables you to pick which elements you want to access by attribute or content.
- [github.com/anaskhan96/soup](https://github.com/anaskhan96/soup) - soup is a small web scraper package for Go, with its interface highly similar to that of BeautifulSoup.
- [github.com/schollz/linkcrawler](https://github.com/schollz/linkcrawler) - Cross-platform persistent and distributed web crawler

## Proposed

  * [ ] Multi-dimensional slices within Go itself ([Proposal](https://github.com/golang/proposal/blob/master/design/6282-table-data.md)).
  * [ ] A robust (and concurrent) package to handle minimizations/fits of data and histograms (gonum/optimize would provide a nice foundation for this).
  * [ ] A robust (and concurrent) package to describe statistical models (Bayesian and frequentist) with many nuisance parameters, etc...
  * [ ] A Go native package for A/B testing.
  * [ ] A database with datalog querying. Inspiration can be drawn from Rich Hickey's [Datomic](http://www.datomic.com) database, but open source.
  * [ ] A datalog query system for distributed computation. Similar to [Cascalog](http://cascalog.org/) for the Hadoop ecosystem, but integrating with some of the Go tools instead.
