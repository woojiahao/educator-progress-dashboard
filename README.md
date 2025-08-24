# educator-progress-dashboard

Progress dashboard for educators to manage classes using Git-Mastery

## Getting started

Fork this repository and create a clone of it:

```bash
git clone https://github.com/<your username>/educator-progress-dashboard.git
```

Enable Github Pages with the fork via Settings > Pages > Source > Set to Github Actions.

Set the name of your class in `config/gitmastery.config.ts`

Add the list of your student's Github usernames to the `config/students.csv` file.

If you wish to shortlist and filter the list of exercises that you want to monitor, add it to the filter list in `config/exercises.csv` file.

Install all dependencies:

```bash
yarn
```

Start the webapp to verify that your students are set correctly:

```bash
yarn dev
```
