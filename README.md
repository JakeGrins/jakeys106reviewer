# BSIT Exam Reviewer: Sound Effects

Audio files for the **BSIT Exam Reviewer** website.

---

## Folder structure

```
.
├── README.md
└── sounds/
    ├── ui/              # buttons, navigation
    │   ├── click.mp3
    │   └── open.mp3
    ├── quiz/            # normal quiz rounds
    │   ├── correct.mp3
    │   ├── wrong.mp3
    │   ├── streak.mp3
    │   └── complete.mp3
    └── timed/           # upcoming timed quiz gizmo
        ├── start.mp3
        ├── tick.mp3
        ├── warning.mp3
        └── timeup.mp3
```

## Sound list

| File | Plays when | Length |
|------|------------|--------|
| `ui/click.mp3` | Any button click (menus, tabs, answer choices) | under 0.2 s |
| `ui/open.mp3` | Donate popup opens | under 0.5 s |
| `quiz/correct.mp3` | Correct answer | under 1 s |
| `quiz/wrong.mp3` | Wrong answer | under 1 s |
| `quiz/streak.mp3` | Streak of 3 or more | under 1.5 s |
| `quiz/complete.mp3` | Round results screen | under 2 s |
| `timed/start.mp3` | Timed round begins (countdown or "go") | under 1.5 s |
| `timed/tick.mp3` | Every second while the timer runs low | under 0.2 s |
| `timed/warning.mp3` | Last 5 to 10 seconds of a question | under 1 s |
| `timed/timeup.mp3` | Timer reaches zero | under 1.5 s |
