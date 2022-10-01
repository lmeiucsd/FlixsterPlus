# Android Project 3 - *FlixsterPlus*

Submitted by: **Larry Mei**

**FlixsterPlus** is a movie browsing app that allows users to browse movies currently playing in theaters.

Time spent: **12** hours spent in total

## Required Features

The following **required** functionality is completed:

- [x] **Make a request to [The Movie Database API's `now_playing`](https://developers.themoviedb.org/3/movies/get-now-playing) endpoint to get a list of current movies**
- [x] **Parse through JSON data and implement a RecyclerView to display all movies**
- [x] **Use Glide to load and display movie poster images**

The following **optional** features are implemented:

- [ ] Improve and customize the user interface through styling and coloring
- [ ] Implement orientation responsivity
  - App should neatly arrange data in both landscape and portrait mode
- [ ] Implement Glide to display placeholder graphics during loading
  - Note: this feature is difficult to capture in a GIF without throttling internet speeds.  Instead, include an additional screencap of your Glide code implementing the feature.  (<10 lines of code)


## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='movie.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [ScreenToGif](https://www.screentogif.com/) for Windows


## Notes

The app could not be ran at first because the internet permission was denied. I searched up the issue on StackOverflow and found that you need to add a setting to AndroidManifest.xml. At first, I had two movies displayed at each row, but I fixed this issue by reducing the spanCount to 1 in MoviesFragment.kt. 

## License

    Copyright [2022] [Larry Mei]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.