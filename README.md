# Laptop Price Analysis

# Project Overview

The original dataset was pretty compact with a lot of details in each column. The columns mostly consisted of long strings of data, which was pretty human-readable and concise but for Machine Learning algorithms to work more efficiently it's better to separate the different details into their own columns. After doing so, 28 duplicate rows were exposed and removed with this dataset being the final result.

# Dataset

 Company: Laptop Manufacturer.
 
 ● Product: Brand and Model.
 
 ● TypeName: Laptop Type (Notebook, Ultrabook, Gaming, …etc).
 
 ● Inches: Screen Size.
 
 ● Ram:Total amount of RAM in laptop (GBs).
 
 ● OS:Operating System installed.
 
 ● Weight: Laptop Weight in kilograms.
 
 ● Price_euros: Price of Laptop in Euros. (Target)
 
 ● Screen: screen definition (Standard, Full HD, 4K Ultra HD, Quad HD+).
 
 ● ScreenW: screen width (pixels).
 
 ● ScreenH: screen height (pixels).
 
 ● Touchscreen: whether or not the laptop has a touchscreen.
 
 ● IPSpanel: whether or not the laptop has an IPSpanel.
 
 ● RetinaDisplay: whether or not the laptop has retina display.

 ● CPU_company
 
 ● CPU_freq: frequency of laptop CPU (Hz).
 
 ● CPU_model
 
 ● PrimaryStorage: primary storage space (GB).
 
 ● PrimaryStorageType: primary storage type (HDD, SSD, Flash Storage, Hybrid).
 
 ● SecondaryStorage: secondary storage space if any (GB).
 
 ● SecondaryStorageType: secondary storage type (HDD, SSD, Hybrid, None).
 
 ● GPU_company
 
 ● GPU_model

# Results

# Model Performance
The linear regression model achieved an R-squared value of 0.6992596278756551, indicating the proportion of variance explained by the model.

The random forest regression model achieved an R-squared value of 0.8521217075896228, indicating the proportion of variance explained by the model.
