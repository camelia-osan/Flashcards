# Flashcards
HTML and CSS web project


### Description
*Flashcards* is a web project with small note cards with countries and capitals used for testing and improving memory. The cards are two-sided, with a country on one side and the capital on the other. 

By default, 9 countries (Mexico, Papua New Guinea, Iceland, South Korea, Sweden, Georgia, Honduras, Tunisia and Austria) are showed. In order to be able to see the capitals of each country, the user simply has to hover the card of the desired country. On release, it turns back to the country face.

### Tools
For this project, I wrote by hand both the structure using *HTML5* and the design using *CSS3*.

- HTML
  
The whole content is fitted in a big container that wraps three smaller containers that represent the columns. Each column has three countries with their capitals.

- CSS
  
The cards represent containers that are styled using *Flexbox*. I used relative measurement units for better screen compatibility.

To make the flipping effect possible, I used the *transform* property. Both card faces are positioned in the 3D space while rotating to 180deg when the user hovers the card. The backface visibility needs to be hidden in order to show the main sides of both countries and capitals when hovering. Stacking the faces correctly is possible due to the *z-index* property. Also, I used a 1000px perspective and 1s linear transition for a smooth animation effect.

The screen compatibility for phones, tablets and large screens, portrait and landscape is covered by the media queries.
