# Control Charts for Statistical Process Control

Control charts are graphs that represent the evolution of certain quantities associated with the variables of a process over time. They are a statistical process control tool typically used to monitor the quality of an industrial process and determine whether it is under control. To do this, we use statistical techniques to set upper and lower control limits for each observation.

Sometimes, we perform individual measurements and work directly with the sequence of data obtained. However, it may also be convenient to collect the data in small batches known as rational subgroups. Within each rational subgroup, we have a small number of measurements obtained under essentially the same conditions and the observed variation is due to random effects only. In this way, we have more robust information about the process mean and dispersion.

There are numerous types of control charts depending on the statistics that we wish to represent. Among others:

- Control charts for continuous data, when we wish to monitor the process mean and dispersion

- Control charts for attributes, for discrete or count data to track nonconformities

- Control charts for detecting small shifts in the process mean

In this project, we work with datasets which simulate the data that could have been collected from one variable of an industrial process. We will show some practical examples of computation and representation of various control charts in R. In particular, 4 datasets have been analyzed and the following charts have been constructed, respectively:

- An $\overline{x}$ and $s$ control chart (using datacc1.txt)

- An $\overline{x}$ and $r$ control chart (using datacc2.txt)

- A c-chart (using datacc3.txt)

- Moving Average (MA) and Exponentially Weighted Moving Average (EWMA) control charts (using datacc4.txt)

For visualization on GitHub, click the .md files, which are rendered directly. If you want to run the code, download the .Rmd notebooks containing the R code chunks. The notebooks are also provided in the .html document format.
