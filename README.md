# project2

CUSTOMER REVIEW

purpose: allow employers / employees to write reviews about customers (good or bad)
    DISCLAIMER: "This application is for entertainment purposes."

HOW TO USE THE APP

Homepage
    -Contains brief description of the app's purpose
    -Logo for Electrified Elephants
    -List of links to other pages:
        -Sign In
        -Register
        -Create Review
        -See Reviews
    

Actions:
    -Register
        -User creates form with name, email, store, and password.
        -Email is sent to inbox
        -Approved and now able to add reviews

    -Sign In
        -User inputs email and password to log on
        -If sign in successful:
            "Sign off" becomes available on NavBar
        -If sign in failed:
            "Error alert"
            "Change Password"

    -Change Password
        -email sent with link to password change page
        -replaces user password from database

    -Add Review
        -insert [Name of store]
        -insert [Headline]
        -insert [Description of experience with customer]
                (X amount of characters useable)
        -insert [Customer rating 1 - 5]
    
    -Post Review
        -Review becomes available on "Reviews" page to be viewed by others


    -Edit Review
        -Poster may go back and change / delete the review

    -Comment:
        -Signed in users comment on posted reviews

Admin Ability
    -Remove review
    
    
CREATING THE APP

Contributers

    -Amanda Neal
    -Chris Dominy
    -Jiji Smith
    -Richard B. Hall
    


Technologies Used

    -Google Books API
    -Axios
    -Bcryptjs
    -Express
    -Handlebars
    -Moment.js
    -MySQL
    -Passport
    -Sequelize
    
Challenges

    -Overcoming Github conflicts and Travis
    -Launching the App
    -Incorporating people's different code
    -Moving HTML and CSS over to Handlebars
    
Future Goals

    -Add a delete review function
    -Allow users to comment on other users’ reviews
    -Some layout and format updates
    -Allow to connect with other users through PM or add them to your “queue”
    
