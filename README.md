# Gym-AB-Testing
## Scenario
A gym called Flex Zone is trying to increase their gym memberships and wants to test out a new button for registration to see if that will boost memberships. The success rate for the new, experimental button will be determined by click through rate. I will perform an A/B test using a 2-sample Z Test because it fit the criteria of having more than 30 data points per group, so by the central limit theorem, we can assume that there is a normal distribution for the data.

<img src="https://github.com/user-attachments/assets/a20d0366-690d-4697-ab05-799d4b740607" width="700" height="400">


## Data
This is an overview of the distribution for click through rates of the control and experimental buttons:

<img src="https://github.com/user-attachments/assets/13abb6c5-b1d2-4b00-8bc7-ab625fd467a5" width="700" height="400">

The distribution for the **control CTR is 0.605** success while the **experimental CTR success is 0.4567**.

## Conclusion
After performing the A/B Test, I concluded that while there was statistical significance in the difference from the experimental button compared to the control button, there was no practical significance. The new button reading "Start 7 Day Free Trial" had a much smaller CTR compared to the original "Enroll Now 7 Days Free." Due to these findings, **Flex Zone has decided to not change their button** and instead launch a different marketing tactic to increase membership enrollment. 
