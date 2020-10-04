# anomalous-cancellations
Python program for finding anomalous cancellations in different bases
An anomalous cancellation is a fraction that retains the same value when a digit is removed from both the numerator and denominator
For instance, when 6 is removed from 16/64, it becomes 1/4, which is merely a simplified form of 16/64
In most cases, this does not work; removing 6 from 16/63 yields 1/3, changing the fraction's value
This program searches for anomalous cancellations in different bases.
It considers only those fractions where the numerator is smaller than the denominator, and where both are less than six digits long.
It then saves the previous fraction, the simplified fraction, and the new digit to a CSV file.
