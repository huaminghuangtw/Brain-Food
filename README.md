# Brain Food

## About

> _“Where is the wisdom we have lost in knowledge? Where is the knowledge we have lost in information?” ― T.S. Eliot, [The Waste Land and Other Poems](https://www.goodreads.com/work/quotes/15306654)_

Welcome to Brain Food 🧠—a curated repository of quality content I've discovered across the Internet. Here, you'll find a personal collection of _articles_, _books_, _podcasts_, _movies_, _TV shows_, and _YouTube videos_ that I've [bookmarked](https://huami.ng/bookmarks) over time.

In today's world of information abundance, we're constantly bombarded with information—fast, [endless](https://perell.com/essay/never-ending-now/), and often driven by algorithms. Most of what we consume is either created within the last 24 hours or recommended by “For You” feeds.

> _“I consider that a man's brain originally is like a little empty attic, and you have to stock it with such furniture as you choose. A fool takes in all the lumber of every sort that he comes across, so that the knowledge which might be useful to him gets crowded out, or at best is jumbled up with a lot of other things so that he has a difficulty in laying his hands.” — Sherlock Holmes_

Your information diet shapes your mind as much as your food shapes your body—the quality of your inputs determines the quality of your thoughts. In an age of information overload, you're not the average of the five people you spend the most time with, but the five information sources you consume most.

What you read, watch, and listen to is as important as what you eat. Your digital environment influences your thinking just as much—_if not more_—than your physical surroundings. Remember that.

Let this repository inspire you to be intentional about what you're feeding your brain. Instead of depending on algorithms, take control and decide what deserves your attention. Choose wisely. Brainwash yourself with [greatness](https://www.thelindylibrary.org/).

## How I Built This Project

I used [ Apple Shortcuts](https://shortcutomation.com/gallery/brain-food/) to gather detailed metadata for each list in [Reminders](https://support.apple.com/en-au/guide/reminders/welcome/mac), leveraging the following APIs, and then [exported the results to JSON files](https://shortcutomation.com/gallery/brain-food/share-brain-food/):

1. **[Movie & TV](https://huami.ng/bookmarks/movie-tv-shows)**
	* [The Movie Database (TMDb) API](https://developer.themoviedb.org)
2. **[Podcast Episode](https://huami.ng/bookmarks/podcasts)**
	* [Spotify Web API](https://developer.spotify.com/documentation/web-api)
3. **[YouTube Video](https://huami.ng/bookmarks/youtube-videos)**
	* [YouTube API](https://developers.google.com/youtube/v3/getting-started)
4. **[Book](https://huami.ng/bookmarks/books)**
	* [Google Books API](https://developers.google.com/books/docs/overview)
	* [Open Library API](https://openlibrary.org/developers/api)
	* [Library of Congress (LoC) API](https://www.loc.gov/apis)
5. **[Essay](https://huami.ng/bookmarks/articles)**
	* [Safari Reading List](https://support.apple.com/en-euro/guide/iphone/iph1a4721132/ios) [^1]

For a quick preview of these lists, explore the [demonstration shortcut](https://shortcutomation.com/gallery/shared/brain-food/), which will deliver a random "Brain Food" directly to your Lock Screen.

<p align="center">

| ![](assets/notification.png) |
| :-: |

</p>

## Contribution

Contributions are welcome! Please [open an issue](https://github.com/huaminghuangtw/Brain-Food/issues/new) or [submit a pull request](https://github.com/huaminghuangtw/Brain-Food/compare).

[^1]: For read-it-later essays, I simply [exported the reading list items in Safari](https://shortcutomation.com/gallery/brain-food/export-safari-reading-list/). No API calls here.
