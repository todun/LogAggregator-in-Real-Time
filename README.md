Complex Event Processor:-Real Time Data Analyzer & Visualizer (CEP - RT) also known as LogAggregatorRT
===
Complex Event Processing is a Distributed, Data Intensive, Real time complex data analysis tool. It continuously ingests & analyses the live data from multiple sources, to derive operational intelligence to identify potential opportunities, risks and any other meaningful event. Data can be analyzed from more than one source, in relation with the other

Data analysis watch lists can be configured on the fly and analyzed, graphs are plotted and shared with other users.

###### Where is it useful

This application is very useful, where time series data is intensive, flowing with high frequency, fuzzy, intelligence has to be inferred in real time as it happens, to identify assertions & patterns and risk

###### Example 1:

By observing the credit card access pattern of a specific user and by comparing each access with his historic access pattern, flag the access as fraudulent or normal, before the transaction is complete or settled.
Example 2:

> On a stock price data feed, by continuously calculating the average price of a specific stock's price against the competitors stock price, we can trigger event if the price is sharply raising/dropping due unexpected event at stock's firm, which can help the trader to decide if he/she has to got long or short on the stock
For more feature details refer Wiki

###### Contributing

Start contributing by cloning the repository, when you are done building a features/fixing, create a pull request

###### To get started, clone the repository to your local

- git clone https://github.com/Surya11111/LogAggregator-in-Real-Time.git


- cd LogAggregatorRT

- npm install
- bower install
- npm start
If you don't have npm and bower , refer to its corresponding installation

PS: If you are trying to do npm insall from a vagrant box, you may have to use --no-bin-install option, like below

    - npm install --no-bin-install

    Unstable version can be found on https://github.com/stackroute/LogAggregatorRT/ i.e our Team repo though its not recommended
