# Instructions

You are building a responsive web application that helps users to see the list of countries and few details about the country.

1. A widget to display the country list
   - Each country should have
     - Its name
     - Its flag (display the icon in smaller size)
     - Population
     - Region
     - Capital
     - "View More" button to display the additional details of the country
2. A widget to display the additional details of the country as below
   - Its flag (should display larger image while viewing the details)
   - Population
   - Region
   - Capital
   - Native name
   - Currencies used
   - Languages
   - Border countries
3. A widget to provide a search option to filter the countries list
   - Filter by countryName
   - If time permits, extend the search based on the region, language and currency
4. If time permits, add pseudocode or an actual example of a unit test
  
## API
*List all countries*

https://restcountries.com/v3.1/all

*Search by*

CountryName - https://restcountries.com/v3.1/name/{name}

Region - https://restcountries.com/v3.1/region/{region}

Language - https://restcountries.com/v3.1/lang/{lang}

Currency - https://restcountries.com/v3.1/currency/{currency}

*Filter the response with required fields*

https://restcountries.com/v3/{service}?fields={field},{field},{field} eg. https://restcountries.com/v3/all?fields=name,capital,currencies
