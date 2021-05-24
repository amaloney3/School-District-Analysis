# Spending and Performance in Schools, Before and After Suspected Violations

## Overview
The purpose of this analysis is to paint a comprehensive picture of local student and school performance in reading and 
mathematics, depicting how school size, budget and type (charter or district) could potentially affect that result. Additionally,
because there were suspected academic violations in one school, modifications were required to the analysis in order to 
maintain the integrity of the conclusions. More analyses could be warranted, however, the changes did not seem to have a large
effect on the results.

## Results

What follows is a brief summary of the exploratory analysis we conducted on the aforementioned variables. The results presented first 
do not include data from 9th graders at Thomas High School, whose results are suspected to have been altered (although that matter is
still being investigated). The results that do include the potentially-compromised data will be presented immediately afterward, in 
each bullted category, for comparison.

- In general, charter schools tended to have better results than district schools when it came to average scores in math and reading, and overall passing rates.

![image](https://user-images.githubusercontent.com/1015285/119282730-5ced2780-bc00-11eb-9f3a-d2e9cd9130eb.png)

The numbers are essentially the same whether the data from the 9th graders at Thomas High (a charter school) are included or not. Those schools tend to be smaller anyway, so it seems plausible there is an interaction effect when it comes to academic results grouped by size.

- Smaller and medium-sized schools tended to have stronger scores than large schools. 

![image](https://user-images.githubusercontent.com/1015285/119283017-4eebd680-bc01-11eb-90cb-d981be55bf01.png)

Again, there could be a moderating effect between type and size of schools. I'll note again here that the results are essentially unchanged whether
Thomas High is included or not (you have to include decimal places, and sometimes hundredths or thousandths, to notice any discrepancies).

- Spending per student seems to have an inverse correlation with performance, as schools spending less than $584 per student had the best
outcomes. However, this relationship is likely moderated heavily by school size and type.

![image](https://user-images.githubusercontent.com/1015285/119283215-e9e4b080-bc01-11eb-9134-0957857995e9.png)

Whether the Thomas High data for 9th graders is included is, again, trivial when the focus is on the overall results.

- One might expect average scores to increase as students progress throughout their high school careers, from 9th to 12th grade. However, the material
is also supposed to become more complex, and it's unclear from this data whether individual educators or discrepancies between school curricula have any
effect on that relationship. The math scores are shown first, and the reading second. 

![image](https://user-images.githubusercontent.com/1015285/119286074-2a93f800-bc09-11eb-9979-bb7dcc0e8053.png)

![image](https://user-images.githubusercontent.com/1015285/119286147-45ff0300-bc09-11eb-8fac-1fc07f514f4a.png)

The snapshots above clarify the Thomas High data that was omitted (NaN). Although the integrity of the 9th graders' scores there remains
unclear, I'll note that the analysis found their average in math to be 83.6 and their average in reading to be 83.7. Again, it's difficult
to tell whether their scores meaningfully impact the overall picture. But it's worth pointing out the school's 10th-12th graders didn't
perform signficantly differently.

- It's fair to say the district-wide summary is affected only at the margins when the Thomas High 9th grade data is omitted versus when it's included. The numbers
would all round the same, and the average reading score (81.9) is exactly the same. However, the potentially-volatile data increases the rest of the scores very
slightly. The first image below is sans the Thomas High data; the second includes it.

![image](https://user-images.githubusercontent.com/1015285/119286800-cbcf7e00-bc0a-11eb-8e4e-296f151f3b1c.png)

![image](https://user-images.githubusercontent.com/1015285/119286831-d8ec6d00-bc0a-11eb-9dcd-bcc9a5153dd4.png)

Note that the conclusions for the entire district would stay the same, regardless.

- Thomas High School's own metrics are, unsurprisingly, most-noticeably affected by the 9th grade data. Below are the metrics being evaluated in this analysis, 
followed by the Thomas High scores with the 9th grade data omitted, and then with the 9th grade data kept.

![image](https://user-images.githubusercontent.com/1015285/119288059-7648a080-bc0d-11eb-9e41-a77d135b9f99.png)

![image](https://user-images.githubusercontent.com/1015285/119287704-96c42b00-bc0c-11eb-8227-932e16305866.png)

![image](https://user-images.githubusercontent.com/1015285/119287813-e86cb580-bc0c-11eb-8157-3d3d1ac8d160.png)

The 9th grade scores again push almost every single category a little bit higher (with the exception of average reading score). However, the theme remains: all
the numbers would round the same with or without those scores.

- Finally, Thomas High remains a top 5 (top 2, actually) performing school whether we evaluate only its 10th through 12th graders, or keep its 9th grade data and evaluate all of its students. 

![image](https://user-images.githubusercontent.com/1015285/119288399-143c6b00-bc0e-11eb-9a1a-da2472950a8c.png)

For the sake of completion, the bottom 5 schools are also listed below, too.

![image](https://user-images.githubusercontent.com/1015285/119288631-8e6cef80-bc0e-11eb-8ba4-95092366f061.png)


## Summary

There's no doubt educators must model integrity, and there's no doubt that the scores from Thomas High School that have reportedly been tampered with must be 
thoroughly checked out before being included in an overall analysis without caveats. However, by simply refining the analysis so it only includes the school's 10th, 11th and 12th graders, we see that the picture for both that particular institution and the rest of the district is relatively unchanged. There are slight tweaks -- the school's overall passing rates and its average math score decrease by fractions, while its average reading score increases by a fraction; the district-wide summary does the same (the overall passing percentage goes from 65% to 64.9% without the Thomas High 9th graders, for instance). Meanwhile, the analysis of spending ranges per student is mildly different in the $630-$644 range, with the average reading score increasing very slightly (going from 81.62% to 81.63% when you omit the Thomas High 9th grade data) and everything else decreasing very slightly. The same is true of the results when you describe performance by school size -- the "Medium" category (1000-2000 students) follows a similar pattern.

But for our results today, the move is mostly symbolic, and perhaps will help mostly serve to prepare the district if there are more suspected violations in the future.



