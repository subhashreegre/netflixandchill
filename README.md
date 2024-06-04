Netflix Movie Duration Analysis 🍿🍿
Introduction
This project involves performing an exploratory analysis of Netflix movie durations over the years. We'll use Python and its data manipulation and visualization libraries to gain insights into the trends and characteristics of movie durations on the Netflix platform.

Data
We started by analyzing average movie durations from 2011 to 2020, provided by a friend. These durations are: 103, 101, 99, 100, 100, 95, 95, 96, 93, and 90, respectively. To delve deeper, we obtained more comprehensive data from a CSV file ("datasets/netflix_data.csv").

Project Steps
Loading Data: We began by loading our friend's data into a dictionary and created a DataFrame. This data provided initial evidence that movie durations might be decreasing.
Creating a DataFrame: We created a DataFrame using pandas from the dictionary, allowing us to manipulate and analyze the data more effectively.
Visual Inspection: We visually inspected the data by creating a line plot to observe the trend in movie durations.
Loading More Data: We loaded additional data from a CSV file containing Netflix data. This data included details about movies and TV shows.
Filtering for Movies: We filtered the data to focus only on movies by selecting rows with the "Movie" type and relevant columns.
Creating a Scatter Plot: We created a scatter plot to visualize movie durations over a longer time range.
Digging Deeper: We analyzed the distribution of short movies (under 60 minutes) and explored their genres.
Marking Non-Feature Films: We marked non-feature films with different colors on the scatter plot to identify trends associated with genres like "Children," "Stand-Up," and "Documentaries."
Final Plot: We created a final scatter plot with colored points to visualize movie durations and understand trends better.
Conclusion
Through data analysis and visualization, we observed trends in movie durations on Netflix. We found that non-feature films, such as children's movies and documentaries, tend to have shorter durations. This project showcases how Python and its libraries can be used to explore and gain insights from data
