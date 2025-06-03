# **Choosing the Perfect AirBnb**

**Toronto, often called the “financial capital” of Canada, is a hub of tourist activity from all around the globe. Thousands of tourists flock to the city, popularly known as The Six, to experience the wonderful cultural landscape and unique attractions it has to offer.**

**Be it the CN Tower, or Art Gallery of Ontario, or even a day trip down to the Toronto Islands, there is something for everybody to enjoy. In such a vibrant city, tourism plays a big role in bringing in revenue used for keeping the city alive and healthy. This includes things such as hotels and guest accommodations, which offer travellers a comfy stay while visiting.**

**But the question in every newcomer’s mind is: Where to stay? How much rent is too much? Which neighborhoods are safe for tourists? And most importantly, which places are available for rent right away? To answer these questions, I took a dataset from the popular guest accommodations service Airbnb, and started working on creating visualizations which provide clarity on where a potential tourist could look to finding their perfect stay.**

**My dataset contains a little over 21000 entries, describing active listings categorised based on accommodation types: private room, shared room, or an entire home/apartment. A dashboard, focused on combining the highlights of the following visualizations, is an interactive space for viewers to get focused information about various kinds of locations and accommodation types.**

1.  **Average Price Per Neighborhood**

![Average Price Per Neighborhood](https://github.com/ZeroOneKaran/The-Tableau-Theater/blob/main/Viz%201.png)

**First order of business was to map out every listing available based on what the average price of listing per neighbourhood. Barring a few huge outliers such as Palmerston-Little Italy, Clairlea-Birchmount, and the Waterfront Communities, all of the listings lay between an average rental price of \$21 per day to \$8000 per day.**

2.  **Top 15 Most Expensive Neighborhoods**

![Top 15 Most Expensive Neighborhoods](https://github.com/ZeroOneKaran/The-Tableau-Theater/blob/main/Viz%202.png)

**Speaking of expensive, next I drew a bar graph to show the most expensive neighbourhoods to rent a place in. As mentioned earlier, Palmerston-Little Italy, Clairlea-Birchmount, and the Waterfront Communities are the top three most expensive neighborhoods to rent in. The only major outlier in this visualization is Rustic, which exists because it is the only property listed from that neighborhood. These entries, in conjunction with a simple search on the maps, can give renters a better idea on whether they are getting their money’s worth or not.**

3.  **Annual Room Availability Trends**

![Annual Room Availability Trends](https://github.com/ZeroOneKaran/The-Tableau-Theater/blob/main/Viz%203.png)

**The biggest concern with finding an accommodation as a tourist is knowing the times when it is available. To solve this, I created a variable called availability ratio. Availability ratio divides the numbers of days a listing is available by the total number of days over which the dataset is being analysed.**

**The ratio is measured on a scale of 0 to 1. In essence, if the availability ratio is closer to 1, it means the listing is often available, which could probably be because factors such as less popular location, higher pricing, etc. On the other hand, if the ratio is closer to 0, it means that the listing is more frequently booked.**

**As expected, barring outliers, the figure shows a large concentration of more expensive listings closer to 1.**

## **Conclusion**

**As a result of this project, tourists and fellow data readers can get a better idea about the finer details involved in picking a rental accommodation when visiting a tourist destination such as Toronto. With my analysis and interactive dashboard showing insights on each and every locality, viewers can make informed decisions about their next guest experience when visiting this wonderful city.**

