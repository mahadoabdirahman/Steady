
<h1 align="center">Steady</h1>

<p align="center"><b>Learn one small step at a time.</b><br>
A calm learning app for students with ADHD or autism, for kindergarten through 12th grade.</p>

**Try it:** https://claude.ai/artifact/8aVYiyc7ppVbr8Mgwgrz6v

## Why I built this

I founded Welcome Neurodiversity, and through that work I saw that kids with ADHD or autism often have a hard time focusing on schoolwork.

Busy screens, countdown timers, disappearing points, and too many choices make it even harder to stay focused on a task. I built Steady to be the opposite. It shows one small step per screen, has no timers or scores, and always includes a Break button, so a student can learn at their own pace without getting overwhelmed.

## Features

**Made for focus**
- One step per screen, with the same buttons in the same place every time
- No timers, no scores, and no streaks to lose
- A Break button on every lesson, with a slow breathing circle. Your place is saved.
- A "Continue where you left off" card on the home screen
- A picture-based First/Then plan for the day. Every task has a picture; students can make their own tasks (pick a picture and type a name), and a button reads the plan aloud. Tasks tick off by themselves when a lesson is finished.

**Learning**
- Four subjects: Math, Science, Reading and writing, and Social studies, for grades K to 12
- Students pick their grade and their real class (for example, Algebra 1 or Biology), then type the unit they are working on in class
- Suggested topics: after a student picks a class, the app suggests the units for that class. The home screen also suggests the next topic for each class they chose.
- Built-in lessons come first. After one, students are guided to choose their own grade-specific class.
- Lessons adapt: after several mistakes, the next lesson is a little easier, and after a perfect lesson it is a little harder. A second wrong answer removes one choice or shows a hint.
- An "Explain it another way" button on learning steps
- **Scan my homework:** take a photo and get clear steps, one at a time (needs Claude)

**Accessibility**
- Quick setups: Calm, High contrast, and Dyslexia-friendly
- Text size, a choice of fonts, light, dark, and high-contrast themes
- A switch to stop all movement
- Works with a keyboard, with labels for screen readers

**Sound and voice**
- A gentle read-aloud voice (slower and softer), with a choice of voice and reading speed
- Optional calming sounds: soft rain, ocean waves, or a quiet hum, with a volume setting
- A switch to mute all sound

**Any language**
- Spanish and French are built in
- Any other language can be translated by Claude, and right-to-left languages such as Arabic are supported

## How to run it

Steady is a single file with no install step and no dependencies.

1. Download `index.html`.
2. Open it in a web browser.

To put it online with GitHub Pages:
1. Upload `index.html` and the `icon` folder to a GitHub repository.
2. Go to **Settings, then Pages**. Under "Build and deployment," choose **Deploy from a branch**, select `main` and `/ (root)`, and save.
3. After about a minute, GitHub shows the link to your live app at the top of the Pages screen.

## Two modes

| | With Claude | AI-free mode |
|---|---|---|
| Lessons | Any class, grade, and topic, plus suggested topics | 12 built-in lessons (every subject, three grade bands: K-2, 3-5, 6-12) |
| Grade-specific classes | All classes in the list, or type your own | Only classes that match a built-in lesson. The rest show "Needs Claude". |
| Languages | Any language | Spanish and French |
| Homework scan | Yes | No (the card is shown with a note) |
| Data sent anywhere | Yes (see Privacy) | None |

The Claude features work when the app is opened inside claude.ai, using the link at the top of this page. Anywhere else, such as GitHub Pages or a downloaded file, Steady runs in AI-free mode. You can also turn Claude off in **Settings**, which also shows whether Claude is connected.

## Privacy

- **Stays on the device:** nickname, number code (scrambled), grade, classes, plan, progress, and settings. These are saved only in that browser.
- **Sent to Claude, only when Claude is on:** the grade, class, and topic (to write a lesson or suggest units), homework photos (to write steps), and the app's words (to translate them).
- **AI-free mode** sends nothing anywhere.

## Known limitations

- Profiles are a convenience, not a secure account system. Anyone with access to the device could get past the number code. Don't use a code you use elsewhere.
- Profiles and progress are stored in one browser, so they do not move between devices.
- Lessons written by Claude are not reviewed ahead of time, so a teacher should check them.
- In AI-free mode, the grade-specific classes reuse the 12 built-in lessons.
- Read-aloud voices and calming sounds depend on the device and browser. They have not been tested on every device.
- The Spanish and French text has not yet been checked by a native speaker.
- The "About" page paragraphs are in English only.

## How it was built

Steady is HTML, CSS, and JavaScript in one file. It uses the Lexend and Atkinson Hyperlegible fonts from Google Fonts.

**AI disclosure:** Most of the code was written by Claude, an AI assistant from Anthropic. I came up with the idea, decided what the app needed (grade levels from K to 12, choosing your real class and topic, login, a Home button, picture-based schedules, sound and voice options, support for any language, and homework help), tested each version, reported what was broken or confusing, and directed every change. I did not write the code myself.

## Testing

15 students from Welcome Neurodiversity used Steady and shared their feedback with me. I am using their feedback to decide what to improve next.

## Accessibility check

The main text, button, and message colors in the light and dark themes were checked and meet the WCAG AA contrast ratio of 4.5:1.

## What's next

1. **Accounts that work on any device,** with a parent or teacher creating accounts for younger students
2. **A teacher and parent view** showing finished lessons and where a student got stuck, shared only with permission
3. **More built-in lessons for every class and grade,** written or checked by teachers, so Steady works well without AI
4. **More languages, checked by native speakers**
5. **Learning through interests,** such as space, animals or trains
6. **Install it like an app and use it offline** on phones and Chromebooks
7. **More testing** with students of different ages and needs, plus a full screen reader and keyboard review

## Files

- `index.html`: the whole app

## License

All rights reserved. Please ask before reusing the code or the design.
