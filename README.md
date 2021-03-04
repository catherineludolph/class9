# class9

1. Write the null and alternative hypotheses you would use to test each of the following situations:
- Is a coin fair?
  - null = fair, 50/50 chance, no correlation
  - alternative = weighted towards heads or tails
- Only about 20% of people who try to quit smoking succeed. Sellers of a motivational tape claim that listening to the recorded messages can help people quit.
  - null = recorded messages have no impact on quitting rate
  - alternative = record messages and quitting rate are correlated
- In the 1950s only about 40% of high school graduates went on to college. Has this percentage changed?
  - null = graduating high school has no impact on going to college
  - alternative = graduating high school influences going to college at a certain rate
- We field test a new type of pipette, planning to market it only if we are sure that at least 60% of people like the new version.
  - null = people have no preference
  - alternative = people have a preference, liking the new pipette more than the previous


2. A survey investigating whether the proportion of today’s high school seniors who own their own cars is higher than it was a decade ago finds a p-value of 0.017. Is it reasonable to conclude that more high schoolers have cars? Explain.
  - the p value is less than 0.05, so it is reasonable to reject the null and conclude that more high schoolers have cars. If the null is true, there is a 1.7% chance that it was due to statistical fluke


3. A medical researcher tested a new treatment for poison ivy against the traditional ointment. With a p-value of 0.047 she concludes the new treatment is more effective. What does the p-value mean in this context?
  - the p value of 0.047 means that if the treatment is not more effective, there is a 4.7% chance that she would still get the results she got, which is a low chance (<0.05), so the results are likely not a fluke, and if they're not a fluke, then the new treatment is more effective.


4. Have harsher penalties and ad campaigns increased seatbelt use? Observations of commuter traffic failed to find evidence of a significant change compared with three years ago. What does the study’s p-value of 0.17 means in this context?
  - the p value of 0.17 is greater than 0.05, and indicates that there was a 17% chance of getting these results due to statistical fluke, which is quite high. This indicates that it is likely that there is no correlation between harsher penalties and ad campaigns increasing seatbelt use over the past 3 years.


5. Researcher developing scanners to search for hidden weapons at airports concluded that a new device is significantly better than the current scanner. They made this decision based on a test using alpha = 0.05. Would they have made the same decision at alpha = 0.10 or alpha = 0.01? Explain
  - Alpha, the significance level, is the probability that you will make the mistake of rejecting the null hypothesis when in fact it is true. When p is greater than alpha, you accept the null hypothesis. SO, if alpha is 0.05, p > 0.05 results in accepting the null hypothesis. However, if alpha is 0.1, p > 0.05 may result in accepting or rejecting the null (p between 0.05 and 0.1 would be rejected when before it was accepted before). Similar, if alpha is 0.01, p > 0.05 would still accept the null, but would also accept if p was less than 0.05 and as low as 0.01, where it was accepted before.

6. Environmentalists concerned about the impact of high-frequency radio transmissions on birds found that there was no evidence of a higher mortality rate among hatchlings in nests near cell towers. They based this conclusion on a test using alpha = 0.05. Would they have made the same decision at alpha = 0.10? How about alpha = 0.01? Explain.
- This reasoning is similar to that of question 5. They accepted the null hypothesis (that there was no correlation) with an alpha of 0.05, so their p must have been greater than 0.05. This p value may have resulted in the null being rejected if the alpha was 0.1 (if the p was between 0.1 and 0.05), but would still have been accepted if alpha was 0.01, as any value over 0.05 is also over 0.01.

7. A clean air standard requires that vehicle exhaust emissions not exceed specified limits for various pollutants. Many states require that cars be tested annually to make sure they meet the standards. Suppose state regulators double check a random sample of cars that a suspect repair shop has certified as okay. They will revoke the shop’s license if they find significant evidence that the shop is certifying vehicles that do not meet standards. 	
- In this context, what is a Type I error?
  - a type I error is when the null hypothesis is true but we mistakenly reject it (false positive)
  - in this context, this means that the shop is not certifying vehicles that do not meet standards, but the regulators have incorrectly concluded that the shop is certifying vehicles that don't meet standards
- In this context, what is a Type II error?
  - a type II error is when the null hypothesis is false but we mistakenly fail to reject it (false negative)
  - in this context, this means that the shop is certifying vehicles that don't meet standards, but the regulators incorrectly conclude that they are not certifying vehicles that don't meet standards.
- Which type of error would the shop’s owner consider more serious?
  - shop owners would probably consider a type I error more serious, as this may shut down their shop
- Which type of error might environmentalists consider more serious?
  - environmentalists would probably consider a type II error more serious, as this means they would be letting shop owners get away with allowing cars to pollute the environment 
