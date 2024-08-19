# HarmonyHub

<br>App is live at https://harmonyhub-1-61up.onrender.com/index.html<br>

## Establishing connection with Spotify's O-Auth Protected API

![Spotify - O Auth Workflow](https://github.com/ThisMonkeysGoneToHeaven/HarmonyHub/assets/32913413/bee16dab-4684-4ad0-950a-578caa23a9b3)

### Things to add

1. Sample .env file <br>
2. Setup separate enviroments for prod and dev<br>
3. New Yahoo Email with name HarmonyHub<br>
4. Spotify Accounts should be unique for all users <br>
5. Implement Redis Based Caching to store user's spotify data for next 24 hours. Try utilising the CachingDecorator to achieve this. <br>
6. De-couple the currently present Email-Password based sign in option from the App.
7. Provide Spotify-Sign-Up option.
8. Design and implement a framework which allows the developer to add/remove sign up methods on a whim. Spotify sign-ins will always be present but maybe I want to have the email-based sign in as well, or not.
9. If you're using a free plan for GEN-AI, make sure that you show an error message that let's people know upfront that they won't be able to generate content untill HH:MM hrs.

-> Class Diagrams for the backend models <br>
-> Session Management Diagram for HH <br>

### Plans

Eventually play around with interesting System Designs <br>
Use decorator pattern to support different caching mechanisms
Google Gemini para generate making fun of user's music taste <br>
Think about followers and following and how it's going to be implemented <br>
Think about how will the feed of common artist be generated <br>

### Further Explorations and Improvements

Think about implementing an external rate limiter wherever required. Currently rate limiting email requests sent within five minutes, move this functionality to external limiter. <br>
Allow user to send more than one emails for activation link or password reset within the specified duration <br>