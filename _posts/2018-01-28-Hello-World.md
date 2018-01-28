---
layout: post
title: Hello World! Posting a Jupyter notebook to my Jekyll blog.
---

### This is a test Jupyter notebook. We will convert this into markdown and put it on our Jekyll blog.


```python
import matplotlib.pyplot as plt
%matplotlib inline
```


```python
x=[1,2,3,4]
y=[5,6,7,8]
```


```python
plt.plot(x,y)
```




    [<matplotlib.lines.Line2D at 0x2641b5a30b8>]




![png](/images/hello_world_output_3_1.png)


Ready to see if equations will render?
The equation of the line above is $ y = x+4 $.

Finally I go to "File" , Download As Markdown.
I will rename the image and move it to a seperate folder, and so will need to adjust the image URL manually.
