
# Epicurious Dataset Cleaning and Analysis

## Overview

This project focuses on cleaning the Epicurious recipe dataset and performing data analysis to extract insights. The analysis explores relationships between recipe ratings, nutritional content (calories, protein, fat, sodium), and categorizes recipes into meal types (breakfast, lunch, dinner) as well as comparing vegetarian and non-vegetarian dishes.




## Data Cleaning Process

1. **Outlier Removal:**
   - Removed recipe ratings that fell outside the valid range (0-5).
   - Removed dishes with calories over 10,000, and dishes with protein, fat, or sodium levels above 5,000, as these were deemed implausible.
   
2. **Null Value Handling:**
   - All rows containing null values were dropped to ensure data completeness.

3. **Assumptions Made:**
   - Ratings were assumed to be between 0 to 5.
   - Nutritional values were capped at logical limits to avoid skewed analysis due to extreme values.

---

## Data Analysis and Insights

### Key Findings:

1. **No Strong Correlation Between Ratings and Nutritional Content:**
   - Ratings are not strongly influenced by calorie, fat, protein, or sodium levels, suggesting that taste, preparation difficulty, or other subjective factors likely drive user feedback.

2. **Meal Type Categorization:**
   - Recipes categorized as dinner tend to have higher average calories compared to breakfast and lunch dishes.

3. **Vegetarian vs. Non-Vegetarian Dishes:**
   - There is minimal difference in average calories between vegetarian and non-vegetarian dishes, but non-vegetarian dishes tend to have higher sodium and protein content.

### Recommendations:
- Consider adding features to provide personalized recommendations for healthier recipe alternatives based on individual nutritional goals (e.g., low sodium, low fat).
- Implement user feedback on ease of preparation or visual appeal to further refine recipe recommendations.



