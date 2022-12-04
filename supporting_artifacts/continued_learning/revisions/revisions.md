---
editor_options: 
  markdown: 
    wrap: 72
---

# Lab 3 Revision:

*Feedback:*

*How was the sample of participants selected? How many students were in
the sample?*

*How were the participants definitions coded?*

**Revision and Reflection:**

At first, I thought that I had sufficiently summarized the data set in
the first question. I realized that my summary included very superficial
information about the data itself rather than the importance behind the
study. I included information about who the data was about and how these
participants were selected. Additionally, I described how the variables
were defined. This information should have been included in the first
place so that people reading my code could understand the study without
having to do additional research about the data set.

*Feedback: Zero is one way missing values were coded, but there is
another way. Look through the data documentation to find the other
method used to code missing values and describe the benefits / drawbacks
of this method.*

**Revision and Reflection:**

I initially only looked through the data set
to find missing values rather than looking at the documentation. I found
out that the data documentation included information about the other
missing value of replacing missing values with means. I described the
benefits and drawbacks to this because this is a significant
characteristic of the data that I need to identify to external users.

*Feedback: In this course, we use `ggplot()` to create our
visualizations. Please recreate this histogram using ggplot instead of
`hist()`.*

**Revision and Reflection:**

I was not thinking to use ggplot from dplyr. I instead used the base R
hist() function. I should be more careful about making sure I use what
we are learning about in my code.

*Feedback: The `filter()` function should only be called **once**.*

**Revision and Reflection:**

For the last two parts of the lab, I called the filter function multiple
times in the same pipe. I did not know that I could combine it all into
one function separated by a comma, but now that I know, it is so much
cleaner and tidy do write code like that.

# Challenge 3

*Feedback: Great work! You are on the right track! The next step is to
find the differences in these means. Could you use another `summarize()`
step to get these differences?*

**Revision/Reflection:**

At first I thought that I only had to find the means of each group and
compare those. I did not think that I could use another function to
better summarize what we were trying to achieve. By using another
summarize() function, I was able to find the difference in means between
the groups which helped to identify the largest differences as well as
allow users to more easily see the differences. Another edit I made was
to use the colon to select a range of columns with the select()
function. This is much cleaner and faster than typing everything out.

# Lab 5

*Feedback: You have revisions to remove the unnecessary output from your
rendered document.*

**Revision/Reflection:**

When I loaded in the tidyverse package, I kept the output in my rendered
document. This is just not a good practice, so I will be careful not to
do this in the future. I will make sure to remove the output as soon as
I start a new quarto doc.

# Lab 7

*Feedback:* *Great function! I\'d press you to think about the
redundancy in your function. Is the same function being called multiple
times? If so, how can you remove this redundancy?*

**Revision/Reflection**

I did not write the most efficient code. I was repetitive and used the
same argument twice. This time, I saved the minimum values from my
vector into another object that I would call later in the function to
reduce the redundancy.

*Feedback: **Every** plot you make in this course should have
informative axis labels!*

I did not label my axis. Because I created a new rescaled version of the
data, it is important that I describe what I'm doing so that external
users can easily understand what I am outputting. Informative axis
labels are a part of good data visualization skills.
