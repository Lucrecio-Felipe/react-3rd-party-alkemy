# 3rd Party API integration - React JS

This project is a challenge for Alkemy Labs. It develops an application to create a team of superheroes consuming an external API (Superhero API) and showing different attributes at the individual and consolidated team level.
To enter the site we must authenticate ourselves. This is done by entering the email and password that appear in the placeholders of the Login form. Once we submit, a POST request is made to a url provided by Alkemy, obtaining a token in response if the fields are correct (otherwise an alert is triggered). This token is stored in the localStorage and will allow access to the different routes of the site, otherwise it is always redirected to the Login form.

## Used Libraries and Resources:
  - Axios (peticiones HTTP)
  - Formik and Yup (From validations)
  - React-Bootstrap (styles and responsive grid)
  - React router (for navigation)

## Functinalities:
  - Field validations with personalized messages.
  - Redirects when validating and submitting forms.
  - Distinctive colors (green and red) identifying good or bad orientation of the superhero.
  - Limits on the number of good and bad superheroes that can be added (3 and 3 respectively).
  - Powerstats, average weight and height of the team. The powerstats are always ordered from highest to lowest identifying the team's strengths.
  - Responsive design with bootstrap grid and media queries.
  - Animations when rendering components.
  - Counter of remaining superheroes and subcounter of good and bad guys in total.
  - Logout button to clear the localStorage token.
  - Crash prevention when no results are found when searching for a new hero. A message is displayed.

Jair Felipe De Lima Lucrecio 👨‍💻
