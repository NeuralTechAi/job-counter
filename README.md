# Job Counter

A browser-based job counter. No account or sign-in is required.

## Use the app

Open https://neuraltechai.github.io/job-counter/ in your browser.

Jobs and preferences are saved in local storage in the current browser profile on the current device. Visitors using separate browsers, profiles, or devices have independent data. Tabs using the same browser profile share storage; this app does not provide separate accounts within one profile or synchronization across devices.

Use **Save / Import** to copy a job's JSON as a backup or import it on another device. Clearing browser site data removes saved jobs. Private browsing may discard jobs when the session ends.

## Hosting

`index.html` is based on the supplied `Job Counter3.html`, renamed for GitHub Pages and updated for mobile use. Two count columns plus Total fit on phones without horizontal scrolling. On narrow phones, the buttons sit below each value when there is more than one count column. Adding a third count column enables horizontal scrolling. The app is self-contained and has no backend or external dependencies. GitHub Pages serves the root of the `main` branch.
