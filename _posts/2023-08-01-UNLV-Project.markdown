---
layout: post
title:  "[UNLV] Big-data Processing "
date:   2023-08-01 18:05:55 +0300
image:  post_5_0.png
tags:   Research_Internship  
---

During my summer vacation in 2023, I visited to UNLV(University of Nevada, Las Vegas) in Las Vegas to work on project under the guidance of a professor Kang.
Professor Kang is from an engineering school, computer science department, so I was able to learn from him in a more technical way. 
I initially proposed an interdisciplinary study in the social sciences like LIS, but my professor wanted me to focus on technology this summer, so I followed his direction.
And it was still a great experience to me.     


So Let me introduce my team's project in UNLV !! 

( note : This is a Final-presentation paper! )


---
## Scalable Data Processing with MapReduce 

<center> <img src="/images/post_5/post_5-01.png" width="600" height="450"> </center>
<center> <img src="/images/post_5/post_5-04.png" width="600" height="450"> </center>

We use this [data][data] from Kaggle, it was used to determine whether a user was at risk of defaulting on a bank loan.    
And it was literally "Big-data", becasue it contains **252,000 rows**!! About Two hundred fifty thousand !!!    
So we had to use a method called "MapReduce" to process big data efficiently and quickly.   

**BUT !! In this project, Data doesn't have a big meaning, it was chosen for its SIZE !!**

<img src="/images/post_5/post_5-02.png" width="500" height="390"> <img src="/images/post_5/post_5-03.png" width="500" height="390">

Rather than the data itself, we focused on how efficiently we processed big data.
MapReduce is the way to dramatically increase the efficiency of processing large scale datasets through distributed parallelism.   
  
It is composed of "Map" and "Reduce" parts.  
First, when it comes to "Map" part, we separated the data and mapped the data that can be paired together.   
And then we "reduced" the data size by summing the mapped data.   





{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[data]: https://github.com/ddubny/UNLV_engineering
