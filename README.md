# Project 3 - *Flixter Part 1*

**Flixter** shows the latest movies currently playing in theaters. The app utilizes the Movie Database API to display images and basic information about these movies to the user.

Time spent: **17** hours spent in total

## Features

The following **required** functionality is completed:

- [ ] (6pts) **Make a request to [The Movie Database API's `now_playing`](https://developers.themoviedb.org/3/movies/get-now-playing) endpoint to get a list of current movies**
- [ ] (6pts) **Parse through JSON data and implement a RecyclerView to display all movies**
- [ ] (6pts) **Use Glide to load and display movie poster images**

The following **stretch** features are implemented:

- [ ] Improve and customize the user interface through styling and coloring
- [ ] Implement orientation responsivity
  - App should neatly arrange data in both landscape and portrait mode
- [ ] Implement Glide to display placeholder graphics during loading
  - Note: this feature is difficult to capture in a GIF without throttling internet speeds.  Instead, include an additional screencap of your Glide code implementing the feature.  (<10 lines of code)

The following **additional** features are implemented:

* [ ] Show an emoticon for each movie, where it will be sad :( if the rating was bad, :/ if was soso, and happy :) if it has a good rating

## Video Walkthrough

Here are some walkthroughs of implemented user stories:

<img src='walkthroug1.gif' title='Video Walkthrough 1' width='' alt='Video Walkthrough' />
<img src='walkthroug2.gif' title='Video Walkthrough 1' width='' alt='Video Walkthrough' />
<img src='walkthroug3.gif' title='Video Walkthrough 1' width='' alt='Video Walkthrough' />
<img src='walkthroug4.gif' title='Video Walkthrough 1' width='' alt='Video Walkthrough' />


GIF created with [LICEcap](https://www.cockos.com/licecap/).

## Notes

It was an amazing app to learn, my biggest challenge was work with the API. Moreover, in my code are a lot of things that should be optimized like the Map that I'm using in Movies.java, I should find a way to make it an attribute not an static Map.

## Open-source libraries used

- [Android Async HTTP](https://github.com/loopj/android-async-http) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android

## License

    Copyright [yyyy] [name of copyright owner]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
