# Scotland's Places - OS Name Books Scraper

This project contains a Python script that scrapes place name data from the Ordnance Survey Name Books on the Scotland's Places website.

## Description

The script uses the `httpx` library to send HTTP requests and the `selectolax` library to parse the HTML responses. 
It navigates to the page for each volume of the Ordnance Survey Name Books, extracts the place name data from the page, and stores the data in a structured format. The data is then written to a CSV file. The goal is to make the data more accessible and easier to work with regards to data analysis and visualisation.

## Getting Started
Currently, the script is designed to scrape the data for the 1st Volume Ordnance Survey Name Books for the county of Lanarkshire. To change this you will need to update the base_url. To get valid base_url you can navigate to the Scotland's Places website, here https://scotlandsplaces.gov.uk/digital-volumes/ordnance-survey-name-books click on which county you want from there you will be taken to that county's available volumes. Select the volume you want to scrape. The base_url will be the URL of the page for that volume. The base_url should look something like this: https://scotlandsplaces.gov.uk/digital-volumes/ordnance-survey-name-books/lanarkshire-volume-01

## Contributing
Contributions are welcome! Please feel free to submit a pull request.

## License
This project is licensed under the MIT License.

## Acknowledgments
- Thanks to the Scotland's Places website for providing the data. https://scotlandsplaces.gov.uk/digital-volumes/ordnance-survey-name-books
- Colin https://github.com/dgplacenames for the inspiration
- John Watson Rooney for his tutorials and discord. https://www.youtube.com/channel/UC8tgRQ7DOzAbn9L7zDL8mLg
