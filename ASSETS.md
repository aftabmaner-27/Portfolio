# Static assets

Everything in this `public/` folder is copied to the site root as-is at build
time. Drop your original portfolio assets here using the exact paths below so
the site references them correctly (the same paths the old site used):

```
public/
├── cv/
│   └── cv_aftab_maner.pdf                     ← "Download CV" / "Resume" button
├── video/
│   └── aftabmaner_android_developer.mp4        ← Hero showcase video
└── img/
    ├── news.png                                ← "News Application" project
    └── port2.jpg                               ← "Android Mobile App" project
```

If an asset is missing, the UI degrades gracefully:

- The hero video falls back to an animated initials card.
- Project images fall back to a branded gradient placeholder.

No code changes are needed — just copy the files in.
