# TheStory_NDA PowerBI Dashboard README

This README provides an overview of the PowerBI dashboard created to explore stock market data and analyze the performance of stock indices before, during, and after a recession. The objective of this project was to gain insights into past trends and understand the impact of economic crises on the stock market.

## Objective
The main objective of this project was to study the stock market data and analyze the performance of stock indices in relation to recessions. The project aimed to identify expected trends and uncover unexpected patterns in the data. Additionally, the project aimed to gain a good understanding of stock market data and terminology, as well as learn how to effectively utilize the PowerBI tool.

## Interesting Discoveries
During the data analysis and visualization process, three interesting discoveries were made:
1. The year 2014 had significant impacts on the majority of the countries studied, despite not being marked as a recession period. Further investigation revealed that the Russian-Ukrainian conflict was a common event during 2014 and the present.
2. Despite the United States' US Dollar being considered the world's reserve currency, it was not the top-performing stock index in the world.
3. The peak unemployment rate does not depend on the duration of a recession. However, the duration of a recession can be a factor in determining its overall impact on countries.

## Tool Limitations
While utilizing PowerBI for visualizations, some limitations were encountered, including:
- Less control over the formatting of text, such as padding and margins.
- Limited customization options for tooltips and legends.
- Aggregation requirements for numeric data types, even when aggregation is not necessary or applicable.
- Fewer features available for the X-Axis Constant Line, such as the absence of tooltips and the inability to shade the area between two constant lines.

Please note that these limitations were based on the group's experience with PowerBI, and some may be specific to their analysis.

## Challenges with the Dataset
The dataset used for this project was mostly clean and well-organized, but some modifications were necessary to make it compatible with PowerBI's processing requirements. Additionally, to eliminate biases, all price fields were converted into US Dollars. Overcoming these challenges required utilizing PowerBI features and conducting thorough research.

## Other Difficulties
Finding the appropriate dataset for analysis was a significant challenge due to the financial nature of the data and concerns regarding data authenticity. Additionally, many sources did not provide all the required fields, further complicating the data collection process. Initially, understanding when to use average, sum, or other aggregations posed difficulties, but with practice and research, the group was able to overcome this challenge. Given more time, additional features offered by PowerBI would have been explored and incorporated into the report.

## Recommendations
For users of the PowerBI report, the following recommendations are provided:
- Utilize the "Drill-through" option to gain a deeper understanding of stock index trends in different countries, navigating from the Summary report to the Insights report.
- Note that due to the large number of tables fetched from multiple sources, the refresh time of the project can take up to 60 seconds.
- To view the analysis for a specific group of countries, select multiple countries in the Summary report. For example, selecting all countries in the Asia region will display the analysis for that region.
- In case of errors during data refresh, follow these steps: open "Transform data" from the toolbar, select "Refresh All" from the "Refresh Preview" option, click "Close & Apply," and then hit "Refresh" again. If the issue persists, there may be a problem with the source from which real-time information is fetched. Tables or visuals related to real-time data will display the last available data, while those not dependent on real-time data will continue to function properly.

Please note that this PowerBI project was created by individuals who were relatively new to the tool. Despite the limitations and challenges encountered, the group made the best effort to incorporate the available features and create meaningful visualizations and reports.

## License
This PowerBI dashboard and associated README file are provided under the [MIT License](https://opensource.org/licenses/MIT).
