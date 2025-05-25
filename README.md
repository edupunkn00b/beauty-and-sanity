# beauty-and-sanity
An AO3 skin and images

## Instructions
To use (the hard way):
1. While logged in to AO3, go to **My Dashboard** -> **Skins** -> **My Site Skins** ->
2. Click **Create Site Skin**
3. Copy/paste all the text from **here-is-the-css-for-the-skin.css** and it there
4. Name it and save
5. You should see it in your Site Skins list. Click **Use**
6. To revert, click **Use** on a different skin or click **Revert to Default Skin**

## Note
There is extra code at the bottom of the CSS that hides statistics so you won't see kudos and hit counts. If you _want_ to see that, remove this section near the very bottom of the css:

```
  #kudos,
    #show_comments_link,
    .bookmark .status .count,
    .series .stats,
    .statistics,
    .stats .bookmarks,
    .stats .hits,
    .stats .kudos,
    .stats-index,
    .work .statistics .bookmarks,
    .work .statistics .hits,
    .work .statistics .kudos,
    .work .stats .bookmarks,
    .work .stats .hits,
    .work .stats .kudos,
    option[value=bookmarks_count],
    option[value=hits],
    option[value=kudos_count] {
      display: none;
    }
```

