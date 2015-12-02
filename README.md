##Sample on updating data into APIGEE 

This sample illustrates how to using Apigee as mBaaS to save data and query data

The sample features the following:

- HTML5 for a simple UI and JavaScript for logic.
- The Apigee JavaScript SDK for access to app services.
- Ionic framework. 

### Prerequisites

To use this sample, you should first:

- Create an app services account, organization, and application.
- Installed Ionic framework
- Have an Android device to test with or configure the Android emulator so that it supports push notifications.

### Configuring the app

When you open the sample in your IDE, do the following before running the project as an Android Application:
Edit the JavaScript code so that it will access your app services account, Make the following changes in assets/www/index.html:
    - APIGEE_ORGNAME: Your Apigee organization. (line 14)
    - APIGEE_APPNAME: The app in your organization. (line 15)
    - Your username/password - line 47

## Screen short

(https://github.com/papaiking/book_app_apigee/blob/master/images/Screenshot_2015-12-01-08-33-56.png)
Create new book page

(https://github.com/papaiking/book_app_apigee/blob/master/images/Screenshot_2015-12-01-23-48-16.png)
Book list