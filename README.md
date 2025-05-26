# 🏛️ White House Visitor Departure Analysis

## Technologies Used
- Programming Language: Python  
- Libraries: Pandas, NumPy, Matplotlib  
- Tools: Jupyter Notebook  
- Dataset: White House Visitor Logs  

## Project Overview
As a taxi driver in Washington, D.C., covering the White House area, my afternoon shift (12PM–8PM) has not generated enough income to sustain my expenses. December was particularly slow due to holiday travel patterns, and I believe visitor departure trends from the White House directly impact taxi availability in the area.

This project analyzes visitor departure trends to:
- Identify peak departure times throughout the week, month, and year.
- Understand fluctuations in taxi demand based on group sizes.
- Build a data-driven argument for switching to the morning shift (4AM–12PM), which has higher potential customers.

## Purpose
My goal is to convince my boss to approve a shift change by presenting structured data on visitor departure patterns and taxi availability.  
Key insights will cover:
- The effect of weekdays vs. weekends on departure volume.
- Seasonal trends in travel behavior.
- Group sizes to determine the most efficient taxi vehicle for the morning shift.

Switching to the morning shift would increase my fares, helping me cover my financial needs.

## Medium
The findings will be presented to my boss in a PDF report with visual charts, designed for easy comprehension.  
By reviewing the report in a one-on-one meeting, I can:
- Walk through each data visualization to highlight insights.
- Clarify assumptions and methodologies used in data cleaning.
- Answer concerns in real time, strengthening the case for a shift change.

## Design Approach
To ensure clarity and intuitive data presentation, I adopted the following strategies:
- Color-coded shifts for easy interpretation:
  - 🟡 **Morning Shift (4AM–12PM)** → Yellow (sunrise)
  - 🔵 **Afternoon Shift (12PM–8PM)** → Blue (daytime skies)
  - 🟣 **Evening Shift (8PM–4AM)** → Purple (night skies)
- Consistent labeling for key departure trends.
- Legends positioned in the top-left corner, following the daily timeline: morning → afternoon → night.

## Ethical Considerations
The White House Visitor Log dataset was extensively refined to focus on key variables:
- Reduced original 27 columns to 3 key fields for analysis.
- Removed entries missing departure time to ensure accuracy.
- Assumptions made:
  - Visitors departing the White House represent primary taxi customers in the area.
  - Groups leaving together prefer riding in the same taxi.

I will be transparent about these assumptions during my meeting, ensuring my boss understands the limitations of the dataset.

## Key Visualizations
The PDF report will include:
- Departure trends by weekdays and months, illustrating peak taxi demand.
- Average group sizes by shift, optimizing vehicle selection.
- Comparisons between morning, afternoon, and evening shifts to support the request.
- Seasonal patterns and anomaly detection (e.g., holiday periods).

These data-driven insights will strengthen my case for switching shifts.

## Future Improvements
- Expand dataset scope to include nearby government buildings and attractions.
- Incorporate real-time taxi fare data for further validation.
- Improve predictive modeling to forecast high-volume departure periods.
- Develop an interactive dashboard for real-time exploration of visitor trends.
