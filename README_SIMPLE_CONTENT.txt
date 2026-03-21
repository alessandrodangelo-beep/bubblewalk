Bubble Walk simple content setup

Files:
- index-simple.html
- photos-simple.html
- content.js

How it works:
- Put all three files in the same site folder.
- The home page and photos page both read their editable content from content.js.
- To change the next walk details, edit the nextWalk section in content.js.
- To change the photos page, upload image files into your /photos folder and then update the paths inside photosPage.featured and photosPage.gallery in content.js.

What you edit:
1. nextWalk.headline
2. nextWalk.day
3. nextWalk.date
4. nextWalk.time
5. nextWalk.duration
6. nextWalk.meetingPoint
7. nextWalk.meetingMapsUrl
8. nextWalk.routeMapsUrl
9. nextWalk.footerText
10. photosPage.featured
11. photosPage.gallery

Important:
- This is not a backend and not a CMS.
- You still upload images manually to the website.
- But almost all recurring text/photo references now live in one file only: content.js
