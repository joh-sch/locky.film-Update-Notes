# Update Notes 03-18-2024

This is the March 22nd 2024 development update for locky.film

<br>

## 🚀 New Features 🚀

### Video Project Laurels

Laurel images can now be placed on top of the video project preview elements. 
They are displayed in the preview video overlay, togehter with the project artist and title (fade in when the mouse enters a video project element).
Each laurel is displayed for 3 seconds after which it fades out

<video 
  src     ="https://github.com/joh-sch/locky.film-Update-Notes/assets/39758027/dc373d1d-dd43-49b5-854f-14512079a378" 
  controls="controls" 
  style   ="max-width: 100%;">
</video>

#### How to add & configure a laurel

0. Switch on a video project’s _Laurel_ toggle field.

![00-laurel-toggle](https://github.com/joh-sch/locky.film-Update-Notes/assets/39758027/9fc2dc53-39cd-42ed-8db9-e090bd70a20d)

1. Set the laurel position, width and file field.

A laurel can be positioned in the video element’s corners (top left/right, bottom left/right) or centered along the element’s bottom edge.

Because the laurel images come with different aspect ratios and different levels of detail (some are more intricate than others), it would be
difficult to find a uniform width that works well for all of them (meaning a width that looks good/balanced in relation to the rest of the
site design while also being legible). Hence the width can be gradually adjusted to a value between 10 and 30. The default value is 15, which worked
well for some laurels during testing. Trust your own judgment here and do a couple of tests to find a good size.

![01-laurel-config](https://github.com/joh-sch/locky.film-Update-Notes/assets/39758027/3d216cc7-8aaa-40a4-8fc6-ad3ce98bc29b)

2. A note on the laurel image files

For a consistent placement/layout of the laurels it will be helpful if the laurel image files themselves have
no extra spacing/whitespace around the actual laurel graphic. Any extra spacing included in the file cannot be controlled via code and will be
added to the laurel when it is displayed on top of the preview video and thereby set off spacing intended in the code. If possible, please try
to get files without any extra spacing. In cases where this isn’t possible, feel free to reach out and I can remove the spacing for you.

<img width="90%" alt="02-laurel-no-spacing" src="https://github.com/joh-sch/locky.film-Update-Notes/assets/39758027/279e5063-30c5-4ec4-b901-008000d4fccb">
<img width="90%" alt="04-laurel-w-spacing" src="https://github.com/joh-sch/locky.film-Update-Notes/assets/39758027/df822bc2-c39b-404e-9911-7a5a33155a54">

