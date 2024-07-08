# Amusement-Park-Data-Analytics-and-Visualization

### Problem Statement
The administrators of Dino Fun World, a local amusement park, have tasked you with multiple data analysis and visualization. These assignments aim to explore park operations, visitor behavior, and spatial patterns through various statistical and graphical methods.

### Data Used
1. **Dino Fun World Database:**
   - **checkins:** Check-in data for all visitors, including inferred and actual check-ins.
     - Fields: `visitorID`, `timestamp`, `attraction`, `duration`, `type`
   - **attraction:** Information about park attractions.
     - Fields: `AttractionID`, `Name`, `Region`, `Category`, `type`
   - **sequences:** Check-in sequences of visitors, listing their position every five minutes.
     - Fields: `visitorID`, `sequence`

2. **Geographic Data:**
   - Geographic data for the lower 48 United States, including state-by-state data and shape files for each state.

### Visualization and Analytical Procedures Involved
1. **Choropleth Map:**
   - Visualization of spatial distribution of data across the states of the lower 48 United States.
   - Insights: Showed geographical patterns and differences among states.

2. **Proportional Symbol Map:**
   - Visualization highlighting relative magnitudes of data points across the United States.
   - Insights: Emphasized key areas with significant data points.

3. **Moran's I Calculation:**
   - Computation of Moran's I to assess spatial autocorrelation.
   - Insights: Provided an understanding of spatial patterns and clustering within the geographic data.

4. **Pie Chart:**
   - Depiction of visits to thrill ride attractions.
   - Insights: Showed the distribution of visitor preferences for thrill rides.

5. **Bar Chart:**
   - Visualization of total visits to food stalls.
   - Insights: Highlighted the popularity of various food stalls within the park.

6. **Line Chart:**
   - Attendance trends at the newest ride, Atmosfear, over the course of a day.
   - Insights: Displayed temporal trends and peak times for ride attendance.

7. **Box-and-Whisker Plot:**
   - Depiction of total visits to Kiddie Rides.
   - Insights: Showed statistical distribution and variability in visits to Kiddie Rides.

8. **Control Chart:**
   - Attendance at the 'Atmosfear' ride, showing mean and standard deviation bands.
   - Insights: Identified fluctuations and stability in ride attendance.

9. **Moving Average Chart:**
   - Visualization of attendance trends with a 50-sample window.
   - Insights: Smoothed data to highlight underlying trends over time.

10. **Exponentially Weighted Moving Average Chart:**
    - Attendance trends using an exponentially weighted moving average.
    - Insights: Provided refined analysis of attendance trends.

11. **Distance Matrix:**
    - Analysis of check-in sequences for five randomly selected visitors.
    - Insights: Helped understand visitor paths and behavior patterns within the park.

12. **Parallel Coordinate Plot:**
    - Visualization of minimum, average, and maximum attendance at each ride.
    - Insights: Allowed comparison of attendance metrics across different rides.

13. **Scatterplot Matrix:**
    - Depiction of min, average, and max attendance for each ride.
    - Insights: Facilitated the understanding of relationships between attendance metrics.

### Insights Gained
- **Visitor Preferences:** Identified the most popular attractions and rides, highlighting visitor preferences and behaviors.
- **Engagement Analysis:** Assessed ride engagement through duration and frequency of visits.
- **Food Stall Popularity:** Analyzed the popularity of various food stalls, identifying the least and most visited options.
- **Attendance Trends:** Evaluated temporal trends in attendance for specific rides, particularly new attractions like Atmosfear.
- **Spatial Patterns:** Visualized geographic data to reveal spatial patterns and clustering across the United States.
- **Statistical Distribution:** Used box-and-whisker plots and control charts to understand the variability and stability in visitor data.
- **Visitor Paths:** Constructed distance matrices to analyze visitor paths and sequences, providing insights into movement patterns within the park.
- **Comparative Analysis:** Employed parallel coordinate plots and scatterplot matrices to compare attendance metrics across different rides, offering a comprehensive view of park operations.
