# Statistics
This repository is my education in statistics.

## Overall Goal
1. Combine the references into one cohesive unit to work with in the future.

## Goals
### Current goal
- Work through probability theory.

## Work
### 24 Feb 2024
- Adding in Set Theory in order to give a second perspective to probability theory. The first approach is documented here and is based on _relative frequency_. This approach is discussed with great detail in [Spiegel](#ref_spiegel) and [Freedman](#ref_freedman). The second approach is used in [Peebles](#ref_peebles), which the author describes as "the axiomatic definition" (page 2). He states, "It is the most mathematically sound of all approaches."
- Chapter 6 of Spiegel - Elementary Probability Theory
  * [Definitions of Probability](Spiegel/06%20Chapter%206%20Elementary%20Probability%20Theory/01%20Text/01%20Definitions%20of%20probability.ipynb). Both Classical and Relative-Frequency.
  * [Conditional Probability](Spiegel/06%20Chapter%206%20Elementary%20Probability%20Theory/01%20Text/02%20Conditional%20probability%3B%20independent%20and%20dependent%20events.ipynb). The difference between independent and dependent events.
  * [Mutually Exclusive Events](Spiegel/06%20Chapter%206%20Elementary%20Probability%20Theory/01%20Text/03%20Mutually%20exclusive%20events.ipynb).
  * [Solved Problems - Fundamental Rules of Probability](Spiegel/06%20Chapter%206%20Elementary%20Probability%20Theory/02%20Solved%20problems/01%20Fundamental%20rules%20of%20probability.ipynb)
  * [Supplementary Problems - Fundamental Rules of Probability](Spiegel/06%20Chapter%206%20Elementary%20Probability%20Theory/03%20Supplementary%20problems/01%20Fundamental%20rules%20of%20probability.ipynb)
- Chapter 13 of Freedman - What are the Chances?
  * [Freedman's definition of chance](Freedman/04%20Part%20IV.%20Probability/13%20What%20Are%20the%20Chances/01%20Introduction.ipynb).
  * [Conditional Probability](Freedman/04%20Part%20IV.%20Probability/13%20What%20Are%20the%20Chances/02%20Conditioanl%20probabilities.ipynb).
  * [The Multiplication Rule](Freedman/04%20Part%20IV.%20Probability/13%20What%20Are%20the%20Chances/03%20The%20multiplication%20rule.ipynb).
  * [Independence](Freedman/04%20Part%20IV.%20Probability/13%20What%20Are%20the%20Chances/04%20Independence.ipynb).
  * [Review exercises](Freedman/04%20Part%20IV.%20Probability/13%20What%20Are%20the%20Chances/05%20Review%20exercises.ipynb).

### Old
* Updated the [Introduction to Regression](Freedman/03%20Part%20III.%20Correlation%20and%20Regression/10%20Regression/01%20Introduction.ipynb).
This demonstrates how to use NHANES data sets and filter data sets for specifics. Although it uses `lm()` to create
the linear regression line, it does explain how to manually create one using the predictor's mean, standard deviation, and the correlation
between predictor and response.
* Updated [The Graph of Averages](Freedman/03%20Part%20III.%20Correlation%20and%20Regression/10%20Regression/02%20The%20Graph%20of%20Averages.ipynb).
A method of aggregating data points is described here. It can be used for other uses.

## References (Chicago)
1. <a id=ref_alder></a>Adler, Joseph. 2012. _R in a Nutshell_, 2nd ed. Sebastopol: OReilly.
2. <a id=ref_boslaugh></a>Boslaugh, Sarah. 2013. _Statistics In a Nutshell_, 2nd ed. Sebastopol: OReilly.
3. <a id=ref_dalpiaz></a>Dalpiaz, David. _Applied Statistics with R_. February 17, 2024. https://book.stat420.org/.
4. <a id=ref_freedman></a>Freedman, David, Robert Pisani, and Roger Purves. 2007. _Statistics_, 4th ed. New York: W. W. Norton & Company, Inc.
5. <a id=ref_peebles></a>Peebles, Peyton Z. Jr. 2001. Probability, Random Variables, and Random Signal Principles. 4th ed. New York: McGraw-Hill Inc.
6. <a id=ref_spiegel></a>Spiegel, M. R., & Stephens, L. J. 2017. _Schaum’s Outline of Statistics_, 6th ed. McGraw-Hill Education.

