App Engine application for the Udacity training course.

## Products
- [App Engine][1]

## Language
- [Python][2]

## APIs
- [Google Cloud Endpoints][3]

## Setup Instructions
1. Update the value of `application` in `app.yaml` to the app ID you
   have registered in the App Engine admin console and would like to use to host
   your instance of this sample.
2. Update the values at the top of `settings.py` to
   reflect the respective client IDs you have registered in the
   [Developer Console][4].
3. Update the value of CLIENT_ID in `static/js/app.js` to the Web client ID
4. Run the app with App Launcher "RUN" button.
5. Test app with api explorer. Input URL: "http://localhost:8080/_ah/api/explorer"
6. In APIs Explorer page, select left "Service" then choose "conference API" to test Session/WishList Functions.
7. Push "SDK Console" button on App Launcher, there are three useful check point for app debugging.
    * Datastore Indexes
    * Memcache Viewer
    * Task Queues
8. Using App Launcher "Deploy" button to Deploy your application.


[1]: https://developers.google.com/appengine
[2]: http://python.org
[3]: https://developers.google.com/appengine/docs/python/endpoints/
[4]: https://console.developers.google.com/

------
##Project APIs
1. Task1
    * createSession - with workqueue
    * getConferenceSessions
    * getConferenceSessionsByType
    * getSessionsBySpeake
2. Task2
    * addSessioinToWishList
    * getSessionInWishList
    * deleteSessionInWishList
3. Task3
    *getFeaturedSpeaker
    *_setFeaturedSpeaker for main.py to cache workqueue push function

Example App Site: [Link](https://conference-central-w3-160221.appspot.com/)

##Creator
------
Watson Huang (wats0n)
02/22, 2016