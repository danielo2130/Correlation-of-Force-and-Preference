# Correlation-of-Force-and-Preference

## Overview:
In a lab study, we gave respondents a task to measure their preferences over pairs of items by first choosing which item they prefer and then rating their strength of preference. To complete this task, we had them select their preferred item using buttons that were specially designed to detect exactly how hard the person is pressing, which we call the haptic response. In the data attached here, you will see:

- Each respondent (`id`)
- Choosing multiple times (`replicate`)
- With a strength of preference (`DV`)
- A haptic response curve, which readings taken every several microseconds, and higher numbers meaning more force applied on the choice button (`curve`)
- The peak of the haptic response (`peak`)
- The duration of the haptic response (`duration`)
- And the response time (`rt`)

You can ignore the column `button`, which just says whether the left or right button was selected. 

## Goal:
To understand if `curve` relates to strength of preference (`DV`). 

Using whatever analysis you think is appropriate, explore this question. We are especially interested in understanding the relationship between `curve` and `DV` controlling for the person, and controlling for different features like `duration`, `peak`, and `rt`.
