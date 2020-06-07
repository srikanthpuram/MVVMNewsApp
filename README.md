# MVVMNewsApp
This Android application displays list of news artciles for a country.
This app has 3 tabs in Home Screen,Breaking News, Favourites, and Search News Fragment.
When the app is loaded, the breaking news are fetched from rest webservices (using Retrofit)
and displayed in the RecyclerView.
The favorites tab displays the news artcicles made favorurites, by selecting the FAB in the Articles details page,
swipe to delete and undo is implemented for favourites.
The Search View tab, displays a search list of news for the searched item.
The News Artcile is displayed ina WebView.
Technologies used: Android Jetpack (MVVM, Room) Kotlin, Retrofit
