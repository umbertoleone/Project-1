# Project-1
Description: using data obtained from http://insideairbnb.com/get-the-data.html our goal was to ascertain the potential price change that could occur when a host becomes a superhost in the NYC Airbnb market from March 2017 to March 2020.

Hypothesis: hosts increase their price after they become superhosts.

We used a paired t-test to determine the p-value associated with our host-to-superhost sample before-and-after the change in status occurred.

A paired t-test was used because our two samples from 2017 & 2020 had the same number of observations (host-to-superhost inflection points). Therefore, the two samples from different points in time could be paired with one another ... Before-and-after observations on the same subjects.

After we isolated the inflection points which represented the change in status from host-to-superhost, we compared price changes associated with these shifts in status.

To ensure our findings would be accurate, we approached the problem statement from three different perspectives: (1) calculating price discrepancies per listing year-over-year specifically regarding hosts becoming superhosts over the same period. (2) paired t-test of 2020 rental price to 2017 rental price for the 943 hosts that became superhosts (3) median price by borough in reference to the changes in status (H->SH & SH->H->SH) year-over-year.

Based on our analysis, we rejected our hypothesis that hosts increase their rental listing base price per night after they become superhosts in the NYC Airbnb market from March 2017 to March 2020.
