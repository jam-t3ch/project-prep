# Software Requirements

---

## Vision

### What is the vision of this product?

* Our vision for Daily Jam is a multi-purpose application with different features loosely based around JAM puns. These will include entertaining and useful functionality using APIs.

### What pain point does this project solve?

* Trying to solve boredom and lack of jam-based content in people’s lives. People should have an amusing hub to also get useful information. Allow users to find news, weather, food recipes, up-to-hour traffic info, and more in an enjoyable, jam-themed (purple-ish color theme/palette), intuitive format.

### Why should we care about your product?

* In an over-stimulating world demanding our attention is spread too thin, Daily Jam app will stimulate the users mental taste-buds and leave them satisfied.

---

## Scope (In/Out)

### IN - What will your product do

* The application will provide information to the users about weather, news, and other info local to their area or other areas of interest.

* The application will use OAuth to persist personal data and unlock full CRUD capabilities with database.

* User will be able to interact with at least three separate pages where two allow user input to comment on.

* Application will be designed to render dynamically for mobile-first functionality.

### OUT - What will your product not do

* Will not be providing navigation if traffic services are implemented.

* Will not display full news articles.

---

## Minimum Viable Product vs

### What will your MVP functionality be?

* User can login through OAuth to persist personal data and unlock full CRUD capabilities with database.

* User can interact with at least three separate pages where two allow user input

* Application will include access to at least one external API.

* After a user logs in, they can write a daily reminder or other modifiable input that will persist associated with their email.

* Application designed to render dynamically for mobile-first functionality.

---

## stretch goals

### What stretch goals are you going to aim for?

* light/dark mode functionality themed to a light and dark jam.

* User presented with share location button feature sends the GET requests based on their location similar to how we are prompted for current location from websites.

* Implement more external APIs to five user more functionality from homepage.

---

## Functional Requirements

### List the functionality of your product. This will consist of tasks such as the following

* A user can login and see their profile information.

* A user can search their city and see  their weather data.

* A user can add/update/delete user notes and see them rendered on-screen.

* A user will have their contributions persist on their associated login.

### Data Flow

![Daily Jam App Data Flow](/DataFlow.png "Daily Jam App Data Flow")

---

## Non-functional requirements are requirements that are not directly related to the functionality of the application but still important to the app

1. Security will be used through OAuth.

2. Simplicity for user.

3. Componentize the application so we can add later functionality with ease.

For the second we want the user to have a default enjoyable view. We'd like the app to be very intuitive based on what they see on their phones OS home screen, this way using the app will be simple.

For the third, we will have everything existing in React-Bootstrap Card components on homepage as buttons and displaying modals. For this reason adding a functional button into card grid and having it's functionality be nested within will make adding to app very simple.
