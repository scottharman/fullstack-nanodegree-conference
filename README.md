App Engine application for the Udacity training course.

# Products
- [App Engine][1]

# Language
- [Python][2]

# APIs
- [Google Cloud Endpoints][3]

# Setup Instructions
1. Update the value of `application` in `app.yaml` to the app ID you
2. have registered in the App Engine admin console and would like to use to host
3. your instance of this sample.
4. Update the values at the top of `settings.py` to
5. reflect the respective client IDs you have registered in the
6. [Developer Console][4].
7. Update the value of CLIENT_ID in `static/js/app.js` to the Web client ID
8. (Optional) Mark the configuration files as unchanged as follows:
9. `$ git update-index --assume-unchanged app.yaml settings.py static/js/app.js`
10. Run the app with the devserver using `dev_appserver.py DIR`, and ensure it's running by visiting your local server's address (by default [localhost:8080][5].)
11. (Optional) Generate your client library(ies) with [the endpoints tool][6].
12. Deploy your application.

# Sessions and Speaker implementation
Sessions and Speaker proposed implementation:

[1]: https://developers.google.com/appengine
[2]: http://python.org
[3]: https://developers.google.com/appengine/docs/python/endpoints/
[4]: https://console.developers.google.com/
[5]: https://localhost:8080/
[6]: https://developers.google.com/appengine/docs/python/endpoints/endpoints_tool
