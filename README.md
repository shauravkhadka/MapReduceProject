# MapReduce Project

This project implements a simple MapReduce program in Java using Apache Hadoop. It reads user ratings for movies from an input file, tokenizes each line based on tab separation, emits key-value pairs where the key is the rating, and the value is 1. Then, it sums up the counts of each rating using the reducer.

## Files

- `RatingMapper.java`: Mapper class to tokenize input lines and emit key-value pairs.
- `RatingReducer.java`: Reducer class to sum up the counts of each rating.
- `Main.java`: Main class to configure and run the MapReduce job.

## Instructions

1. Compile the Java code using `javac`.
2. Run the MapReduce program using Hadoop with the input and output directories.
3. Collect the output file containing each rating and its corresponding count.

## Usage

```bash
hadoop jar MapReduceProject.jar Main input output
