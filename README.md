# Zomato — restaurant page (HTML)

Welcome. This repository is **empty on purpose**. Everything in it is yours to create.

## Where the work is

Open the **Issues** tab. There are four, in order. Each one says exactly what done looks like.

Do them one at a time. For each issue:

```bash
git checkout main
git pull
git checkout -b issue-1          # the issue number you are working on
# ...make your changes...
git add .
git commit -m "Add the page structure"
git push -u origin issue-1
```

Then open a **Pull Request** on GitHub and put `Closes #1` in the description, using the issue
number. Raj reviews every pull request. If he approves, it merges itself and the ticket moves
to Submitted. If he asks for changes, push another commit to the **same branch** — the review
runs again.

## What you need installed

Nothing. A text editor and a browser. Open your `.html` file directly in the browser to see it.

## A note on this project

No CSS and no JavaScript. The page will look plain, and that is the finished state — this one
is about whether the markup says what each part of the page *is*. Ask Priya on Slack if
anything is unclear; that is what she is there for.

## Why this repository is nearly empty

Deliberately, and it stays that way.

Most templates in the library hand you a scaffold — the boring setup done, so you can get
straight to the work. This one cannot, because **ticket 1 is "Create the page and its
structure".** A repository arriving with an `index.html` in it would have done that ticket for
you, and the structure of the page is the thing this project is about.

Your brief says the same in Priya's words: *you are not given a starter template, and that is
deliberate.*

(If you are an engineer auditing the templates: this is not the thin-template gap DZ-382 fixed
on the Ola and Meesho repos. It is a decision — the scaffold here would be the graded work.)
