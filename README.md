# rails-maps-poc

The Application shows the integration of google map with rails application. By using google map api we can calculate distance between two location in kilometers and duration to reach from source to destination.

To use google api we have to generate API key. 

Obtaining an API Key:

All Maps API applications should load the Maps API using an API key. Using an API key enables you to monitor your application's Maps API usage, and ensures that Google can contact you about your application if necessary.

To create your API key:

1. Visit the Google APIs Console and log in with your Google Account.
2. Click the Services link from the left-hand menu.
3. Activate the Distance Matrix API service.
4. Click the API Access link from the left-hand menu. Your API key is available from the API Access page, in the Simple API Access section. Maps API applications use the Key for browser apps.

Courtesy limit of Distance Matrix API service: 2,500 requests/day

Application Setup:

Version:

Rails : 4.1.6
Ruby  : 2.1.2

Steps:

1. Clone the application in your local directory using git clone https://github.com/BoTreeConsultingTeam/rails-maps-poc.git

2. Go to Project Directory and install Application Specific Gems bundle install

3. Start the server.
   rails s
4. open http://localhost:3000 in browser.