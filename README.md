# Descriptive Statistics

The project contains descriptions and example code for identifying and creating summary statistics as it relates to your data set. The following are some common ways to report descriptive statistics and included in the project:
* Frequency distributions: You can report frequency distributions
* Measures of central tendency: You can report the mean, median, and mode of the data.
* Measures of variability: You can report the range, interquartile range (IQR), variance, and standard deviation of the data.
* Skewness and Kurtosis: You can report the skewness and kurtosis values to describe the shape of the data.

Descriptive Statistics is also known as summary statistics because they provide a summary or overview of the main characteristics or features of a dataset, such as measures of central tendency, variability, and distribution. They are called "descriptive" because they describe or summarize the data in a way that is easy to understand and communicate, without necessarily making any inferences or conclusions about the population from which the data was sampled. Although in most cases the primary research question will be about one or more statistical relationships between variables, it is also important to describe each variable individually. For this reason, we begin by looking at some of the most common techniques for describing single variables.

Frequency Distribution
A frequency distribution is a table or graph that displays the number of occurrences (frequency) of different values in a set of data. It is a way of summarizing a large set of data to make it easier to understand and draw conclusions from. In a frequency distribution, the data is grouped into classes or intervals, and the frequency of each class is counted and displayed. This provides a visual representation of the distribution of the data, showing how the values are spread out and how often certain values occur. Frequency distributions can be represented in various forms such as a histogram, bar graph, or table.

What are the main Measures of Central Tendency?
There are three main measures of central tendency: mean, median, and mode. When exploring your data, all these three measures should be applied together in order to come to a better conclusion.
* Mean: Also known as average (µ for population, x̄ for sample). It corresponds to the center of a set of numbers. The mean is computed by dividing all the numbers by the total number of elements.
* Median: Represents the middle value of the data after being sorted in ascending or descending order. As opposed to the mean, the median is not affected by the presence of outliers and can be for that reason a better measure of central tendency. However, median and mean only work for numerical data.
* Mode: Corresponds to the most occurring value in the data and can be applied to both numerical and categorical variables. Similarly to the median, the mode is not sensitive to outliers. However, the mode does not exist when all the values in the data have the same number of occurrences.

Measures of Variability
The variability of a distribution is the extent to which the scores vary around their central tendency.
Consider the two distributions below, both of which have the same central tendency. The mean, median, and mode of each distribution are 0. Notice, however, that the two distributions differ in terms of their variability. The top one has relatively low variability, with all the scores relatively close to the center. The bottom one has relatively high variability, with the scores are spread across a much greater range.
* Range: One simple measure of variability is the range, which is simply the difference between the highest and lowest scores in the distribution. Although the range is easy to compute and understand, it can be misleading when there are outliers.
* Interquartile Range: The “IQR” is a way to measure the spread of the middle 50% of a dataset. It is calculated as the difference between the first quartile (the 25th percentile) and the third quartile (the 75th percentile) of a dataset.
* Spot Outliers: There are different methods to determine that a data point is an outlier. The most widely known is the 1.5xIQR rule.
Outliers are extreme observations in the dataset. So a rule of thumb to determine if a data point is extreme is to compare it against the interquartile range.But why 1.5 times the interquartile range? This is related to an important characteristic of the Normal Distribution known as the 68–95–99 rule. Any data point lower than the lower bound or greater than the upper bound is an outlier:
**  (data point value) < Q1–1.5xIQR, then it’s an outlier.
**  (data point value) > Q3 + 1.5xIQR, then it’s an outlier.

Standard Deviation
Variance and standard deviation are measures of the spread or dispersion of a set of data. By far the most common measure of variability is the standard deviation. The standard deviation of a distribution is the average distance between the scores and the mean.
The standard deviation is the square root of variance, has the same unit as the data and is a more interpretable measure of dispersion.Computing the standard deviation involves a slight complication. Specifically, it involves finding the difference between each score and the mean, squaring each difference, finding the mean of these squared differences, and finally finding the square root of that mean.

Distribution and Shape
Skewness and Kurtosis are the two main techniques that can tell more about the shape of a given dataset.
What is Skewness and kurtosis important to measure?
* Skewness is a measure of the asymmetry of a data distribution. Knowing the degree of skewness can help to understand the distribution of a variable and identify any outliers or extreme values that may be affecting the mean and median. Skewness is important in many areas of research, such as finance and economics, where it is important to understand the distribution of financial data, such as stock prices and returns.
* Kurtosis is a measure of the tailedness (some say peakedness or flatness) of a data distribution. Knowing the degree of kurtosis can help to understand the concentration of values around the mean, median, or mode and identify any outliers that may be affecting the distribution. Kurtosis is particularly important in areas such as psychology, where it is important to understand the distribution of personality traits or IQ scores, or in medical research, where it is important to understand the distribution of patient outcomes.
* In summary, measuring skewness and kurtosis provides important information about the shape of a data distribution, which can affect the interpretation of central tendency measures, such as mean and median, and measures of variability, such as standard deviation and range.

