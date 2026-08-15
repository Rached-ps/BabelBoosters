# Contributing

Welcome. This page is longer than the [README](README.md) on purpose — it is
here for when you want more detail, or when a step did not go the way you
expected. Nothing here is required reading before you start.

**The short version:** add one new file at
`translations/<lang-code>/<your-github-username>.md`, fill in the twelve words
and two sentences, open a pull request.

---

## Part 1 — The steps, in detail

### Before you start

You need a free GitHub account, and that is all. Create one at
[github.com/signup](https://github.com/signup) if you have not already.

Set up your own account yourself and keep your password to yourself. No
workshop helper, and nobody in this project, will ever need it.

You do **not** need: git installed, a laptop, a terminal, an editor, Node, npm,
or any knowledge of what those things are.

### A few words, explained once

These come up constantly and are never explained to beginners, so:

| Word | What it actually means |
| --- | --- |
| repository | A project's folder of files, kept on GitHub. Often shortened to "repo". |
| branch | A separate copy of the files where your changes live before they are accepted. |
| commit | One saved change, with a short message describing it. |
| pull request | Asking the project to take your change in. Often shortened to "PR". |
| merge | The moment your change becomes part of the project. |
| maintainer | Someone who looks after the project and merges pull requests. |

If a helper uses a word you do not know, stop them and ask. You are not the
only person in the room who does not know it — you are just the one being brave
about it.

### Step 1 — Open the template

Open [`translations/TEMPLATE.md`](translations/TEMPLATE.md).

Tap the **Raw** button (or the copy icon) to get the plain text, then select all
and copy. On a phone, long-press in the text and choose *Select all*.

If copying on your phone is fighting you, do not lose ten minutes to it. Type
the words out by hand instead — there are only twelve of them, and you will
read them more carefully that way.

### Step 2 — Add file → Create new file

Go to the front page of this repository. Tap **Add file**, then choose
**Create new file**.

If you cannot find **Add file** on a small screen: take this repository's web
address and add `/new/main` to the end, then open that. Same page, no hunting.

### Step 3 — Name your file

There is a box at the top labelled **Name your file...**

Type the whole path in one go:

```
translations/hi/yourname.md
```

Three things to get right:

1. **The language code.** Use the code from the table in the
   [README](README.md#language-codes). Lower case.
2. **Your GitHub username.** Spelled exactly as it appears on your profile.
   This is what makes your file yours and stops it colliding with anyone
   else's. If your username has capital letters, that is fine — use them.
3. **The `.md` ending.** Without it, GitHub will not display your work nicely.

**About the folders:** you do not create them separately. The moment you type
`/`, GitHub turns everything before it into a folder and carries on. Typing
`translations/hi/yourname.md` creates `translations/` and `hi/` if they do not
exist yet, and reuses them if they do.

If you typed a `/` by accident and the box jumps about, press backspace at the
very start of the box — the folder collapses back into editable text.

### Step 4 — Write your translations

The big box below is where your file's contents go. Paste the template in and
fill the blanks.

There are **Edit** and **Preview** tabs. Preview shows you how it will look once
saved. It is worth a glance, but nothing depends on it.

Typing in an Indic script? If your phone is not set up for it yet:

- **Android:** Settings → System → Languages & input → On-screen keyboard →
  Gboard → Languages → Add keyboard.
- **iOS:** Settings → General → Keyboard → Keyboards → Add New Keyboard.
- **In a browser:** Google Input Tools, or your operating system's built-in
  transliteration keyboard, which lets you type `shakha` and get शाखा.

And if none of that works today, write in Latin letters. See Part 2.

### Step 5 — Commit changes

Tap the green **Commit changes...** button, near the top right.

A box opens asking for a **Commit message**. This is a one-line note saying what
you did. Keep it plain:

```
Add Hindi translations
```

There is also an **Extended description** box. It is optional. Leave it empty.

You may see two options: commit directly to `main`, or **Create a new branch for
this commit and start a pull request**. Choose the second one. If you do not see
those options at all, GitHub has already made the branch for you — nothing is
wrong.

The green button at the bottom of that box says **Propose changes**, or
sometimes **Commit changes**. Which one you see depends on your access to the
repository. Both are correct. Tap it.

### Step 6 — Create pull request

You now see a page comparing your new file against the project. Tap the green
**Create pull request** button.

A form opens with a title (already filled in from your commit message) and a
description box. You can write a line about your language, or about a choice you
found difficult — those notes are genuinely interesting to read. Or leave it
blank.

Tap **Create pull request** again. Done.

### After that

A maintainer will read your pull request. They may leave a comment — that is a
**review**, and it is a normal part of how open source works. It is not a
mark, a grade, or a judgement of you. Most reviews here will just say thank you.

If a change is needed, you can edit your file straight from the pull request
page: open the **Files changed** tab, tap the pencil icon, edit, and commit
again. Your pull request updates itself.

---

## Part 2 — What makes a good entry

### Sometimes there is no translation, and that is the correct answer

Some of these words have settled, natural equivalents that people have used for
decades — *branch*, *review*, *merge* usually do.

Others simply do not. *Commit* and *fork* mean something very specific in
version control, and in many languages no word has landed yet. When that
happens, **write the word the way people actually say it in your language** —
in your script or in Latin letters — and add a note saying there is no settled
translation.

That is not giving up. That is an accurate description of the language as it is
today, and it is more useful to a beginner than a beautiful word that nobody
around them uses. A glossary that invents twelve perfect words nobody says would
help no one.

Please do not invent a new word to fill a gap. Recording the gap is the more
honest contribution, and future readers can see the gap is real.

### Consistency matters more than elegance

If you translate *repository* one way, translate it the same way in the
sentences below. If you keep *commit* in English in one place, keep it in
English everywhere.

A reader is trying to build a small map in their head. One word meaning one
thing throughout is what makes the map hold together. A more elegant word used
inconsistently is harder to learn from than a plain word used the same way every
time.

Same goes for register. Pick either the formal literary form of your language or
the way people actually talk, and stay there. Both are valid choices. Drifting
between them mid-file is the only thing to avoid.

### A short note about your choice is very welcome

Every entry has an optional note field. Use it whenever you have something to
say:

- "There is a formal word for this, but nobody uses it in conversation."
- "This is the word used in Wikipedia in my language."
- "I chose the everyday word over the technical one because this list is for
  beginners."
- "Two regions say this differently. I have given both."
- "I am not certain about this one."

Notes are not extra credit and they are not required. But they are often the
most useful thing in the file — they are where the actual knowledge is. "I am
not sure" is a perfectly good note; it tells a future curator exactly where to
look.

### Regional variation is welcome

If your language is spoken differently in different places, give more than one
form and say which is which. Nobody here will make you choose one and call it
the right one.

### Practical checklist

- Your file is at `translations/<lang-code>/<your-github-username>.md`.
- You filled in the language name and script at the top.
- Every one of the twelve words has something under it — a translation, or a
  note saying there is no settled one.
- Both sentences are translated.
- You did not edit anyone else's file. (If you find a mistake in someone
  else's, open an **issue** instead and describe it — do not change their file.)

That is the whole list. Spelling wobbles, an uncertain word, an empty note
field — none of those will stop your pull request being merged.

### Adding a language that is not listed

Make the folder and add your file. That is the whole process — no permission
needed, no discussion first.

Pick a short lower-case code. If your language has an ISO code, use it. If you
are not sure, use something sensible and mention it in your pull request. We
would far rather have your language in the repository under an imperfect code
than not have it at all.

---

## Improving these instructions

If any step here was confusing, wrong, or missing something, that is a genuine
bug in this project and worth reporting. Open an **issue** describing where you
got stuck, or fix the wording and send a pull request.

People who have just done something for the first time are the only people who
can see clearly where the instructions fail. That window closes fast. If you
noticed something today, please write it down today.

## Licence

By contributing, you agree that your work is published under
[CC BY 4.0](LICENSE), the same licence as the rest of this repository. In short:
anyone may reuse it, including commercially, as long as they credit you.
