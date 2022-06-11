<div align="center">

  ![Cat Pedigree](https://github.com/cat-pedigree/.github/blob/main/assets/images/cover.jpg)

  <h1>Cat Pedigree</h1>
   
<h4>
    <a href="https://github.com/cat-pedigree/app/">Mobile Development</a>
  <span> · </span>
    <a href="https://github.com/cat-pedigree/CatPedigree_ML_Model">Machine Learning</a>
  <span> · </span>
    <a href="https://github.com/cat-pedigree/">Cloud Computing</a>
  </h4>
</div>

<!-- Table of Contents -->
# :notebook_with_decorative_cover: Table of Contents

- [Repository](#repository)
  * [Machine Learning](#machine-learning)
  * [Mobile Development](#mobile-development)
  * [Cloud Computing](#cloud-computing)
- [Team](#team)

<!-- Repository -->
## Repository

<!-- Machine Learning -->
### Machine Learning

<!-- Mobile Development -->
### Mobile Development
You can see all the mobile development code in the repository https://github.com/cat-pedigree/app

#### User Interface
|  ![User Interface](https://github.com/cat-pedigree/.github/blob/main/assets/images/ui/1.png) | ![User Interface](https://github.com/cat-pedigree/.github/blob/main/assets/images/ui/2.png)  |
|---|---|
| ![User Interface](https://github.com/cat-pedigree/.github/blob/main/assets/images/ui/3.png)  | ![User Interface](https://github.com/cat-pedigree/.github/blob/main/assets/images/ui/4.png)  |

#### How to clone this project
- You can clone the Cat Pedigree App repository to download the zip file from this repository, or by running the git command on android studio:
```bash
git clone https://github.com/cat-pedigree/app.git
```
- Open In Android studio
- Please wait gradle project synchronization

#### How to Get Google Maps API key
how to get Google Maps API key? Don't worry, Android Studio will provide a link that you can directly use to create a project in Google Console and get an API Key for Google Maps.
- First, sign in to the Google Cloud Console and go to the Credentials tab.
- Check and click AGREE AND CONTINUE to agree to the Terms of Service.
- Then go to the side menu and select API & Services → Credentials.
- Create a new project by clicking CREATE PROJECT and changing the project name to your liking. Click CREATE to continue.
- Next, activate the Google Maps feature by selecting Enabled APIs & Services on the side menu and clicking the + ENABLED APIS AND SERVICES button.
- Various features will appear that you can use in the Google Cloud Console. Select Maps SDK for Android and click Enable.
- Then select the Credentials menu on the side menu and click the CREATE CREDENTIALS → API key button to create a new credential.
- At this point, you have got a key that usually starts with the word “AIza…”. Actually you can already use this API key, but this key is still not secure because any project can use it. To be more secure, click the Edit API key link.
- Select the Android apps checkbox under Application restrictions and add new data by clicking ADD AN ITEM. Then fill in the package name of your application and SHA-1 of the device used.
Notes:
Each device has a different SHA certificate. To get SHA-1, you can run the command gradlew signingreport on Terminal
- Setelah usai, klik SAVE dan copy key dengan awalan “AIza…” yang sudah didapat ke meta-data pada AndroidManifest berikut.
```xml
  <manifest xmlns:android="http://schemas.android.com/apk/res/android"
    package="com.catpedigree.capstone.catpedigreebase">
    <application
      ...
        <meta-data
            android:name="com.google.android.geo.API_KEY"
            android:value="YOUR_API_KEY" />
    </application>
    ...
</manifest>
```

<!-- Tech Stack -->
#### Tech Stack

 - [Kotlin](#)
 - [Tensorflow Lite](#)
 - [Retrofit](#)
 - [Room](#)
 - [Room Paging](#)
 - [Camerax](#)
 - [Datastore](#)
 - [Gson](#)
 - [Glide](#)
 - [Navigation Dynamic](#)
 - [Viewmodel](#)
 - [Live Data](#)
 - [Navigation UI](#)
 - [Constraint Layout](#)
 - [Circle Image](#)

#### Prerequisites

- Android 9.0 (Pie) API 28
- Internet Connection
- Camera
- GPS

#### Installation

- Download the APK
- Install the APK
- Create a new account
- Login
- And then run all the features in the application

<!-- Cloud Computing -->
### Cloud Computing

<!-- Team -->
## Team

| ID         | Name                    | Contact |
|------------|-------------------------|---------|
| M7269J2321 | Bugi Sulistiyo          | <a href="https://www.linkedin.com/in/bugi-sulistiyo/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a> <a href="https://github.com/Bugi-Sulistiyo"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" /></a>         |
| M2272J2364 | Zahrizhal Ali           | <a href="https://www.linkedin.com/in/zahrizhal-ali/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a> <a href="https://github.com/ZahrizhalAli"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" /></a>         |
| M2208K1922 | Wardatun Sayyidah       |<a href="https://www.linkedin.com/in/wardatun-sayyidah/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a> <a href="https://github.com/wardatunsayyidah"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" /></a>          |
| A2152G1665 | Robby Ramadhan Anshory  | <a href="https://www.linkedin.com/in/robby-ramadhan-anshory-99b338228/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a> <a href="https://github.com/RobbyRamadhanAsnhory"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" /></a>         |
| A7314F2733 | Budi Setiawan           |<a href="https://www.linkedin.com/in/budi-setiawan15/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a><a href="https://github.com/budistwn15"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" /></a>          |
| C7312F2682 | Fina Enno Rizki Oktavia | <a href="https://www.linkedin.com/in/finaenno/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" /></a><a href="https://github.com/finaenno"><img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" /></a>         |
