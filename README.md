The product link: https://www.amazon.ca/Apple-iPhone-128GB-Green-Renewed/dp/B0CMPMTL69/ref=sr_1_2?crid=UXP6U4SCGKRV&dib=eyJ2IjoiMSJ9.txo3w1r9hJwjpQx7HR49HfVUeRn_QiZ_vw99sEI3FV50phLvF58jP8UG3A6msHvDzStGB1OblA9fsraOzrEFDxduW45iOt8ETZPyQbd8iXBHq__Aax0Twnsc1xAHGjyS2LmNcl22YgpROhanNlfJnj4px-mXv-eKeq-ZoUei5Otj65wgcmA2H68ZYFzgdn6bp6RL8rTqlByx4fjIfyHBwHUOWdxnguzPzlJhKriQ6_3PEve03O1FvPIK-N0_A4MoOmLxhPJVF_SFYJmBFXAbeLZokKi_IITVbFKY108wEhc.OAlaNP4H70bkfst4cn1Linu8tTgmrPgOP3IZxaTfuv8&dib_tag=se&keywords=Iphone%2B16&qid=1731290432&sprefix=iphone%2B16%2Caps%2C149&sr=8-2&th=1

Amazon Product Price Tracker
This project is an Amazon product price tracker built with Python. Using the BeautifulSoup library, it scrapes product information 
(such as title, price, and rating) from Amazon. The data is stored in a CSV file for further analysis, and if the product price drops below $1000,
an email notification is sent automatically.

Project Overview

Objective: Track and analyze Amazon product prices over time.

Data Collection: Scrapes product information (title, price, and rating) using BeautifulSoup and stores it in a CSV file.

Notification System: Sends an email alert if the price falls below a specified threshold ($1000 in this case).

Use Case: This project is useful for anyone who wants to be alerted when a desired product falls below a target price.

Features

Web Scraping: Extracts product details from Amazon using BeautifulSoup.

CSV Storage: Saves scraped product information in a CSV file for easy access and analysis.

Email Notification: Notifies the user by email when the product price meets the desired condition (below $1000).

Technologies Used
Python: Main programming language.
BeautifulSoup: For web scraping.
CSV Module: To store scraped data.
smtplib: For sending email notifications.

Email Alert Example
If the price drops below $1000, you will receive an email alert with the following subject:

The iPhone you want is below $1000! Now is your chance to buy!

Disclaimer
This project is for educational purposes. Web scraping Amazon may violate their Terms of Service, and it is recommended to check their policies before using this script extensively.
