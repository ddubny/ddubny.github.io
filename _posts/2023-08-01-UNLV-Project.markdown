---
layout: post
title:  "Big-data Processing "
date:   2023-08-01 18:05:55 +0300
image:  post_5_0.png
tags:   Data_analysis   
---


<div class="notice--gray">
   <span style="font-size: 18px; font-family: Open Sans;">
      📢 Notice !!    <br>
      This project was done at Universtiy of Nevada, Las Vegas, under the guidance of an Computer Science professor Kang.    
   </span>
</div>

<br>
<br>


<justify>  
During my summer vacation in 2023, I visited to UNLV(University of Nevada, Las Vegas) in United States to work on a Engineering project.
Particularly, I engaged in Big-data processing project, coupled with Machine Learning method. 
<span style='background-color:#fff5b1'>This is because I felt that the needs of Parallel Processing methods like MapReduce, when I had conducted <strong>Social media analysis</strong> with streaming data.</span>
 </justify>




---
## Scalable Data Processing with MapReduce 

<center> <img src="/images/post_5/post_5-01.png" width="600" height="450"> </center>
<center> <img src="/images/post_5/post_5-04.png" width="600" height="450"> </center>

We used this [data][data] from Kaggle, it was composed of user factors and their final states whether a user was at risk of defaulting on a bank loan.    
And it was literally "Big-data", becasue it contains **252,000 rows**!! About Two hundred fifty thousand !!!    
So we had to use a Parallel Processing method called "MapReduce" to process big data efficiently and quickly.   

**BUT !! In this project, Data was not a matter, it was chosen for its SIZE to practice applying MapReduce!!**

<center> <img src="/images/post_5/post_5-02.png" width="600" height="450"> <img src="/images/post_5/post_5-03.png" width="600" height="450"> </center>

Rather than the data itself, we focused on how efficiently we processed big data.    
MapReduce is the way to dramatically increase the efficiency of processing large scale datasets through distributed parallelism.    

<center> <img src="/images/post_5/plus.jpeg" width="600" height="450"> </center>

It is composed of "Map" and "Reduce" parts.  
First, when it comes to **"Map"** part, we separated the data and mapped the data that can be paired together.   
And then we **"reduced"** the data size by summing the mapped data.   
This is how MapReduce works. 

<center> <img src="/images/post_5/post_5-05.png" width="600" height="450"> </center>
<center> <img src="/images/post_5/post_5-06.png" width="600" height="450"> </center>
<center> <img src="/images/post_5/post_5-07.png" width="600" height="450"> </center>


<center> <img src="/images/post_5/post_5-08.png" width="600" height="450"> </center>
   
 

<center> <img src="/images/post_5/post_5-09.png" width="600" height="450"> </center>

We used **Linear Regression** as a <span style='background-color:#ffdce0'>Machine Learning method</span> to predict the loan defaulter. This is why the Ordinary least squares formula was applied to the mapping process. We calclutate the gradients in this process. 

<center> <img src="/images/post_5/post_5-10.png" width="600" height="450"></center>

And then, we chose one of entire gradients and multiplied by learning rate in reduce process. 

<center> <img src="/images/post_5/post_5-11.png" width="600" height="450"> </center>

<center> <img src="/images/post_5/post_5-12.png" width="600" height="450"></center>
  

<center> <img src="/images/post_5/post_5-13.png" width="600" height="450"> </center>


<center> <img src="/images/post_5/post_5-14.png" width="600" height="450"></center>


<center> <img src="/images/post_5/post_5-15.png" width="600" height="450"> <img src="/images/post_5/post_5-16.png" width="600" height="450"></center>

<center> <img src="/images/post_5/post_5-17.png" width="600" height="450"> <img src="/images/post_5/post_5-18.png" width="600" height="450"></center>

<center> <img src="/images/post_5/post_5-19.png" width="600" height="450"> <img src="/images/post_5/post_5-20.png" width="600" height="450"></center>

<center> <img src="/images/post_5/post_5-21.png" width="600" height="450"> <img src="/images/post_5/post_5-22.png" width="600" height="450"></center>


<center> <img src="/images/post_5/post_5-23.png" width="600" height="450"> <img src="/images/post_5/post_5-24.png" width="600" height="450"></center>


<center> <img src="/images/post_5/post_5-25.png" width="600" height="450"> <img src="/images/post_5/post_5-26.png" width="600" height="450"></center>

<center> <img src="/images/post_5/post_5-27.png" width="600" height="450"> <img src="/images/post_5/post_5-28.png" width="600" height="450"></center>


[data]: https://github.com/ddubny/UNLV_engineering
