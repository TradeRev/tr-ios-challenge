# The challenge
Implement a simple browser of a movie library. The list of movies is available in JSON format and has examples below in API section.
There's absolutely no expectation of pixel perfection, so feel free to use the mocks below as a guidance rather than a final design.
Feel free to use any 3rd-party libraries of your choise, but be ready to justify the reason you pick them.


# Mocks
###List
![](./List.png)
###Details
![](./Details.png)

# API

###List 
`https://raw.githubusercontent.com/TradeRev/tr-ios-challenge/master/list.json` to get the list

###Details
Construct the URL using the template `https://raw.githubusercontent.com/TradeRev/tr-ios-challenge/master/details/{id}.json`, 

i.e. `https://raw.githubusercontent.com/TradeRev/tr-ios-challenge/master/details/1.json`

###Recommended

Construct the URL using the template `https://raw.githubusercontent.com/TradeRev/tr-ios-challenge/master/details/recommended/{id}.json`,

i.e. `https://raw.githubusercontent.com/TradeRev/tr-ios-challenge/master/details/recommended/1.json`

