# Research Project - A Computational Comparison of Sorting Algorithms
Capstone Research Project - A Computational Comparison of Sorting Algorithms

Report: https://github.com/AyushGupta51379/Research_A_Computational_Comparison_of_Sorting_Algorithms/blob/master/FinalReport.pdf
Presentation: https://github.com/AyushGupta51379/Research_A_Computational_Comparison_of_Sorting_Algorithms/blob/master/FINAL_PRESENTATION.pdf

# Abstract

Sorting algorithms are used to sort data into order. Previous researchers have used asymptotic analysis method and considered worst running time of algorithms for comparison of sorting algorithms. This project used practical cases and considered average running time of algorithms for comparing four sorting algorithms, namely, Bubble sort, Insertion sort, Merge sort and Quick sort. The purpose of this project was to find out the difference in practical method and theoretical method of comparing sorting algorithms. Based on
the results from this project, the practical method of comparison offers more insights on comparing sorting algorithms. In this research, Merge sort is found to be the best sorting algorithm considering the average number of operations for comparison. Further research can be done on comparing other algorithms using the practical method of comparison from this research. The results of this project have applications in computer science, engineering, finance and economics.

# 5 Conclusion

## 5.1 Brief summary
This project practically computed the average running time of Bubble sort, Insertion sort, Merge sort and Quick sort sorting algorithms for different input sizes ranging from 100 to 1 million. The results of this project show that by comparing the algorithms in the practical case of finite input size and average running time, we can get better insights on which algorithm is better. The results are more detailed than the theoretical case of n tending to infinity and worst running time. For example, while considering the number of operations as the running time for comparison of algorithms, Insertion sort seems twice as better than Bubble sort, Merge sort seems better than Quick sort, Merge sort and Quick sort seem much better than Bubble sort and Insertion sort. Among Bubble sort, Insertion sort, Merge sort and Quick sort sorting algorithms, Merge sort seems to be the best in terms of number of operations needed to sort elements. However, it must be noted that these results are valid on the data sets randomly generated in this project and the results may vary based on the data needed to be sorted. However, the number of operations being a mathematical method independent of the machine used for sorting, should offer more stability in results than considering the CPU time. Overall, more insights can be obtained from the practical method used in this project to computationally compare sorting algorithms considering average case than the theoretical method of Asymptotic analysis considering the worst case used in researches in this field [3].
## 5.2 Limitations 
There can be other case specific ways to implement algorithms which would affect their running time. Similarly, there can be different results obtained based on the type of data, for example if the data is already well sorted or sorted in parts, then Insertion sort might work much better than the other three algorithms considered in this project. Due to this, python uses Timsort
sorting algorithm as default, which is a combination of Merge sort and Insertion sort sorting algorithms [7].

In some cases, parameters other than number of operations can also matter, for example, the space complexity or the space needed by an algorithm. If the space complexity matters more than number of operations in some projects, then Quick sort is considered better than Merge sort by previous researchers [5].
## 5.3 Future implications
Based on the results from this project, if we just consider the number of operations for comparing sorting algorithms then among the 4 sorting algorithms, the increasing order of performance is Bubble sort, Insertion sort, Quick sort and Merge sort, with Merge sort found to be the best
sorting algorithm. 

In future, the method of computational comparison of algorithms used by this research can be used to compare other algorithms and provide a better understanding of the differences in performances of algorithms.

# Acknowledgements:

Part of this work was done by the author (Ayush GUPTA) at the course "Capstone Projects in Applied Mathematics" at The Hong Kong University of Science and Technology (HKUST) supervised by Prof. Shingyu Leung and Dr. Yin Bon Ku.

# References

[1] https://www8.cs.umu.se/kurser/TDBA77/VT06/algorithms/BOOK/BOOK/NODE30.HTM

[2] K. Ali, A Comparative Study of Well Known Sorting Algorithms, Retrieved from http:
//www.ijarcs.info/index.php/Ijarcs/article/view/2903/2886

[3] T. H. Cormen, C. E. Leiserson, R. L. Rivest, & C. Stein, Introduction to Algorithms, Third Edition, The MIT Press, 2009.

[4] https://www.geeksforgeeks.org/bubble-sort/

[5] https://www.geeksforgeeks.org/quick-sort-vs-merge-sort/

[6] https://www.geeksforgeeks.org/sorting-algorithms/

[7] https://www.geeksforgeeks.org/timsort/
