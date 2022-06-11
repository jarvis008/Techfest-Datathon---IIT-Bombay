# Techfest-Datathon---IIT-Bombay

# Problem Statement:
### Given the business potential of 3,915 regions over a period of 6 years(72 months), forecast the business potential of all these regions for the next 15 months. 
### Link to the detailed problem statement - https://techfest.org/2021/competitons/Datathon.pdf

# Exploring the data:
<img width="700" alt="image" src="https://user-images.githubusercontent.com/77911251/157307309-b094b2c1-eaa3-46f8-bf6e-76121c021052.png">

## Variation of business potential data for different regions
![regional variations](https://user-images.githubusercontent.com/77911251/173178312-6836ca4f-f088-4dc4-9670-104fd2cb390d.jpg)

## Observing trends, seasonality, and random noise
![trends and seasonalities](https://user-images.githubusercontent.com/77911251/173178361-0f9fe84a-e7d5-4c61-9da3-f24d190f9d86.jpg)

## Looking for regions with highly similar business potential curve
![High correlation](https://user-images.githubusercontent.com/77911251/173178404-dc50a2fa-cb22-4c80-ae02-8ef5c3f1ecc1.jpg)

## Regions with dissimilar business potential curves
![low correlation](https://user-images.githubusercontent.com/77911251/173178462-98556186-f1ba-458b-8a5a-d53763d732dc.jpg)

## Looking for Outliers
![outlier detection with inter-quartile range](https://user-images.githubusercontent.com/77911251/173178651-c880843b-ac0f-4a91-bd0c-5572f5c7a2c9.jpg)
#### Green region shows values within 25-75% of median. All points outside the green region are assumed to be outliers. Outliers are replaced with the previous value. The lower figure shows the plot with outliers removed(in blue).
