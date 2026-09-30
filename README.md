# DecodeLabs Project 1 – Data Cleaning & Preparation

## Overview

This project was completed as part of my Data Analytics internship at DecodeLabs.

The objective of this project was to clean and prepare a raw dataset using Microsoft Excel.

## Objectives

- Identify and handle missing values
- Check duplicate records
- Verify duplicate Order IDs
- Standardize date formatting
- Check numeric data formatting
- Review text and category consistency

## Dataset

The dataset contains 1,200 records and 14 columns related to customer orders.

Key columns include:

- OrderID
- Date
- CustomerID
- Product
- Quantity
- UnitPrice
- PaymentMethod
- OrderStatus
- CouponCode
- ReferralSource
- TotalPrice

## Data Cleaning Performed

### Missing Values

Missing values in the CouponCode column were handled by replacing blank values with `No Coupon`.

### Duplicate Check

- Duplicate OrderID: 0
- Duplicate Full Rows: 0

### Formatting

- Dates were standardized.
- Quantity and ItemsInCart were checked as whole numbers.
- UnitPrice and TotalPrice were checked for appropriate decimal formatting.
- Text and category fields were reviewed for consistency.

## Final Result

The dataset was cleaned and verified for missing values, duplicates, and formatting consistency.

## Tools Used

- Microsoft Excel
- Data Cleaning
- Data Preparation
