# Bus Scheduler App

This folder contains the source code for the Bus Scheduler app codelab.

# Introduction
The Bus Scheduler app displays a list of bus stops and arrival times. Tapping a bus stop on the first screen will display a list of all arrival times for that particular stop.

The bus stops are stored in a Room database. Schedule items are represented by the `Schedule` class and queries on the data table are made by the `ScheduleDao` class. The app includes a view model to access the `ScheduleDao` and format data to be display in a list, using `Flow` to send data to a recycler view adapter.

# Pre-requisites
* Experience with Kotlin syntax.
* Familiarity with activities, fragments, and recycler views.
* Basic knowledge of SQL databases and performing basic queries.

# Getting Started
1. Install Android Studio, if you don't already have it.
2. Download the sample.
3. Import the sample into Android Studio.
4. Build and run the sample.

# Result 
<img width="330" alt="Screen Shot 2021-12-06 at 2 28 59 PM" src="https://user-images.githubusercontent.com/92260200/144838506-e8d6ee49-a765-42b4-9676-4932cc13bff0.png"> <img width="330" alt="Screen Shot 2021-12-06 at 2 28 52 PM" src="https://user-images.githubusercontent.com/92260200/144838521-04aa47c1-2572-40bb-8711-87adfc017662.png">

# Reference 
- https://developer.android.com/courses/pathways/android-basics-kotlin-unit-5-pathway-1#codelab-https://developer.android.com/codelabs/basic-android-kotlin-training-intro-room-flow


