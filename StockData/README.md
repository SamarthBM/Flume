To write python code for getting live stock data using the link provided:


1. Generate API(Application programming interface) key from following link:

	https://www.alphavantage.co/


2. Get the required url and python code for the stock data from following link:

	https://www.alphavantage.co/documentation/#


3. Create a .env file in VS Code and declare your API key to a variable.


4. Create a .py file and paste the code taken from link mention in point 2.


5. Now create a configuration file in cd apache-flume-1.9.0-bin/conf.


6. Run the following command to send the python source to hdfs:

	bin/flume-ng agent –conf ./conf/ -f conf/StockData.conf -n StockAgent -Dflume.root.logger=DEBUG

	Note: Set the configuration file name and agent name accordingly.


7. Open localhost:9870 to see the transferred file:

