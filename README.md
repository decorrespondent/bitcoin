# Cryptocurrency research

This repo contains some notebooks and code for our project on cryptocurrencies. The project is divided in several parts. 

1. Market data
2. Crime data

## 1 Market data

Here you will find some notebooks with market data on cryptocurrencies. There are a couple of data aggregators in the cryptocurrency space that provide API access to a wealth of market, coin and token data. This data can be used to get a sense of how the market works, the parties involved and the wider ecology of the cryptocurrency space. 

There is still a lot to do. These are the most important and obvious steps:
1. Gather more data on mining and energy consumption.
2. Visualize the ecosystem of exchanges, mixers, miners, developers, and other platforms. And get data on all of these parties.
3. Get market data on pump and dump schemes and price manipulation.

## Crime data

This is a bit of a misnomer, but the idea behind the notebooks are that we can analyze the bitcoin blockchain for fraudulent use of the cryptocurrency. Also - and this is the misnomer part - we try to get more information about people who use bitcoin or other cryptocurrencies as an alternative source of revenue or funding, since they are banned from mainstream platforms like PayPal or Patreon. These people are often right wing political activists and I wouldn't want to suggest that they are involved in criminal activities. The analytical tools are the same though as we use with criminal investigations, so they are part of this branch. 

For the crime data bitcoin research, we use the [BlockSci parser](https://github.com/citp/BlockSci), developed by CITP of Princeton University. You need an Amazon EC2 instance of BlockSci to run this code. Also you need some basic knowledge on the structure of bitcoin transactions.

This code is used for research by De Correspondent into the funding of right wing (alt-right, far right, extremist) activists, but the code should be re-usable for other kinds of investigations.

There are still many things to do. These are the most important and obvious steps:
1. Create a seed list of bitcoin addresses of people and organizations of interest.
2. Cluster all donations made into their bitcoin addresses (outputs).
3. Produce statistics based on these clusters.
4. Find the big donors and get all their other donations. Make a short list of people or organizations of interest.
5. Use OSINT techniques to de-anonymize the donors. 
6. Profit

If you are interested in helping out with any of these steps, please drop me a line.

Some of the code was partly written by Hidde and Alexis of ADC, [Amsterdam Data Collective.](https://amsterdamdatacollective.com/)
