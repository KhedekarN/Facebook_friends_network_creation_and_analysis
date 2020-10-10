# Facebook_friends_network_creation_and_analysis
The project aims at crawling social media data and performing analysis on the extracted data. The social media platform selected for this is Twitter. Twitter is one of the most well known platforms and extracting the data from it is also simplified by them. They provide Twitter APIs through which we can extract the data. We will further perform analysis on in it and build a friendship network.

In this project, we have taken the list of six influential users to conduct analysis on.
The goal of our project is to build a friendship network between these users using Twitter API.
We have made use of networkX library to calculate the network measures and also plot our network graph.

1. Create a Twitter Developer account.
2. Generate authentication keys (Consumer Key, Consumer Secret, Access Key and Access Secret)
3. Construct a Twitter API and pass our authentication keys to it.
4. Read the users list from the text file candidates.txt where we stored them. 
5. Based on the screen names read, get their twitter user objects.
6. Check the total count of the users friends.
7. Get a list of IDs of the friends that our user follows. We have limited them to 500.
8. For each user, save their friends details in a dictionary particular to the user. The friends are looked upon by using their ID as a key.
9. Calculate the friends overlap between the users.
10.Create an undirected graph of the friendship network using networkX. We selected only the friends who are friends with at least two users.
11.The friendship network is saved in png format in network.png.
12.The degree distribution was calculated suing networkX and a histogram was plotted along with the inset. It is stored as a png in degree_distribution_histogram.png file.
13.Graph properties like Eccentricity, Diameter, Radius, Periphery and center are calculated using networkX.
14.Network measures like Degree Centrality, Eigenvector Centrality, Betweeness and Closeness are calculated using networkX.
15.We finally calculated the shortest paths between all the users.
16.The above measures were used for analysis.


