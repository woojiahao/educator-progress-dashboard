# educator-progress-dashboard

Progress dashboard for educators to manage classes using Git-Mastery

## Getting started

Fork this repository and create a clone of it:

```bash
git clone https://github.com/<your username>/educator-progress-dashboard.git
```

Add the list of your student's Github usernames to the `STUDENTS` constant in `gitmastery.config.ts` (without `@`).

If you wish to shortlist and filter the list of exercises that you want to monitor, add it to the filter list in `EXERCISES` constant in `gitmastery.config.ts`.

Set the class name to display on the webpage using the `CLASS_NAME` constant in `gitmastery.config.ts`.

Install all dependencies:

```bash
yarn
```

Start the webapp to verify that your students are set correctly:

```bash
yarn dev
```
