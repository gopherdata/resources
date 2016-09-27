# Go Data Science Tooling, Packages, Libraries, etc.

This is a curated list of well-maintained and developing tools, packages, libraries, etc. related to doing data science with Go.

[Arithmetic](README.md#arithmetic)  
[Classification](README.md#classification)  
[Clustering](README.md#clustering)  
[CSV](README.md#csv)  
[Distributed Data Analysis/Pipelining](README.md#distributed-data-analysispipelining)  
[General data munging](README.md#general-data-munging)  
[General purpose machine learning](README.md#general-purpose-machine-learning)  
[Graphs](README.md#graphs)  
[JSON](README.md#json)  
[Matrices/Linear Algebra](README.md#matriceslinear-algebra)  
[Neural Networks](README.md#neural-networks)  
[NLP](README.md#nlp)  
[Non-SQL Database Interactions](README.md#non-sql-database-interactions)  
[Plotting/dashboarding](README.md#plottingdashboarding)  
[Probability/statistics/experiments](README.md#probabilitystatisticsexperiments)  
[Regression](README.md#regression)  
[SQL-like Database Interactions](README.md#sql-like-database-interactions)  
[Web Scraping](README.md#web-scraping)  

Also, this space includes a list of proposed packages that would fill certain gaps in the ecosystem or provide enhanced functionality.

[Proposed](README.md#proposed)

## Arithmetic 

- [math](https://golang.org/pkg/math/) - Stdlib math functions.
- [math/cmplx](https://golang.org/pkg/math/cmplx/) - Package cmplx provides basic constants and mathematical functions for complex numbers.
- [github.com/gonum/floats](https://github.com/gonum/floats) - A set of helper routines for dealing with slices of float64.
- [github.com/gonum/optimize](https://github.com/gonum/optimize) - This is an optimization package for the Go language. 

## Classification

- [github.com/jbrukh/bayesian](https://github.com/jbrukh/bayesian) - Naive Bayes classification.
- [github.com/datastream/libsvm](https://github.com/datastream/libsvm) - libsvm golang version derived work based on LIBSVM 3.14.

## Clustering

- [github.com/salkj/kmeans](https://github.com/salkj/kmeans) - A ready-to-use naive kmeans package for Go.

## CSV

- [encoding/csv](https://golang.org/pkg/encoding/csv/) - Stdlib CSV functionality.
- [github.com/go-hep/csvutil](https://github.com/go-hep/csvutil) - A set of types and funcs to deal with CSV data files in a somewhat convenient way.
- [github.com/go-hep/csvutil/tree/master/csvdriver](https://github.com/go-hep/csvutil/tree/master/csvdriver) - A CSV library for `databases/sql`.

## Distributed Data Analysis/Pipelining

- [github.com/pachyderm/pachyderm](https://github.com/pachyderm/pachyderm) - Containerized Data Analytics http://pachyderm.io.
- [github.com/chrislusf/glow](https://github.com/chrislusf/glow) - Glow is an easy-to-use distributed computation system written in Go, similar to Hadoop Map Reduce, Spark, Flink, Storm, etc.
- [github.com/chrislusf/gleam](https://github.com/chrislusf/gleam) - Another go based distributed execution system.
- [github.com/flowbase/flowbase](https://github.com/flowbase/flowbase) - A Flow-based Programming inspired micro-framework for Go (Golang) http://flowbase.org.
- [github.com/scipipe/scipipe](https://github.com/scipipe/scipipe) - A Scientific workflow system written in pure Go (Golang) inspired by Flow-based Programming http://scipipe.org.

## General data munging

- [github.com/kniren/gota](https://github.com/kniren/gota) - Dataframes.
- [github.com/gopherds/gophernotes](https://github.com/gopherds/gophernotes) - Go kernel for Jupyter notebooks.

## General purpose machine learning

- [github.com/chewxy/gorgonia](https://github.com/chewxy/gorgonia) - Provides the necessary primitives for creating and executing neural networks and machine learning algorithms.
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
- [github.com/white-pony/go-fann](https://github.com/white-pony/go-fann) - Go bindings for FANN, a library for artificial neural networks

## NLP

- [github.com/advancedlogic/go-freeling](https://github.com/advancedlogic/go-freeling) - This is a partial port of Freeling 3.1 (http://nlp.lsi.upc.edu/freeling/).
- [github.com/endeveit/enca](https://github.com/endeveit/enca) - This is a minimal cgo bindings for libenca.
- [github.com/Lazin/go-ngram](https://github.com/Lazin/go-ngram) - N-gram index for Go.
- [github.com/reiver/go-porterstemmer](https://github.com/reiver/go-porterstemmer) - A native Go clean room implementation of the Porter Stemming Algorithm.
- [github.com/Rookii/paicehusk](https://github.com/Rookii/paicehusk) - A native Go implementation of the Paice/Husk stemming algorithm
- [github.com/blevesearch/segment](https://github.com/blevesearch/segment) - A Go library for performing Unicode Text Segmentation as described in Unicode Standard Annex #29.
- [https://github.com/kljensen/snowball](https://github.com/kljensen/snowball) - A Go (golang) implementation of the Snowball stemmer for natural language processing.
- [github.com/sajari/word2vec](https://github.com/sajari/word2vec) - word2vec is a Go package which provides functions for querying word2vec models.
- 

## Non-SQL Database Interactions

- [gopkg.in/mgo.v2](https://labix.org/mgo) - mgo (pronounced as mango) is a MongoDB driver for the Go language.
- [github.com/gocql/gocql](https://github.com/gocql/gocql) - A fast and robust Cassandra client for the Go programming language.
- [github.com/go-redis/redis](https://github.com/go-redis/redis) - Redis client for Golang.
- [github.com/garyburd/redigo](https://github.com/garyburd/redigo) - Go client for Redis.
- [github.com/tsuna/gohbase](https://github.com/tsuna/gohbase) - Pure Go HBase client.

## Plotting/dashboarding

- [github.com/gonum/plot](https://github.com/gonum/plot) - An API for building and drawing plots.
- [github.com/gigablah/dashing-go](https://github.com/gigablah/dashing-go) - A port of dashing for real-time dashboarding.

## Probability/statistics/experiments

- [github.com/gonum/stat](https://github.com/gonum/stat) - Statistics package for Go.
- [github.com/montanaflynn/stats](https://github.com/montanaflynn/stats) - A statistics package with common functions that are missing from the Golang standard library.
- [github.com/URXtech/planout-golang](https://github.com/URXtech/planout-golang) - (Multi Variate Testing) Interpreter for Planout code written in Go.
- [github.com/peleteiro/bandit-server](https://github.com/peleteiro/bandit-server) - Bandit-server is a Multi-Armed Bandit api server which needs no configuration neither persistent store.

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

## Web Scraping

- [github.com/yhat/scrape](https://github.com/yhat/scrape) - A simple, higher level interface for Go web scraping.
- [github.com/cathalgarvey/sqrape](https://github.com/cathalgarvey/sqrape) - Simple Query Scraping with CSS and Go Reflection.

## Proposed

  * [ ] Multi-dimensional slices within Go itself ([Proposal](https://github.com/golang/proposal/blob/master/design/6282-table-data.md)).
  * [ ] A robust (and concurrent) package to handle minimizations/fits of data and histograms (gonum/optimize would provide a nice foundation for this).
  * [ ] A robust (and concurrent) package to describe statistical models (Bayesian and frequentist) with many nuisance parameters, etc...
  * [ ] A Go native package for A/B testing.
  * [ ] A database with datalog querying. Inspiration can be drawn from Rich Hickey's [Datomic](http://www.datomic.com) database, but open source.
  * [ ] A datalog query system for distributed computation. Similar to [Cascalog](http://cascalog.org/) for the Hadoop ecosystem, but integrating with some of the Go tools instead.
