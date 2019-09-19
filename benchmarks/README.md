# Benchmarks

This folder will contain benchmarks for different steps of single-cell scRNA-seq tools. Benchmarks will be presented in jupyter notebooks.

### Benchmarks must contain evaluations of:
1. Time
2. Memory usage
3. Accuracy
4. Errors

### Fairness rules (under construction...):
1. Comparisons of tools between default and non-default parametrizations is not fair.
2. Tools should be compared on at least 2 real datasets with different structure.
3. All tools have limitations, these should be uncovered in the benchmark (no tools with 100% scores on all metrics)
4. Benchmarks should be reproducible.
5. Ultimate judgement of benchmarking quality will be made by a core member.