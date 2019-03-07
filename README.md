# Visualizing Big Datasets: Tools, Pitfalls, Experimental Example

Talk about Data visualization in Science. Based on my experience with ratCAVE project and suggested approaches in Python I created a talk for my fellow MSNE students. The talk covers main problems with use of scatter plot for big, convolved data and explains how to address it.  

### Summary:

What should we keep in mind, when working with big datasets? In case of <b><i>Scatter plots</b></i> - 3 hyperparameters:

* overplotting - avoid obscuring the data
* saturation - look howmany points overlapping cause saturation of intensity points
* undersampling - taking a subset might not be an answer

Or instead you can work with <b><i>Heatmaps</i></b> and remember to address following problems (1 hyperparameter):

* undersaturation
* pick the color map in accordance to the

<figure>
<p float="left">
    <img src="/images/1_a.png" width="320">
    <img src="/images/1_b.png" width="320">
</p>
<figcaption>
  Talk explains how to get from left to right: impretable visualization of datasets.
</figcaption>
</figure>


<br>Presented on 01.06.2018 at the retreat for [Master of Science in Neuroengineering](https://www.msne.ei.tum.de/en/home/) students.

### Installing

To run jupyter notebook as slides I used:
* [RISE](https://damianavila.github.io/RISE/)

The talk was based on the use of:
* pandas
* seaborn
* datashader


## Acknowledgments
* [Nicholas A. Del Grosso](https://github.com/nickdelgrosso) - for supervision and inspiration for this talk
* [Mohammad Bashiri](https://github.com/mohammadbashiri) - for feedback
