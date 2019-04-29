# Bootstrap-Portfolio

This project is the second assignment for the Coding Bootcamp at the University of Texas at Austin.

For this project, I used Bootstrap to build my personal website. This website has three separate parts which are About Me, Portfolio and Contact.

# About Me
I graduated from Baylor University with a Bachelor's of Science in Applied Mathematics. 

Currently, I am a Sortation Associate at Amazon and a Mathematics instructor at Mathnasium. 
I chose to pursue the Coding Bootcamp at UT Austin in order to further my skills in software development, and because I aspire 
to become a full stack software engineer in the future. 

Some of my research interests include Artificial Intelligence and Machine Learning. These fields interest me because I aspire to learn more about the systems and tools we interact with daily, figure out ways to improve them, and help create cutting edge applications which will make the world a better place. 

#Portfolio
The portfolio describes projects that I have been working on, both at the Coding Bootcamp and outside of Coding Bootcamp. 

Recently, I worked with three other developers on a CityRank project. 
In this project, we ranked cities throughout the United States based on three factors: Happiness, Affordability and Political Views. 

My primary role in the project was designing and building the algorithm. 
One of my biggest challenges in this project was trying to figure out where to start here. I was originally planning to use a Machine Learning algorithm to predict what would be the best city someone would use. I was planning to compare the Neural Network, Random Forest, or a Gradient Boosting Algorithm to see what would give me the most accurate results. 

After talking to my group about this, they told me that I was way overthinking the algorithm. After looking at the data, Glenn, one of my group members suggested that I needed to only use a simple algorithm based on distance. 

Ultimately, I decided to go with a vector distance calculation. The smaller the distance your preferences were from the city, the better that city would be for you to live in. 

How the Algorithm worked: The user's preference is at a point in three-dimensional space. Each of our three preferences (affordability, politics, and happiness) were on separate axes. In addition, each of our three cities were also represented by a point in 3-space. 

We used the distance formula to calculate the distance from the user's preference vector and a city's attribute vector. 
This formula was used for all 182 cities in our database. 
Each distance was dumped into an array, and this array would then be sorted from least distance to greatest distance. 
The shortest distance would ultimately give us the 'best' match based on those factors. 

