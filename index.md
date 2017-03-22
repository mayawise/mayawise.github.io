# Frequentist vs Bayesian probability

The overarching goal of both approaches is the same: to make a statement about the population (*all* data points) based on a *sample* of data points, and describe our uncertainty about that statement.

Suppose we’re interested in the average height in inches, AKA *h*, of all [pangolins](http://www.telegraph.co.uk/science/2016/03/15/pangolins-13-facts-about-the-worlds-most-hunted-animal/) in the sub sahara.


|                      | Frequentist                                                                                                               | Bayesian                                                                                                                                                                                                                           |
|----------------------|---------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Ask:                 | What is the probability of our data given a true and fixed population mean?                                               | What is the probability of the true mean given the data that we have?                                                                                                                                                              |
| *h*:| It’s a single point; an estimate of a true mean. *h* is an unknown constant which either lies in the range [70, 74] or does not | It’s a range of values; an estimate within a range of a true mean. *h* is a probability distribution.                                                                                                                                        |
| Process:            | Observe a sample and calculate a mean based purely on that sample                                                         | Update the prior distribution in light of the sampled data to get a new probability distribution for h AKA the “posterior distribution.” The posterior distribution reflects our state of knowledge about h after collecting data. |

[![Pangolin](https://i.ytimg.com/vi/LMiYjkG4onM/hqdefault.jpg?custom=true&w=336&h=188&stc=true&jpg444=true&jpgq=90&sp=68&sigh=UvxMNMKfzcbVEJEhJ5zAa8Je9L4)](https://www.youtube.com/watch?v=LMiYjkG4onM)



