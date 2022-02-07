# MechaCar_Challenge

## Purpose
The goal of this study is to analyze various metrics (such as vehicle length, weight, spoiler positioning, ground clearance, AWD, MPG and PSI) that influence vehicle manufacturing and performance. 

## Linear Regression to Predict MPG
<img width="473" alt="Screen Shot 2022-02-06 at 5 10 44 PM" src="https://user-images.githubusercontent.com/89936913/152710246-d7674682-7110-476e-aaac-7aaf26765c78.png">

### Takeaways
Variance of non-randoms is at zero or almost at zero, so the intercept, vehicle length and ground clearance likely produce a non-random amount of variance. 
We can reject the null hypothesis because of the very small p-value (0.05). Thus, the slope is zero. 

## Visualizations for the Trip Analysis

<img width="344" alt="Screen Shot 2022-02-06 at 5 22 46 PM" src="https://user-images.githubusercontent.com/89936913/152710905-157816ae-b921-45f8-89fb-2a7edb8102de.png">

Variance tells us that the manufacturer meets the 100 lbs per square inch variance limitation, but the third lot demonstrates a much higher variance.

## T-Test on Suspension Coils

<img width="371" alt="Screen Shot 2022-02-06 at 5 25 35 PM" src="https://user-images.githubusercontent.com/89936913/152711055-b4df3572-8012-48c3-95c4-cae892302654.png">

Here we fail to reject the null hypothesis with the p value of 0.06, so the sample mean may be the same as the true population mean. 

## T-Test on Smaller Lots

<img width="370" alt="Screen Shot 2022-02-06 at 5 25 56 PM" src="https://user-images.githubusercontent.com/89936913/152711081-0a8948cb-4af9-42ad-9df7-72430be55bf3.png">

We fail to reject the null hypothesis of Lot 1, as the p-value is 1. The confidence interval is also smaller, implying a more accurate population mean. 

<img width="376" alt="Screen Shot 2022-02-06 at 5 26 38 PM" src="https://user-images.githubusercontent.com/89936913/152711127-672832f9-8ee8-4e25-950d-f40f3ac1a2f3.png">

We also fail to reject to null hypothesis with the p-value at 0.6072. 

<img width="376" alt="Screen Shot 2022-02-06 at 5 26 53 PM" src="https://user-images.githubusercontent.com/89936913/152711141-dc4e8c12-0078-44f3-ba0a-c68ce54c2e32.png">

Here we reject the null hypothesis with p-value of 0.04168

## Designing a Study: MechaCar vs. Competition
A worthwhile study would be on fuel efficiency in the city versus in the highway. These variables would include city and highway fuel efficiency as the dependent variable, and horsepower, vehicle weight, AWD and MPG as the independent variables. 
