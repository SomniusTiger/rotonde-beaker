# Rotonde for Beaker Browser

This is an all inclusive Rotonde instance client and server.

## Setup

There is a beginner-friendly setup tutorial available at the following URL: [https://louis.center/p2p-social-networking/](https://louis.center/p2p-social-networking/). See this list for rotonde portals to follow: [https://cblgh.org/rotonde.html](https://cblgh.org/rotonde.html)

## Start

- Write a first message maybe.
- Share your `dat:` url with people, and past theirs to follow them.
- Enjoy!

## Commands

- `dat://000` will follow a portal.
- `undat://000` will unfollow a portal.
- `filter @neauoire` will show your mentions.
- `clear_filter` will clear the filtered feed.
- `edit:name Some_name` will change your display name.
- `edit:desc Some_name` will change your display description.
- `edit:site Some_name` will change your display site.
- `edit:0` will edit your first entry.
- `delete:0` will delete your first entry.

## Icon

To change your display icon, update the SVG file located at `media/images/icon.svg`. The icon should be a square file for it to display properly. Keep it small. If you update your svg manually, don't forget to go to Library->(Your Rotonde Site) and press Review Changes -> Publish, otherwise your changes wont be seen by anyone!

## Rich content

- `TEXT >> MEDIA_NAME.jpg`, will connect a media filename from `/media/content/MEDIA_NAME.jpg`.

## Commands

- `dat://`, to subscribe to a portal.
- `undat://`, to unsubscribe to a portal.
- `edit:name TEXT`, to update your portal name.
- `edit:desc TEXT`, to update your portal description.
- `edit:site URL`, to update your portal website.
- `edit:ENTRY_ID TEXT`, to edit an entry.
