# Flix

Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

## Flix Part 2

### User Stories

#### REQUIRED (10pts)
- [X] (5pts) User can tap a cell to see more details about a particular movie.
- [X] (5pts) User can tap a tab bar button to view a grid layout of Movie Posters using a CollectionView.

#### BONUS
- [ ] (2pts) User can tap a poster in the collection view to see a detail screen of that movie.
- [ ] (2pts) In the detail view, when the user taps the poster, a new screen is presented modally where they can view the trailer.

### App Walkthough GIF

<img src='https://imgur.com/V8GquJl.gif' width=250><br>

### Notes
Describe any challenges encountered while building the app.
-For the last segment of part 2, the superhero tab, the images in this section were different from what the video had shown. Some tinkering around allowed me to manage to make the superhero tab have at least 2 of the movie poster on screen at a time as oppose to one large poster in the center or all the posters shrunken to a small checkbox size image.
-Other bugs that I've encountered is that after completing the superhero tab, when clicking on a movie's detail and then exiting, I can no longer click on any of the movies for any further detail without having to restart the app.

---

## Flix Part 1

### User Stories

#### REQUIRED (10pts)
- [X] (2pts) User sees an app icon on the home screen and a styled launch screen.
- [X] (5pts) User can view and scroll through a list of movies now playing in theaters.
- [X] (3pts) User can view the movie poster image for each movie.

#### BONUS
- [ ] (2pt) User can view the app on various device sizes and orientations.
- [ ] (1pt) Run your app on a real device.

### App Walkthough GIF

<img src='https://i.imgur.com/Y4F5fa2.gif' width=250><br>

### Notes
Describe any challenges encountered while building the app.
-Cannot use AlamofireImage on Xcode 9.1 for MacOS 10.13 High Sierra, throws up many errors and requires newer versions of Swift not available in 10.13.
