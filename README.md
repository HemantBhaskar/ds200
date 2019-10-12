The file details about the observations from the plots in Hemant_Kumar_Plots.zip folder. 


1. SCATTER PLOT:

	1.1 Folder: SCATTER_PLOT

	1.2 Data Source: https://data.gov.in/resources/monthly-seasonal-and-annual-max-temp-series-1901-2017-0

	1.3 Python_File: scatter.py

	1.4 Data_Source_Filename: Max_Temp_IMD_2017.csv

	1.5 Operating Instructions: The scatter.py file accepts Data_Source_Filename from command line arguments. 
		So, in terminal type: 

		python3 scatter.py <Data_Source_Filename> , ie.,

		python3 scatter.py Max_Temp_IMD_2017.csv

	1.6 Plot_Image: Scatter_Plot.png

	1.7 Plot Observations: The downloaded data file 'Max_Temp_IMD_2017.csv' from Data Source [4] gives the maximum temperature for months from January to December for the year 1901 to 2017. The data is contributed by Ministry of Earth Sciences [6] and India Meteorological Department (IMD) [2]. The months were grouped based on the seasons they fall in. From Wikipedia 'Climate of India' [1] information (Seasons Section) and India Meteorological Department (IMD) [2,3] information, I have grouped the months 'December, January and February' for Winter season, 'March, April, and May' for Summer season, 'June, July, August and September' for Monsoon Season, and 'October and November' for Autumn season. I have taken the average of the maximum temperature of each constituting months within a season to determine the season's 'average maximum temperature'. For the value of annual 'average maximum temperature,' I have taken the average of the maximum temperature of all the months within that year. From the plot Scatter_Plot.png, the x-axis shows the 'year' and the y-axis shows the value of 'average maximum temperature' season-wise and annual for a given year. In Scatter_Plot.png, it has labels described as:

		a. 'dec_to_feb (winter)' : It accounts for Winter season months, ie., December, January, and February
		b. 'mar_to_may (summer)' : It accounts for Summer season months, ie., March, April, and May
		c. 'jun_to_sep (monsoon)' : It accounts for Monsoon season months, ie., June, July, August, and September
		d. 'oct_to_nov (autumn)' : It accounts for Autumn season months, ie., October, and November
		e. 'annual' : It accounts for all the months in a year, ie., from January to December

	From the plot, it can be seen that the 'average maximum temperature' has increased annually from the year 1901 to 2017 in INDIA. For Winter season the 'average maximum temperature' was less than 24 degrees for the year 1901 and around, while for year 2017 and around the 'average maximum temperature' can be seen to be approx 26 degrees. For the Summer season also the 'average maximum temperature' was approx 30 to 32 degrees for the year 1901 and around, while for the year 2017 and around the 'average maximum temperature' can be seen to be approx 32 to 34 degrees. Similarly, for the Autumn and Monsoon season, an increase in temperature from 1901 to 2017 can be easily seen from the plot. Hence a steady increase in temperature per season and annually is witnessed in INDIA from the year 1901 to 2017. This effect is mainly due to increasing deforestation and global warming. The effect of global warming in incrementing the temperature of INDIA could be easily seen from the plots. Global warming [5] is the result of human emissions of greenhouse gases. Strict steps need to be taken against increasing global warming like improving afforestation rate, controlling pollution and population, less usage of devices that emit greenhouse gases, etc.

	1.8 References:

		1. Wikipedia: Climate of India 
		   https://en.wikipedia.org/wiki/Climate_of_India

		2. India Meteorological Department (IMD)
		   http://www.imd.gov.in/Welcome%20To%20IMD/Welcome.php

		3. India Meteorological Department (IMD) : Frequently Asked Questions (FAQ)
		   http://imd.gov.in/section/nhac/wxfaq.pdf

		4. Monthly, Seasonal and Annual Max Temp Series from 1901 to 2017
		   https://data.gov.in/resources/monthly-seasonal-and-annual-max-temp-series-1901-2017-0

		5. Wikipedia: Effects of global warming
		   https://en.wikipedia.org/wiki/Effects_of_global_warming

		6. Ministry of Earth Sciences
		   https://moes.gov.in/


