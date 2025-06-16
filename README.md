# AP CSP Performance Task
Main Features
1. User Interface for Car Selection
    * The page displays dropdown menus for users to choose:
        * Year of Manufacture (2014–2021)
        * Car Make/Brand (Acura, Tesla, Mercedes-Benz, BMW)
        * Car Model (Sport, Convertible, SUV, Luxury)
        * Car Color (Red, Silver, Black, Blue)
    * There are clear headings and styled labels for each selection.
2. Interactive Search
    * After selecting options, users click the "Search" button.
    * The page displays:
        * An image of the selected car (if available)
        * Details about the car (year, make, model, color)
        * The price of the selected car for the chosen year and make
3. Reset Functionality
    * Clicking the "Reset" button (or the car image) clears all selections and outputs.
4. Car Data Storage
    * The JavaScript holds arrays for:
        * Available years, makes, models, colors
        * Car images (organized by make, model, and color)
        * Car prices for different makes and years
5. Image and Price Lookup
    * When the user searches, the code matches the selected values to find the right image and price.
    * If a specific combination isn’t available (e.g., no image for that make/model/color), it alerts the user.
6. Styling
    * The page has extensive CSS for a visually appealing and organized layout with custom fonts, colors, borders, and spacing.

How It Works
* Dropdowns: Let users pick their preferences.
* Search Button: Gathers the selected inputs, finds matching data, and updates the image and details.
* Reset Button: Resets all fields to their default states.
* JavaScript Functions: Handle looking up images, prices, and details based on user input.
