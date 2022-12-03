---
editor_options: 
  markdown: 
    wrap: 72
---

For the revisions included in your Portfolio, to help me understand the
nature of your revisions, please denote somehow the feedback I provided
you (e.g., boldface, italics, colored text) before your revisions.

# Lab 3 Revision:

*Feedback:*

*How was the sample of participants selected? How many students were in
the sample?*

*How were the participants definitions coded?*

**Revision and Reflection:**

At first, I thought that I had sufficiently summarized the data set in
the first question. I realized that my summary included very superficial
information about the data itself rather than the \
importance behind the study. I included information about who the data
was about and how these participants were selected. Additionally, I
described how the variables were defined. This \
information should have been included in the first place so that people
reading my code could understand the study without having to do
additional research about the data set.

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
