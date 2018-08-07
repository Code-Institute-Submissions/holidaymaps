# Holiday Maps 

Holiday Maps is a one page website designed to allow one to search for a holiday destination. The website displays items of interest on the map to the user, lists these items in an accordian drop down to the right, and upon selection of an item displays photos and ratings of that item beneath. The Holiday Maps project is intended to give users a good idea of the main attractions of a destination before one travels there.
 
## UX

I designed a wireframe on paper before I designed the web site. I then transferred it over to a digital copy using Pencil. The wireframe is located in the UX folder, called holidayux.png.

- The user initially is presented with an embedded google maps. The map displays the world, so the user knows that they can search for any location in the world, that is available on google maps. 

- The user is also presented with a search bar, to activate the search. I have written my home town in the map search bar, as an example of how it should be used.

- A loading screen is presented to the user, after the user initiates a search. Google Maps and Google Places only allow a number of requests per second, and so it takes some time for the search to complete and retrieve all the data. I felt the loading screen was a good feature to add - so the user knows how long left to wait until the search is complete.

- Rather than output all the results on a page, I neatly placed them according to three topics using an accordian drop down. Initially, the accordian is empty, as no results have been retrieved, but after the results are retrieved, the accordian drop down is populated using the three headings, 'Tourist Attractions', 'Accomodations' and 'Restaurants'.

- The results of the search are also displayed as markers on the goggle maps display. The user can zoom in and out and see the markers of the items retrieved. Selecting a marker reveals its name.

- The results in the accordian drop down can be clicked too. Clicking an item in one of the accordian drop downs, zooms the google maps into the marker, and also displays photos, information and ratings of that place beneath the google maps and accordian drop down.


## Features
 
### Existing Features
- Search and find feature - this feature allows a user to search a location and return items of interest
- Photos and ratings - this feature allows a user to select an item that is found, and have displayed it's location in google maps, photos, ratings and reviews.
- Spinner to display loading

### Features Left to Implement
- A search feature would be another great feature to implement so a user can narrow the selection of results returned.

## Technologies Used

- [Javascript]
    - This project used javascript extensively for implementing the website

- [Google Maps Javascript API] ( https://cloud.google.com/maps-platform/ )
    - Used to display what is searched

- [Google Places Javascript API] (https://cloud.google.com/maps-platform/places/)
    - Used to retrieve places of interest and their details

- [JQuery](https://jquery.com)
    - Used by other libraries

- [Bootstrap] (https://getbootstrap.com/)
    - HTML/CSS library used

- [iOSOverlay Spinner] (https://taitems.github.io/iOS-Overlay/)
    - A library used to display a progress spinner


## Testing

The website was extensively tested. There was no automated tests that were created, as it is mostly a graphical web site, but it was tested feature by feature and as a whole together. Testing was done by confirming the output and each feature working as expected on the web site.

1. Search and find feature - 
    1. Enter a destination in the search field and hit search
    2. Google maps and the results should reflect the searched field submitted

2. Loading progress spinner
    1. Search for a location
    2. The spinner should display the progress and confirm when finished and present the results after it is finished in a timely manner.

4. Accordian dropdown
    1. Search for a location
    2. The results should be reflected in the accordian dropdown under each feature.
    3. Click on the header to expand the results

3. Photos and ratings
    1. Click on an item in the accordian dropdown.
    2. The name and location should be displayed and the map zoomed in to the location
    3. Photos and ratings should appear beneath the map.

The website was tested on different screen sizes using the google chrome and internet explorer developer tools. Also, tested on a notebook, laptop, phone and samsumg pad.

One problem during testing was that the google maps sometimes did not load when the page was loaded initially. A page refresh was needed in this case to reload it. I could not isolate the issue with this.

## Deployment

Deployed on github:

https://andrew-carton.github.io/holidaymaps/


## Credits

### Content
- Google maps and places for the content

### Media
- All media is retrieved from Google but photos and reviews have been submitted by users of google.

### Acknowledgements

- I wish to acknowledge the website Stack Overflow, for its abundant questions and answers by users that helped implement this website.
