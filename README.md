# 1660_CaptainLeeDaSom

made by Jaehyeok Choi

## Welcome to Jaehyeok's github!

## What is the problem?

![image](https://github.com/Choi-JaeHyeok-21500749/1660_CaptainLeeDaSom/blob/main/1660_pro.PNG)

## What Algorithm should I use?

dynamic programming

## What was the key point and the hard part?

The number of bomb in triangle is adding 1 to n. The number of 사면체(Don't know in english...) is making sum of number of bomb until n.

So add the number of bombs in 사면체 in the array and stop when the number is bigger than n. This is because we don't need the number bigger than n.

Then starting from 1, we will check the number of bombs in 사면체 that is smaller than i, and find the min value.

For example, if n == 15 , we will check the min value in dp[i-1] + 1 , dp[i-4] + 1 , dp[i-10] + 1.

Keep saving the minimum value in dp will make right answer.

## Where can I get more help, if I need it?

You can contact me through email, which is wogur7496@gmail.com.
Thank you for visiting this github!
