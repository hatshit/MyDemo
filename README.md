# News Reader App

Create a simple Android application that displays a list of news articles fetched from a public API. Users should be able to view the details of each article by clicking on it.

## Latest 
Use Kotlin as the programming language.
Follow MVVM (Model-View-ViewModel) architecture.
Use the latest stable versions of Android libraries and tools.

## UI Components:
Main screen with a RecyclerView that displays a list of news articles.
Each item in the list should display the article's title, a thumbnail image, and a brief description.
Clicking on an article should navigate to a detail screen that shows the full content of the article.

## Networking:
Fetch the news articles from the News API (You will need to sign up and get an API key).
Use Retrofit for networking.
Display a loading indicator while fetching data.
Handle errors gracefully (e.g., display a message if the network request fails).

## Data Persistence:
Use Room to cache the news articles in a local database.
When the app is opened, first display the cached articles, then update the list with the latest articles from the network.

## Other Requirements:
Use ViewModel and LiveData for managing UI-related data.
Use Data Binding or View Binding.
Write at least one unit test for your ViewModel.

## Bonus:
Implement a search functionality that allows users to search for articles by keyword.
Use Kotlin Coroutines for background operations.

## Installation

1. Clone the repository:![Screenshot 2024-06-14 104705](https://github.com/hatshit/MyDemo/assets/52077080/677c87b0-e191-4a7e-9650-cf08b60f9436)


   ```bash
   git clone https://github.com/hatshit/MyDemo.git
