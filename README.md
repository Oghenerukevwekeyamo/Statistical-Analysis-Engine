# Statistical-Analysis-Engine with Numpy
This project experiments the performance differences between loop-based and vectorized implementations of common statistical operations using Numpy, with a focus on 1D and 2D arrays.

This project was created to learn more on vectorization and understand the conditions involved when vectorized Numpy operations outperform traditional Python loops and when they do not. Each statistical operation was implemented twice; using Python loops and using Numpy vectorized operations. Execution time was measured using Jupyter's '%timeit' to compare performance.


## Features
- Mean and median calculation
- Variance computation
- Minimum and Maximum value computation
- Loop-based vs vectorized performance comparison
- Support for both 1D and 2D arrays


## Technologies
- Python
- Numpy
- Jupyter Notebook


## Performance Findings
- For small 1D datasets, loop-based implementations performed almost equivalently or slightly faster due to lower overhead.
- For 2D arrays, the performance gap was more visible as vectorized Numpy operations performed significantly better in terms of performance and lower execution time.


## What I learned
- Vectorization is not always faster for small datasets.
- Vectorization saves a lot of time compared to loops and mastering it will be valuable in the long run.
