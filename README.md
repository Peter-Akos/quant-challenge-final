# Morgan Stanley Quant Challenge Final

Morgan Stanley’s Quant Challenge is a chance to experience first-hand how quantitative analytics teams work within a global investment bank. 

Read more about the challenge at the [official site](https://www.quantchallenge.hu/).

# Our team - Compacto
 - Péter Ákos
 - Magyari-Sáska Attila
 - Ács Hunor
 - Gagyi Levente-Lóránt

# The task
Find the optimal number of options to purchase, to hedge the risk of farmers to climate change.

More details in [task.pdf](https://github.com/Peter-Akos/quant-challenge-final/blob/main/task.pdf)

# Our Solution

Farmers get high profit, if the price is high. We need to give them profits if the prices are low, so we must only buy put options, meaning we bet on the price being low.

We need to search a 7 dimensional space for an optimal strategy, and only use the solutions that that conform to the percentile limits.

To do this, we first select random numbers of options to see if the distribution conforms to the percentile requirements, and if it does, we search the space around the point to see if there are better solutions there.

Feel free to take a look at our [presentation](https://drive.google.com/file/d/1GYFjzHbPhA_7oMo9j-cAcr8FF68yC17O/view?usp=sharing) in Hungarian.
