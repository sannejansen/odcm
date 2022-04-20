# <span style="color:orange">Scraping data from KAYAK</span>

For the course Online Data Collection & Management at Tilburg University, our team aims to scrape data from the website kayak.com. KAYAK provides a service that compares airline tickets with one another. When on the explore page, KAYAK provides a set of destinations based on the airport of departure. The purpose of this scraper is to create a dataset in which the suggested destinations based on the airport of departure (the top 10 biggest airports in Europe) become visible in April for a trip duration of five days.

## Top 10: Biggest airports in Europe
The top 10 of the biggest airports in Europe is as follows:
1. London Heathrow Airport, United Kingdom (LHA)
2. Aéroport de Paris-Charles de Gaulle, France (CDG)
3. Amsterdam Airport Schiphol, the Netherlands (AMS)
4. Flughafen Frankfurt am Main, Germany (FRA)
5. Aeropuerto Adolfo Suárez Madrid-Barajas, Spain (MAD)
6. Aeroport de Barcelona-el Prat, Spain (BCN)
7. Istanbul Airport, Turkey (IST)
8. Sheremetyevo International Airport, Russia (SVO)
9. Flughafen München Franz Josef Strauß, Germany (MUC)
10. London Gatwick Airport, United Kingdom (LGW)


In this notebook we will discuss the scraping in three chapters:
1. The preparation before scraping
2. The kayak.com/explore scraper
3. Saving the scraped data in a csv file
