# PySpark MapReduce Lab for Distributed Systems

This repository contains materials for a hands-on lab demonstrating MapReduce concepts using PySpark, designed for a distributed systems course.

## Prerequisites

Before running the lab examples, you'll need to install:

1. **Python** (3.7 or higher recommended)
2. **Java** (8 or higher required for Spark)
   - Verify with: `java -version`

## Installation

1. **Install PySpark** using pip:
   ```bash
   pip install pyspark
   ```

2. **Verify installation** by running Python and importing PySpark:
   ```python
   from pyspark import SparkContext
   ```

## For Windows Users

Windows users may need some additional setup:
- Install a Java JDK and set `JAVA_HOME` environment variable
- You may need to add Hadoop winutils for some features (not required for basic examples)

## Repository Contents

- `pyspark_mapreduce_lab.py` - Main lab script with complete examples
- `README.md` - This file
- Additional materials and documentation

## Running the Lab Example

1. Clone this repository:
   ```bash
   git clone https://github.com/aysegulrana/mapreduce-pyspark-lab.git
   cd mapreduce-pyspark-lab
   ```

2. Run the main lab examples:
   ```bash
   python mapreduce-pyspark-lab.ipynb
   ```

There is a function to generate sample data within the notebook.

## Lab Structure

The provided code demonstrates:
- Basic PySpark setup
- MapReduce implementation of word count
- Performance comparison with single-machine processing
- Data partitioning concepts
- Effect of partition size on performance

## Troubleshooting

- **Java issues**: Ensure you have Java installed and `JAVA_HOME` is correctly set
- **Memory errors**: Try reducing the size of the generated sample data
- **Performance**: For single-machine testing, ensure you have at least 4GB of RAM available

## Resources

- [Apache Spark Documentation](https://spark.apache.org/docs/latest/)
- [PySpark API Reference](https://spark.apache.org/docs/latest/api/python/index.html)
