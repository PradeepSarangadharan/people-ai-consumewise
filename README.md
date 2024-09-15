# ConsumeWise Application Development

## Problem statement shared by People+ai
ConsumeWise is an AI-enabled smart label reader that helps consumers understand the health impact of packaged food products and nudges them to make better choices.
Problem Statements

## 1. Product Catalogue
Build an AI tech solution for automated collection of data for packaged food products. Existing Data Points on label: Product Name, Product Qty, Brand Name, Weightage in Gram/ML, Nutritional information with serving size, Ingredients, Product Category, any proprietary claims made on the label (sugar free, trans fat free, etc). This data layer can also be augmented and enriched in various ways to widen information available for our algorithm stack. Food products can be categorised into various indexes based on user habits like purpose (nutritional, regular, recreational), frequency (daily, weekly, monthly) etc.

### What to optimise for?

Accuracy: Ensuring that the data collected is accurate
Dynamic Database: Updated with more products that get introduced into the market
Exhaustive: Designing it to be exhaustive. Metric: products listed by online retailers in India- blinkit, bigbasket.
Relevance of augmentation: If generated insights and categorization from raw data are relevant to the scope of the problem

## 2. Health Analysis
Utilise AI to generate a health analysis of the product. The analysis can be general or user-specific, with relevant nudges to the user. Some pointers are:

Nutritional Analysis - Higher presence of nutrients desired in low qty (fats, sugar, sodium, calories)
How processed and nutrient deficit is the product?
- Harmful Ingredients present
- If people follow certain diets, does it comply with it
- Is it diabetes/allergen friendly
- Are there any claims made by brands that could be misleading
### What to optimise for

- Scientific credibility & accuracy of the analysis provided
- The information should add value to the user such that helping them make a decision

## Multi-modality
Solve for better user experience by building for different interfaces/modalities/languages to enhance reach to users. 

**_FastAPI developed by People+ai team:_**
You can use [this](https://cwbackend-a3332a655e1f.herokuapp.com/docs) existing API as a starting point. 

**_Basic Functionality Video:_**
This is [how it functions](https://drive.google.com/file/d/1xDfaIYwEr9wPZKXIYNQKnQ9cTiO2362C/view?usp=sharing).

### What to optimise for

- Reaching the user at the point of decision and influencing their decision making
- Providing the information without causing cognitive overload
- You can choose to work on a specific problem statement from the above or plug and play these modules to build an end-to-end solution.


