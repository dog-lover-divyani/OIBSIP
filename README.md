# OIBSIP

### Key Observations So Far
- What item has highest calories?
- Any category noticeably high in fats/sodium?
- Patterns or outliers?


# McDonald's Nutrition Analysis 🍟

## Objective
Analyze McDonald's menu dataset to uncover nutritional facts and health patterns.

## Key Insights
- High correlations found between Total Fat, Calories, and Saturated Fat
- Salads are lowest-calorie category
- Breakfast items contain highest sodium concentration

## Health Ranking
### Top 10 healthiest items
(Insert screenshot or table)

### Top 10 unhealthiest items
(Insert screenshot or table)

## Visualizations
- Correlation heatmap
- Calories distribution
- Nutrient pairplots
- Category calorie averages

## Conclusion
McDonald's menu includes items with extreme nutritional variations.
Custom scoring reveals which foods align better with healthy goals.

'|     | Category     | Item                | Serving Size   |   Calories |   Calories from Fat |   Total Fat |   Total Fat (% Daily Value) |   Saturated Fat |   Saturated Fat (% Daily Value) |   Trans Fat |   Cholesterol |   Cholesterol (% Daily Value) |   Sodium |   Sodium (% Daily Value) |   Carbohydrates |   Carbohydrates (% Daily Value) |   Dietary Fiber |   Dietary Fiber (% Daily Value) |   Sugars |   Protein |   Vitamin A (% Daily Value) |   Vitamin C (% Daily Value) |   Calcium (% Daily Value) |   Iron (% Daily Value) |   Health Score |\n|----:|:-------------|:--------------------|:---------------|-----------:|--------------------:|------------:|----------------------------:|----------------:|--------------------------------:|------------:|--------------:|------------------------------:|---------:|-------------------------:|----------------:|--------------------------------:|----------------:|--------------------------------:|---------:|----------:|----------------------------:|----------------------------:|--------------------------:|-----------------------:|---------------:|\n| 147 | Coffee & Tea | Coffee (Large)      | 16 fl oz cup   |          0 |                   0 |           0 |                           0 |               0 |                               0 |           0 |             0 |                             0 |        0 |                        0 |               0 |                               0 |               0 |                               0 |        0 |         0 |                           0 |                           0 |                         0 |                      0 |            0   |\n| 146 | Coffee & Tea | Coffee (Medium)     | 16 fl oz cup   |          0 |                   0 |           0 |                           0 |               0 |                               0 |           0 |             0 |                             0 |        0 |                        0 |               0 |                               0 |               0 |                               0 |        0 |         0 |                           0 |                           0 |                         0 |                      0 |            0   |\n| 145 | Coffee & Tea | Coffee (Small)      | 12 fl oz cup   |          0 |                   0 |           0 |                           0 |               0 |                               0 |           0 |             0 |                             0 |        0 |                        0 |               0 |                               0 |               0 |                               0 |        0 |         0 |                           0 |                           0 |                         0 |                      0 |            0   |\n| 136 | Beverages    | Dasani Water Bottle | 16.9 fl oz     |          0 |                   0 |           0 |                           0 |               0 |                               0 |           0 |             0 |                             0 |        0 |                        0 |               0 |                               0 |               0 |                               0 |        0 |         0 |                           0 |                           0 |                         0 |                      0 |            0   |\n| 140 | Coffee & Tea | Iced Tea (Child)    | 12 fl oz cup   |          0 |                   0 |           0 |                           0 |               0 |                               0 |           0 |             0 |                             0 |        5 |                        0 |               0 |                               0 |               0 |                               0 |        0 |         0 |                           0 |                           0 |                         0 |                      0 |            1.5 |\n| 114 | Beverages    | Diet Coke (Small)   | 16 fl oz cup   |          0 |                   0 |           0 |                           0 |               0 |                               0 |           0 |             0 |                             0 |       10 |                        0 |               0 |                               0 |               0 |                               0 |        0 |         0 |                           0 |                           0 |                         0 |                      0 |            3   |\n| 138 | Coffee & Tea | Iced Tea (Medium)   | 21 fl oz cup   |          0 |                   0 |           0 |                           0 |               0 |                               0 |           0 |             0 |                             0 |       10 |                        0 |               0 |                               0 |               0 |                               0 |        0 |         0 |                           0 |                           0 |                         0 |                      0 |            3   |\n| 137 | Coffee & Tea | Iced Tea (Small)    | 16 fl oz cup   |          0 |                   0 |           0 |                           0 |               0 |                               0 |           0 |             0 |                             0 |       10 |                        0 |               0 |                               0 |               0 |                               0 |        0 |         0 |                           0 |                           0 |                         0 |                      0 |            3   |\n| 139 | Coffee & Tea | Iced Tea (Large)    | 30 fl oz cup   |          0 |                   0 |           0 |                           0 |               0 |                               0 |           0 |             0 |                             0 |       15 |                        1 |               0 |                               0 |               0 |                               0 |        0 |         0 |                           0 |                           0 |                         0 |                      0 |            4.5 |\n| 117 | Beverages    | Diet Coke (Child)   | 12 fl oz cup   |          0 |                   0 |           0 |                           0 |               0 |                               0 |           0 |             0 |                             0 |       15 |                        1 |               0 |                               0 |               0 |                               0 |        0 |         0 |                           0 |                           0 |                         0 |                      0 |            4.5 |'

[View top 10 healthiest items](healthiest_items.csv)
[View top 10 unhealthiest items](unhealthiest_items.csv)
### Nutrient Correlation Heatmap
![Heatmap]("C:\Users\divya\OneDrive\Desktop\projects\OIBSIP\Task1_McDonalds\images\heatmap.png")
### Calories Distribution
![Calories Distribution]("C:\Users\divya\OneDrive\Desktop\projects\OIBSIP\Task1_McDonalds\images\calories_hist.png")
