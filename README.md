# Population-climate-analysis
Exploratory data analysis of climate and population

The dataset used in this project is the **Ford GoBike System Data**, which contains information about individual bike share trips in the San Francisco Bay Area. The dataset includes details such as trip duration, start and end stations, start and end times, user type (Subscriber or Customer), gender, and birth year.

The dataset helps analyze how people use the bike-sharing system and identify patterns in trip duration, rider demographics, and riding behavior.

During the data preparation stage, several transformations were performed:

- Converted start and end times to datetime format
- Created new features such as:
  - trip distance
  - trip hour
  - day of week
- Removed invalid or missing values where necessary
- Calculated trip distance using latitude and longitude coordinates

These steps helped prepare the dataset for meaningful exploratory analysis and visualization.

## Summary of Findings

The exploratory analysis revealed several interesting patterns in bike usage:

1. **Trip Duration Distribution**
   - Most trips are relatively short, typically under 20 minutes.
   - The distribution of trip durations is heavily right-skewed, indicating a small number of long trips.

2. **User Type Behavior**
   - Subscribers make up the majority of trips.
   - Subscribers tend to have shorter and more consistent trip durations compared to customers.

3. **Distance vs Duration Relationship**
   - There is a positive relationship between trip distance and trip duration.
   - Longer trips naturally take more time, though the relationship is not perfectly linear due to varying speeds and riding patterns.

4. **Time Patterns**
   - Bike usage peaks during commuting hours, particularly in the morning and late afternoon.
   - This suggests that many users rely on the service for commuting purposes.

5. **Demographic Patterns**
   - Male riders represent the largest group of users in the dataset.
   - Differences in trip duration across gender groups were relatively small.

Overall, the data suggests that the Ford GoBike system is heavily used for short, efficient trips, especially by regular subscribers during commuting hours.

## Key Insights for Presentation

The explanatory presentation focuses on the most important insights discovered during the exploratory analysis.

### 1. Subscriber vs Customer Usage
Subscribers dominate the system and tend to take shorter, more frequent trips. This suggests the service is widely used as a commuting tool.

### 2. Relationship Between Distance and Duration
Trips with longer distances generally correspond with longer durations. Visualizing this relationship helps highlight typical riding patterns across users.

### 3. Daily Usage Patterns
Trip counts increase significantly during commuting hours, especially around early morning and late afternoon. This reinforces the idea that bike-sharing plays a role in urban commuting.

For the presentation slides, visualizations were refined to improve clarity by:
- simplifying axis labels
- highlighting key trends
- reducing unnecessary visual elements
- focusing only on the most impactful insights

These adjustments help communicate the findings more clearly to a non-technical audience.
