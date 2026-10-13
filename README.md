# Steady

<h1 align="center">Steady</h1>

<p align="center"><b>Learn one small step at a time.</b><br>
A calm learning app for students with ADHD or autism, for kindergarten through 12th grade.</p>


## Why I built this

[Write 2 to 4 sentences in your own words. For example: what you saw at Welcome Neurodiversity that made you want to build this.]

Many students with ADHD or autism want to learn, but busy screens, countdown timers, and too many choices make it hard to stay with a task. Steady removes those distractions. It shows one small step per screen, has no timers and no scores, and always has a Break button.

## Features

**Made for focus**
- One step per screen, with the same buttons in the same place every time
- No timers, no scores, and no streaks to lose
- A Break button on every lesson, with a slow breathing circle. Your place is saved.
- A "Continue where you left off" card on the home screen
- A First/Then plan for the day (for example Math, then Reading, then Break) with tick boxes that tick themselves when you finish a lesson

**Learning**
- Four subjects: Math, Science, Reading and writing, and Social studies
- Grades K to 12. Students pick their grade and their real class, such as Algebra 1 or Biology, then type the unit they are working on.
- Lessons adapt: after several mistakes the next lesson is a little easier, and after a perfect lesson it is a little harder. A second wrong answer removes one choice or shows a hint.
- An "Explain it another way" button on every learning step
- **Scan my homework:** take a photo and get clear steps, one at a time (needs Claude)

**Accessibility**
- Quick setups: Calm, High contrast, and Dyslexia-friendly
- Text size, a choice of fonts, light, dark and high-contrast themes
- A switch to stop all movement
- Read aloud
- Works with a keyboard, with labels for screen readers

**Any language**
- Spanish and French are built in
- Any other language can be translated by going into settings and changing the language that the user prefers (Arabic, for example)

## How to run it

Steady is a single file with no install step and no dependencies.

1. Download `steady(1).html`.
2. Open it in a web browser.

To put it online with GitHub Pages:
1. Upload `steady (1).html` folder to a GitHub repository.
2. Go to **Settings, then Pages**. Under "Build and deployment," choose **Deploy from a branch**, select `main` and `/ (root)`, and save.
3. After about a minute your app is live at `https://YOUR-USERNAME.github.io/YOUR-REPO/`.

## Two modes

| | With Claude | AI-free mode |
|---|---|---|
| Lessons | Any class, grade and topic | 12 built-in lessons for each subject and grade band (K-2, 3-5, 6-12) |
| Languages | Any language | Spanish and French |
| Homework scan | Yes | No |
| Data sent anywhere | Yes (see Privacy) | None |

The Claude features only work when the app is opened inside claude.ai. Anywhere else, such as GitHub Pages, Steady runs in AI-free mode. You can also turn Claude off in **Settings**.

## Privacy

- **Stays on the device:** nickname, number code (scrambled), grade, classes, plan, progress and settings. These are saved only in that browser.
- **Sent to Claude, only when Claude is on:** the grade, class and topic (to write a lesson), homework photos (to write steps), and the app's words (to translate them).
- **AI-free mode** sends nothing anywhere.

## Known limitations

- Profiles are a convenience, not a secure account system. Anyone with access to the device could get past the number code. Don't use a code you use elsewhere.
- Profiles and progress are stored in one browser, so they do not move between devices.
- Lessons written by Claude are not reviewed ahead of time, so a teacher should check them.
- The Spanish and French text has not yet been checked by a native speaker. [Update this line if someone has checked it.]
- The "About" page paragraphs are in English only.

## How it was built

Steady is HTML, CSS and JavaScript in one file. It uses the Lexend and Atkinson Hyperlegible fonts from Google Fonts.

**AI disclosure:** Most of the code was helped with Claude, an AI assistant from Anthropic, working from my troubles in some code that I encountered. [Describe honestly what you did yourself, for example: the idea and the research with students, which features to build, design decisions, testing, bugs you found and fixed, and any code you wrote or changed.]

## Testing

15 students from Welcome Neurodiversity tried Steady during one of our meetings, for about 15 minutes each.

Nine of the 15 told me they never felt engaged by regular classroom lessons because there is too much on the screen at once and they lose their place. Seven said the Break button helped them reset. Three said the home screen was confusing at first.

Because of this, I moved the grade menu to the top so it’s the first thing students see. I also added the “Explain it another way” button after two students said some steps didn’t make sense the first time.

I’m still working on more lessons for middle school, which a few students asked for. 

## Accessibility check

The main text, button and message colors in the light and dark themes were checked and meet the WCAG AA contrast ratio of 4.5:1.

## What's next

## What's next

I built Steady as a first version. Here is what I want to add next, roughly in order:

1. **Real accounts that work on any device.** Right now profiles stay in one browser. I want a proper sign-in so a student's progress follows them from school to home, with a parent or teacher creating the account for younger students.
2. **A teacher and parent view.** A simple page showing which lessons a student finished and where they got stuck, shared only with permission, so adults can help without hovering.
3. **More lessons, checked by teachers.** The built-in lessons cover each subject at three grade levels. I want a full set for every grade, written or reviewed by real teachers, so it works well without AI.
4. **More languages, checked by native speakers.** Spanish and French are built in. I want to add more of the languages my community speaks and have each one read by a native speaker.
5. **Picture-based schedules.** The First/Then plan uses words. I want to add pictures and let students customize tasks, which helps younger students and non-readers.
6. **Learning through interests.** Let students choose themes like space, animals or trains so examples and practice questions match what they care about.
7. **Install it like an app and use it offline.** Make Steady installable on a phone or Chromebook, working without internet.
8. **Sound and voice options.** Gentler read-aloud voices, optional calming sounds, and the choice to turn all sound off.
9. **Testing with more students.** Keep testing with more students, including different ages and needs, and do a full screen reader and keyboard accessibility review.

## Files

- `stead(1).html`: the whole app

## License

[Choose a license. If you are not sure, GitHub can add one for you when you create the repository.]
