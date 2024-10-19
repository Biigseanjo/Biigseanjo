Amazon Tracker
This is a web scraper designed to track Amazon product prices and send notifications when price drops are detected.

How It Works
Let's demonstrate how this works by tracking a sample product from Amazon.

The URL of the web page of the product that we want to track is given as input to the scraper.

Once the target page has been retrieved by the scraper, it begins to fetch pricing data from the web page every couple of seconds as follows:

The retrieved product prices and corresponding timestamps are stored in a CSV file. Here, you can see the price difference during a time period of 1 day in the highlighted records.

The data from the CSV file is plotted as a live graph. This helps in visualizing the pricing variations over a period of time.

It is also possible to track multiple products prices simultaneously using the scraper.

When a price drop is detected, we are notified of it via email.

Prerequisites
Ensure that you have Python and the following libraries installed:

requests
dataclasses
numpy
time
matplotlib
BeautifulSoup
pandas
datetime
smtplib
csv
re
DictWriter
random
count
threading
os
To install a library, open Powershell and enter

pip install < name of the library >

You can use the following command as well, if you are starting fresh.

pip install -r requirements.txt

Running The Code
Download the files named Web Scraper.py and Live Graph.py
Place them in a separate folder.
Create an empty subfolder named 'data' and place it in this folder. Here's where the CSV files will be generated.
Run the file named Web Scraper.py and then simultaneously run Live Graph.py
You'll now see the live graph being generated from the CSV file data which was scraped from the web.
You can track any Amazon product's prices by replacing the links in the code with your own.
Future Enhancement
The code can be further expanded to track any number of products.
A cloud service can be used to run the script 24/7 for more accurate results.

<!---
Biigseanjo/Biigseanjo is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
