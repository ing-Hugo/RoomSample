# RoomSample
Android application RoomSample
In this practical you build an app that uses the Android Architecture Components. The app, called RoomWordsSample, stores a list of words in a Room database and displays the list in a RecyclerView. The RoomWordsSample app is basic, but sufficiently complete that you can use it as a template to build on.

The RoomWordsSample app does the following:

Works with a database to get and save words, and pre-populates the database with some words.
Displays all the words in a RecyclerView in MainActivity.
Opens a second Activity when the user taps the + FAB button. When the user enters a word, the app adds the word to the database and then the list updates automatically.
The screenshots below show the following:

The RoomWordsSample app as it starts, with the initial list of words
The activity to add a word
Snapshot of the RoomWordsSample app at startup 

Snapshot of the RoomWordsSample app edit activity 

RoomWordsSample architecture overview
The following diagram mirrors the overview diagram from the introduction and shows all the pieces of the RoomWordsSample app. Each of the enclosing boxes (except for the SQLite database) represents a class that you create.

Tip: Print or open this diagram in a separate tab so you can refer to it as you build the code.

![image](https://user-images.githubusercontent.com/68777214/204503075-21d542b6-9ef3-4062-ac3c-09ced4aaccbc.png)