2. BAR PLOT:

	2.1 Folder: BAR_PLOT

	2.2 Data Source: https://data.gov.in/resources/variety-wise-daily-market-prices-apple-2019

	2.3 Python_File: bar.py

	2.4 Data_Source_Filename: Apple_2019.csv

	2.5 Operating Instructions: The bar.py file accepts Data_Source_Filename from command line arguments. 
		So, in terminal type: 

		python3 bar.py <Data_Source_Filename> , ie.,

		python3 bar.py Apple_2019.csv

	2.6 Plot_Image: Bar_Plot.png

	2.7 Plot Observations: The downloaded data file 'Apple_2019.csv' from Data Source [1] gives state-wise, market-wise, and variety-wise wholesale prices of apple in INDIA for the year 2019. The data is contributed by Department of Agriculture, Cooperation & Farmers Welfare [2] and Ministry of Agriculture & Farmers' Welfare [3]. The data shows the wholesale maximum price, minimum price, and modal price. The modal price is considered because it accounts for the most frequent price value. From the data given, I have calculated the average modal prices of apples per state. From the plot Bar_Plot.png, the x-axis shows the 'state' of INDIA and the y-axis shows the value of 'average modal price' in wholesale rate for a given state. The plot shows that the 'average modal price' in wholesale rate for each state except 'Goa' lies within 20000 rupees. States except 'Goa' has wholesale 'average modal price' in the range of  2791 to 17111 rupees. Goa, Andaman and Nicobar, and Mizoram rank first, second, and third in highest wholesale 'average modal price' of apples respectively. The Jammu and Kashmir state show a very low 'average modal price' compared to other states as it is one of the major apple-producing states in INDIA. The plot also signifies an increase in the rate of apples modal prices with an increase in distance from Jammu and Kashmir state. The plot shows extensively very high prices for apples in Goa compared to rest states. On verification from the data set, it was observed that the modal price of apples in Goa ranges from 81000 rupees to 148000 rupees. From the data analysis through the plot, it can be seen that the Northern states such as NCT of Delhi, Punjab, Himachal Pradesh, Haryana, UP has 'average modal price' ranging between 5500 to 7200 rupees, which is low compared to rest states. The North-Eastern state such as Tripura and Mizoram and Southern states such as Karnataka and Kerela has high 'average modal price' compared to other most states. The apple modal prices plot shows low value for the Northern states, a bit high value for the eastern and western state and then relatively very high values for North-Eastern, and Southern states.

	2.8 References:

		1. Variety-wise Daily Market Prices of Apple 2019
		   https://data.gov.in/resources/variety-wise-daily-market-prices-apple-2019

		2. Department of Agriculture, Cooperation & Farmers Welfare
		   http://agricoop.nic.in/

		3. Ministry of Agriculture & Farmers' Welfare
		   http://agriculture.gov.in/


3. BOX PLOT:

	3.1 Folder: BOX_PLOT

	3.2 Data Source: https://data.gov.in/resources/variety-wise-daily-market-prices-apple-2019

	3.3 Python_File: box.py

	3.4 Data_Source_Filename: Apple_2019.csv

	3.5 Operating Instructions: The box.py file accepts Data_Source_Filename from command line arguments. 
		So, in terminal type: 

		python3 box.py <Data_Source_Filename> , ie.,

		python3 box.py Apple_2019.csv

	3.6 Plot_Image: Box_Plot.png

	3.7 Plot Observations: The downloaded data file 'Apple_2019.csv' from Data Source [1] gives state-wise, market-wise, and variety-wise wholesale prices of apple in INDIA for the year 2019. The data is contributed by the Department of Agriculture, Cooperation & Farmers Welfare [2] and the Ministry of Agriculture & Farmers' Welfare [3]. The data file used for box plotting is the same data file used for bar plotting. The data shows the wholesale maximum price, minimum price, and modal price. From the plot Box_Plot.png, the x-axis shows the 'state' of INDIA and the y-axis shows the value of 'modal price' in wholesale rate for a given state. The modal price is considered because it accounts for the most frequent price value. The box plot shows minimum, maximum values and Interquartile Range (IQR) along with outliers. From the plot Box_Plot.png, the shaded light pink regions denote the IQR, and the peach-colored circle denotes the outliers. The box plot shows the distribution of modal prices in the wholesale rate of apples for a given state. The distribution of modal prices is more uniform in states of Jammu and Kashmir, Jharkhand, Kerela, NCT of Delhi, and Uttarakhand with no or very few outliers. For the state of Goa and Mizoram, the modal prices of apples are usually high than their median as can be seen from the plot. More variance amongst prices can be seen in such states. Similarly, for Andaman & Nicobar and Telangana, the modal prices of apples are low than their median. A high number of outliers can be seen for Haryana, Punjab, Rajasthan, Himachal Pradesh, Madhya Pradesh, and Maharastra symbolizing very high rates than the median. A high number of outliers can be seen for Uttar Pradesh, Karnataka, and Jharkhand symbolizing very low rates than the median. From the Bar_Plot.png, we witnessed that the wholesale average modal price except 'GOA' was always less than 17500 rupees. Form Bar_Plot.png we didn't get an intuition about the wholesale modal price distribution of apples in a state. But from the Box_Plot.png, we witnessed that the wholesale modal prices of apples sometimes cross 20000 rupees, especially in Mizoram state, and some of the state outliers. Hence, this gives a better analysis of the distribution of apple prices in a state rather than just considering the average of modal prices in a state. The bar plot shows a much better view of the distribution of wholesale modal prices compared to the median as shown in Normal Distribution.

	3.8 References:

		1. Variety-wise Daily Market Prices of Apple 2019
		   https://data.gov.in/resources/variety-wise-daily-market-prices-apple-2019

		2. Department of Agriculture, Cooperation & Farmers Welfare
		   http://agricoop.nic.in/e bx 

		3. Ministry of Agriculture & Farmers' Welfare
		   http://agriculture.gov.in/