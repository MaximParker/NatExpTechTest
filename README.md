# NatExpTechTest

Produce a homepage for a fictional brand

    ✅ Must utilise bootstrap for layout
    ✅ Besides bootstrap no other JS libraries can be used
    ✅ Must utilise a separate custom stylesheet that makes a change to the default bootstrap styling
    ✅ Must be responsive and work correctly on differing browser sizes
        ◦ Must work correctly across Edge, Chrome, Safari and Firefox (current versions, support for legacy versions is not required)
    ✅ Must include at least one H1, H2. P, UL and LI element
    ✅ Must include at least one image
    • Must include 2 interactive elements
        ✅ A form field which a user can input their name into
            ✅ On subsequent visits, a users name will be displayed on page
                • This can be handled with local storage or cookies, does not require a back end to be developed
            ✅ Must accept only string input. For incorrect data values, an error message must be displayed
        ✅ A form field which takes a users input and asynchronously calls an external API, processes the response and displays some data from the response on page. Response errors should be handled gracefully and display a clear text error message to users on page.
            ▪ Any api can be used, the only requirement is that you send a request asynchronously to an external source and process the response for display on page. Any vanilla JS method for this is acceptable. A list of free to use APIs is here https://mixedanalytics.com/blog/list-actually-free-open-no-auth-needed-apis/ or you can find your own.
                • EG: Use the coinbase API to retrieve price of a specific cryptocurrency based on the users input.
                • EG: Use a weather API to retrieve temperature data for a location based on users input
