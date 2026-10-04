# Cognifyz Technologies - Data Analysis Internship
## Level 2 Tasks

This folder contains the completed Level 2 tasks for the Cognifyz Technologies Data Analysis Internship.

## Tools & Technologies

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

---

# Task 1: Restaurant Ratings

## Objective

Analyze the distribution of restaurant ratings, identify the common rating ranges, and calculate the average number of votes received by restaurants.

## Analysis Performed

- Analyzed the distribution of Aggregate Ratings.
- Calculated the average restaurant rating.
- Identified the distribution of ratings across different ranges.
- Analyzed the number of votes received by restaurants.
- Visualized the restaurant rating distribution.

## Results

- **Average Restaurant Rating:** 2.67
- **Rating Range:** 0.0 to 4.9
- **Restaurants with 0.0 rating:** 2,148

## Key Insight

A large number of restaurants have a rating of 0.0, while rated restaurants are mainly concentrated around the 3.0–4.0 range.

---

# Task 2: Cuisine Combination

## Objective

Identify the most common cuisine combinations and analyze whether certain cuisine combinations tend to have higher restaurant ratings.

## Analysis Performed

- Counted the most frequently occurring cuisine combinations.
- Identified the top cuisine combinations.
- Compared average ratings across cuisine combinations.
- Filtered combinations with sufficient restaurant records for meaningful comparison.
- Visualized the most common cuisine combinations.

## Results

| Cuisine Combination | Restaurant Count |
|---|---:|
| North Indian | 936 |
| North Indian, Chinese | 511 |
| Chinese | 354 |
| Fast Food | 354 |
| North Indian, Mughlai | 334 |
| Cafe | 299 |
| Bakery | 218 |
| North Indian, Mughlai, Chinese | 197 |
| Bakery, Desserts | 170 |
| Street Food | 149 |

## Key Insight

North Indian is the most frequently occurring cuisine entry, while combinations such as North Indian with Chinese and North Indian with Mughlai are also highly represented in the dataset.

---

# Task 3: Geographic Analysis

## Objective

Analyze the geographic distribution of restaurants using latitude and longitude data and identify major restaurant concentrations.

## Analysis Performed

- Loaded restaurant latitude and longitude coordinates.
- Checked for missing geographic coordinates.
- Created a scatter plot to visualize restaurant locations.
- Analyzed the number of restaurants across cities.
- Calculated the percentage distribution of restaurants across the top cities.
- Identified major geographic concentrations.

## Results

| City | Restaurant Count | Percentage |
|---|---:|---:|
| New Delhi | 5,473 | 57.30% |
| Gurgaon | 1,118 | 11.71% |
| Noida | 1,080 | 11.31% |
| Faridabad | 251 | 2.63% |
| Ghaziabad | 25 | 0.26% |
| Ahmedabad | 21 | 0.22% |
| Amritsar | 21 | 0.22% |
| Bhubaneshwar | 21 | 0.22% |
| Guwahati | 21 | 0.22% |
| Lucknow | 21 | 0.22% |

## Key Insight

New Delhi has the highest concentration of restaurants, followed by Gurgaon and Noida. The geographic analysis shows that restaurants are concentrated in a few major cities rather than being evenly distributed.

---

# Task 4: Restaurant Chains

## Objective

Identify restaurant chains and analyze their presence, average ratings, and popularity based on votes.

## Analysis Performed

- Grouped restaurants by restaurant name.
- Identified restaurant chains with at least 5 outlets.
- Calculated the number of outlets for each chain.
- Calculated average ratings.
- Calculated average votes.
- Identified highly represented and highly rated restaurant chains.

## Results

| Restaurant Chain | Outlets | Average Rating | Average Votes |
|---|---:|---:|---:|
| Cafe Coffee Day | 83 | 2.42 | 29.25 |
| Domino's Pizza | 79 | 2.74 | 84.09 |
| Subway | 63 | 2.91 | 97.21 |
| Green Chick Chop | 51 | 2.67 | 18.90 |
| McDonald's | 48 | 3.34 | 110.23 |
| Keventers | 34 | 2.87 | 37.15 |
| Pizza Hut | 30 | 3.32 | 165.37 |
| Giani | 29 | 2.69 | 29.45 |
| Baskin Robbins | 28 | 1.86 | 15.29 |
| Barbeque Nation | 26 | 4.35 | 1082.38 |

## Key Insights

- Cafe Coffee Day has the highest number of outlets among the analyzed chains.
- Domino's Pizza and Subway also have a strong presence.
- Barbeque Nation has the highest average rating at 4.35.
- Barbeque Nation also has the highest average votes, indicating strong customer engagement.
- McDonald's and Pizza Hut also have relatively high average ratings.

---

# Conclusion

The Level 2 analysis provided practical insights into:

- Restaurant rating distributions
- Cuisine combinations and their ratings
- Geographic distribution of restaurants
- Restaurant chains, ratings, and popularity

These tasks provided hands-on experience in exploratory data analysis, data aggregation, visualization, and extracting meaningful insights using Python.

## Files

- `Task_1_Restaurant_Ratings.ipynb`
- `Task_2_Cuisine_Combination.ipynb`
- `Task_3_Geographic_Analysis.ipynb`
- `Task_4_Restaurant_Chains.ipynb`