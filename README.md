# aitoa-data

## 1. Introduction

This repository holds the experimental result data used in the book "[An Introduction to Optimization Algorithms](http://thomasweise.github.io/aitoa/index.html)".
With this data, in conjunction with the R scripts in [thomasWeise/aitoaEvaluate](http://github.com/thomasWeise/aitoaEvaluate), you can generate most of the diagrams and charts in the book.

## 2. Contents

The results are provided as the raw log files packaged into `tar.xz` archives.
The following result data sets are available for the Job-Shop Scheduling (JSSP) Experiment:

|file|download size|size unpacked|description|
|--:|--:|--:|:--|
|[rs.tar.xz](jssp/rs.tar.xz)|2.4&nbsp;MiB|17.3&nbsp;MiB|Random Sampling|
|[hc.tar.xz](jssp/hc.tar.xz)|27.4&nbsp;MiB|241.5&nbsp;MiB|Hill Climber w/o Restarts|
|[ea.tar.xz](jssp/ea.tar.xz)|83.8&nbsp;MiB|680.2&nbsp;MiB|Evolutionary Algorithm w/o Crossover|
|[eac.tar.xz](jssp/eac.tar.xz)|47.9&nbsp;MiB|360.0&nbsp;MiB|Evolutionary Algorithm with Clearing|
|[sa.tar.xz](jssp/sa.tar.xz)|11.9&nbsp;MiB|96.3&nbsp;MiB|Simulated Annealing|
|[hc2.tar.xz](jssp/hc2.tar.xz)|7.2&nbsp;MiB|56.3&nbsp;MiB|Hill Climber 2 w/o Restarts|
|[ma.tar.xz](jssp/ma.tar.xz)|17.9&nbsp;MiB|142.0&nbsp;MiB|Memetic Algorithm based on `hc2`|
|[umda.tar.xz](jssp/umda.tar.xz)|27.7&nbsp;MiB|224.1&nbsp;MiB|UMDA-style Estimation of Distribution Algorithm|

## 3. License

The book and this data set here are released under the Attribution-NonCommercial-ShareAlike 4.0 International license (CC&nbsp;BY&#8209;NC&#8209;SA&nbsp;4.0), see [http://creativecommons.org/licenses/by-nc-sa/4.0/](http://creativecommons.org/licenses/by-nc-sa/4.0/) for a summary.
The experiments have been conducted using the Java programs published in repository [thomasWeise/aitoa-code](http://github.com/thomasWeise/aitoa-code), which is licensed under the MIT License.
Many of the graphics and diagrams in the book have been created based on the data published in this repository using the `R` scripts in  [thomasWeise/aitoaEvaluate](http://github.com/thomasWeise/aitoaEvaluate), which are the MIT License, too.

## 4. Contact

If you have any questions or suggestions, please contact
[Prof. Dr. Thomas Weise](http://iao.hfuu.edu.cn/team/director) of the
[Institute of Applied Optimization](http://iao.hfuu.edu.cn/) at
[Hefei University](http://www.hfuu.edu.cn) in
Hefei, Anhui, China via
email to [tweise@hfuu.edu.cn](mailto:tweise@hfuu.edu.cn) with CC to [tweise@ustc.edu.cn](mailto:tweise@ustc.edu.cn).

