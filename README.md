# MODULE 10 CHALLENGE 

## Introduction

With Module 10, we applied our knowledge with Machine Learning to utilize Jupyter Lab and create k-mean plots. In this exercise, we assume the role of an advisor and are assembling investment portfolios that base proposals on other worldly factors than just volatility.



## Code Samples

composite_1 =df_elbow_data.hvplot.line(
    x="k", 
    y= "inertia", 
    title="Crypto Elbow Curve", 
    xticks=k
)

composite_1
