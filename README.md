# Scotland's Places - OS Name Books Scraper

This project contains a Python script that scrapes place name data from the Ordnance Survey Name Books on the Scotland's Places website.

## Description

The script uses the `httpx` library to send HTTP requests and the `selectolax` library to parse the HTML responses. 
It navigates to the page for each volume of the Ordnance Survey Name Books, extracts the place name data from the page, and stores the data in a structured format. The data is then written to a `Pandas DataFrame` for easier data cleaning and formatting, then exported to a `Excel file`. The goal is to make the data more accessible and easier to work with in regards to data analysis and visualisation.

## Getting Started
Currently, the script is designed to scrape the data for the 1st Volume Ordnance Survey Name Books for the county of Lanarkshire. To change this you will need to update the main_url. To get valid main_url you can navigate to the Scotland's Places website, here https://scotlandsplaces.gov.uk/digital-volumes/ordnance-survey-name-books click on which county you want to scrape, the main_url should look something like this: https://scotlandsplaces.gov.uk/digital-volumes/ordnance-survey-name-books/lanarkshire-os-name-books-1858-1861

## Contributing
Contributions are welcome! Please feel free to submit a pull request.

## License
This project is licensed under the MIT License.

## Acknowledgments
- Thanks to the Scotland's Places website for providing the data. https://scotlandsplaces.gov.uk/digital-volumes/ordnance-survey-name-books
- Thanks to Vision of Britain for the list of place names in the gazetteer csv. https://www.visionofbritain.org.uk/
- Colin https://github.com/dgplacenames for the inspiration
- John Watson Rooney for his tutorials and discord. https://www.youtube.com/channel/UC8tgRQ7DOzAbn9L7zDL8mLg
