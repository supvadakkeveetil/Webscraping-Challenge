# Webscraping-Challenge
## Description
Webscraping from the Mars News Article and Mars Weather Data websites

### Part1 - Scrape Titles and Preview Text from Mars News 
[
](https://github.com/supvadakkeveetil/Webscraping-Challenge/blob/main/part_1_mars_news.ipynb)

Steps: 1. Inspect the website using Devtools

2. Create a Beautiful Soup object and use it to extract elements from the website
   
3. Extract the title and preview of the news articles and store in a Python Data Structure

Example:

{'title': "NASA's MAVEN Observes Martian Light Show Caused by Major Solar Storm",
  'preview': 'For the first time in its eight years orbiting Mars, NASA’s MAVEN mission witnessed two different types of ultraviolet aurorae simultaneously, the result of solar storms that began on Aug. 27.'}
  
  ### Part2 - Scrape and Analyze Mars Weather Data
[
](https://github.com/supvadakkeveetil/Webscraping-Challenge/blob/main/part_2_mars_weather.ipynb)

![Screen Shot 2023-12-05 at 3 50 21 PM](https://github.com/supvadakkeveetil/Webscraping-Challenge/assets/144635564/cdcb591f-b183-4737-9720-50f4343425b7)

Analyzing dataset using Pandas functions to answer the following questions:

1. How many months exist on Mars?
Answer: 12 months

2. How many Martian (and not Earth) days worth of data exist in the scraped dataset?
Answer: 1867

3. What are the coldest and the warmest months on Mars (at the location of Curiosity)? 
![image](https://github.com/supvadakkeveetil/Webscraping-Challenge/assets/144635564/c6c136bb-21ec-4730-9330-e2c1dfa383a6)

Answer: Coldest month in Curiosity location is 3rd month

Hottest month in Curiosity location is 8th month

4. Which months have the lowest and the highest atmospheric pressure on Mars? 

![image](https://github.com/supvadakkeveetil/Webscraping-Challenge/assets/144635564/2dcbd2f5-f0e0-4802-8126-392d16308e7c)

Answer: Lowest Stmospheric Pressure on Mars is observed in the 6th month

Highest Pressure on Mars is observed in the 9th month

5. About how many terrestrial (Earth) days exist in a Martian year?
   
Visually estimating the result by plotting the daily minimum temperature.

![image](https://github.com/supvadakkeveetil/Webscraping-Challenge/assets/144635564/523f9b59-4223-4122-9295-edcdc74e8045)

Answer: The distance from peak to peak is roughly 1425-750, or 675 days. A year on Mars appears to be about 675 days from the plot. Internet search confirms that a Mars year is equivalent to 687 earth days.

6. Saving the DataFrame into a csv file -Link
   [
](https://github.com/supvadakkeveetil/Webscraping-Challenge/blob/main/Mars_weather_data)
## References
Data Source: The Mars News websiteLinks to an external site. is operated by edX Boot Camps LLC for educational purposes only. The news article titles, summaries, dates, and images were scraped from NASA's Mars NewsLinks to an external site. website in November 2022. Images are used according to the JPL Image Use PolicyLinks to an external site., courtesy NASA/JPL-Caltech.
