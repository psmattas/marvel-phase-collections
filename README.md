# Marvel Phase Collections

*Story-order Jellyfin collection artwork for the road to Avengers: Doomsday.* It comes in two versions, plus 3 bonus sets.

![Doomsday Essentials](Doomsday%20Essentials/Previews/posters_1-7.jpg)

| Folder | What it is |
|---|---|
| [**Doomsday Essentials**](Doomsday%20Essentials/) | 13 phase collections + a playlist. Only the essential and recommended titles (54), with credits-scene placement. |
| [**Complete Watch Order**](Complete%20Watch%20Order/) | 15 phase collections and all 137 entries: Fox X-Men, Sony Spider-Man, Netflix/ABC shows, One-Shots. |
| [**Dynamic Collections**](Dynamic%20Collections/) | Bonus: Most Watched This Week · Trending · Rewatch. |

Each folder's README has its full watch order (collapsible per phase).

<details><summary><b>Bonus: Most Watched This Week · Trending · Rewatch</b></summary>

![Bonus posters](Dynamic%20Collections/preview.jpg)

</details>

## Download

Use the green **Code → Download ZIP** button at the top of this repo, or clone it:

```
git clone https://github.com/psmattas/marvel-phase-collections.git
```

Every set comes with **poster, backdrop, landscape/thumb, logo and banner** in Jellyfin's naming (`poster.jpg`, `backdrop.jpg`, `landscape.jpg`, `logo.png`, `banner.jpg`), so they also work for Emby/Plex with a quick rename.

## How to use (Jellyfin)

1. Create the collections. Name them `Marvel 01: Legacy: Before 1950` and so on, so they sort in order.
2. Open each collection → ⋮ → *Edit Images* → upload each file. Or drop the files into `config/data/collections/<Collection Name> [boxset]/`.
3. **Ordering tip:** Jellyfin collections sort by name or date, not by a custom order. Set each item's *Sort Title* to `Marvel 001 - …`, `Marvel 002 - …` (the numbers in the lists), and set the collection's display order to *Sort Name*. For shows, add the individual **season** to the collection, not the whole series, so each season sits in its own phase.
4. **Playlist (Doomsday Essentials):** create a playlist named `Marvel: Doomsday Watch Order`, add the titles in list order (episodes for shows), and upload the art from the `Playlist - …` folder.

---

Watch order based on marvelwatchlist.com (story order). Backdrops and logos from fanart.tv / TMDB. Fonts: Anton, Bebas Neue, Oswald (SIL OFL). Fan-made, not affiliated with Marvel or Disney.
