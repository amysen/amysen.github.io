# images/

Site media, grouped by where it is used so the folder stays tidy as it grows.

```
images/
  site/            profile photo, nav easter-egg gif, social icons, university logos
  publications/    one folder per paper / patent (figures, demo videos)
  projects/        one folder per project in "Recent Projects"
    eth-robotics-summer-school/
    roboracer/
  blog/            thumbnails for blog.html posts
```

Adding a new project: create `images/projects/<project-slug>/`, drop the media in,
and reference it from `index.html` as `images/projects/<project-slug>/<file>`.

Travel photos for the gallery page live separately in `travel_images/`.
