# WeeklyAssTravelWebSite   https://tejaskarde21.github.io/WeeklyAssTravelWebSite/TravelWeeklyTest/index.htm

The task was to get fetch API from RapidAPI to make a travel app like hotel.com.
where API consists of city code contryCodeImage, and customer review.
So to fetch that API I get a code from rapid API we want to copy that source code to js.

Then some error occurs of awaiting so to resolve it:-
We take that URL in the try-catch block.
that put a condition if that response of URL is ok then get that converted JSON data to the console to check  the response.

we get all the HTML tags to the JS by using the document to get the element.

*filterDataByName(name): This function takes a name parameter and is designed to filter data based on the provided name. Here's how it works: 
     -If the name parameter is empty or false, it returns the entire jsonData object, 
      effectively displaying all countries' data.
     -If a non-empty name is provided, it filters the JSON data object to find matching 
      countries by their country code (case-insensitive match). 
     -It constructs a new object containing only the matching data and returns it.

*displayFilteredData(filteredData): This function is responsible for displaying the filtered data on a web page. It performs the following steps:
       -Clears any previous results in the card container (assuming the card container is a valid 
        HTML element).
       -If the filtered data object is empty (no matching countries), it displays a message 
        saying "No matching countries found."
       -If there are matching countries in filtered data, it iterates through each country's 
        data and creates a "card" element for each one.
*Each card includes:
       -An image displaying the country's image (using the URL from the countryData).
       -The country code.
       -A customer review.
       -A date (which appears to be coming from an HTML input element with the id "date").
       -A star rating (displayed as stars using Font Awesome icons).
       -A price.
       
*It appends each card to the cardContainer, effectively displaying the filtered data on the webpage.

**Last when we click a button to search its filterDateByName and display that FilterData.
