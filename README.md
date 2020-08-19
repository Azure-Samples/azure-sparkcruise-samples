# SparkCruise

SparkCruise is an automatic computation reuse system developed for Spark. It can automatically detect overlapping computations in the past query workload and enable automatic materialization and reuse in future Spark SQL queries.

## Getting Started

### Prerequisites

- Query workload

### Installation

HDInsight clusters are pre-installed with SparkCruise library and configuration options.

### Quickstart

Please refer to the detailed documentation [here](https://docs.microsoft.com/en-us/azure/hdinsight/spark/spark-cruise).

We have also developed Workload Insights Notebook (WIN) to help users derive insights from their query workloads. To use WIN run the analyze command - `sudo /opt/peregrine/analyze/peregrine.sh analyze`
and then import the notebook [(available here)](SparkCruise/WorkloadInsights_HDI_v0.4.ipynb) in Jupyter.

## Demo

[SparkCruise and Workload Insights Notebook Demo](https://databricks.com/session_na20/sparkcruise-automatic-computation-reuse-in-apache-spark) at Spark+AI Summit 2020.

## Resources

- [SparkCruise: Handsfree Computation Reuse in Spark. VLDB 2019](https://people.cs.umass.edu/~aroy/sparkcruise-vldb19.pdf).
