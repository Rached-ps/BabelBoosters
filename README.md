# Babel Boosters

A community glossary of open-source words, translated into the languages people
actually speak. Anyone can add a file with the words in their own language, and
that file is their contribution : nobody edits anybody else's.

## Why this exists

Open source is meant to be open to everyone, but almost all of its vocabulary
only exists in English. Words like *fork*, *commit* and *pull request* are not
hard ideas : they are just unfamiliar words. For a lot of people, that
vocabulary is the actual wall between them and their first contribution, not
the coding.

So this repository collects those words in as many languages as we can reach.
If someone can read *fork* in a language they think in, the wall gets a little
lower.

## What you are going to do

You will add **one new file** with twelve words and two sentences translated
into a language you know. The file is yours alone, so nothing you do can clash
with anyone else's work.

The whole thing works on a phone, in your browser. You do not need to install
anything.

## How to contribute : step by step

You will need a free GitHub account. If you do not have one, make one first at
[github.com/signup](https://github.com/signup) : do that yourself; never share
your password with anyone, including a workshop helper.

Some words before we start, so nothing surprises you:

- A **repository** ("repo") is a project's folder of files. This page is one.
- A **branch** is a separate copy of the files where your changes live until
  they are accepted. GitHub makes one for you automatically.
- A **commit** is one saved change with a short message describing it.
- A **pull request** ("PR") is you asking the project to take your change in.

None of that needs memorising. Just follow the steps.

### Step 1 : Read the template

Open [`translations/TEMPLATE.md`](translations/TEMPLATE.md) and read it. It has
the twelve words, each with a short English explanation, and the two sentences.
Keep it open in another tab if you can : you are about to copy from it.

Two finished examples are there too, so you can see what "done" looks like:

- [`translations/hi/example-devanagari.md`](translations/hi/example-devanagari.md) : Hindi, in Devanagari script
- [`translations/ta/example-transliterated.md`](translations/ta/example-transliterated.md) : Tamil, written in Latin letters

### Step 2 : Start a new file

Go back to the front page of this repository. Find the button that says
**Add file**, tap it, and choose **Create new file**.

> On a narrow phone screen the **Add file** button can be hard to reach. The
> reliable shortcut: take this repository's web address and add `/new/main` to
> the end of it, then open that. It lands you on exactly the same page.

### Step 3 : Name your file

At the top there is a box that says **Name your file...**

Type your file path into it, like this:

```
translations/hi/yourname.md
```

Change three things:

1. `hi` → the code for your language, from the table below.
2. `yourname` → your GitHub username, exactly as it is spelled.
3. Keep the `.md` at the end. That is what makes it a Markdown file.

**You do not need to create the folders first.** As soon as you type a `/`,
GitHub turns what you typed into a folder and moves the cursor along. Typing
the whole path in one go creates every folder it needs. This surprises most
people the first time : it is working correctly.

### Step 4 : Fill it in

In the big text box underneath, paste the contents of
[`translations/TEMPLATE.md`](translations/TEMPLATE.md) and write your
translations into the blank spaces.

If a word has no good translation in your language, say so and write it the way
people actually say it. That is a real answer, and the template explains how to
record it.

### Step 5 : Commit changes

Tap the green **Commit changes...** button.

A box appears. In **Commit message**, write something short and plain, like:

```
Add Hindi translations
```

If you are offered a choice between committing straight to `main` and creating
a new branch, choose **Create a new branch for this commit and start a pull
request**. If you are not offered a choice, GitHub has already sorted it out
for you : carry on.

Then tap the green button at the bottom of that box. It says **Propose changes**
(or **Commit changes**, depending on your access : either is correct).

### Step 6 : Create pull request

You now land on a page comparing your file with the project. Tap the green
**Create pull request** button.

A title and a description box appear, with the title already filled in from
your commit message. You can add a sentence about your language if you like, or
leave it as it is. Then tap **Create pull request** again.

That is it. You have opened a pull request. A maintainer will read it, and it
will be merged.

If something looks different from these steps, or you get stuck at any point,
ask : being stuck at step 3 is not a sign you are behind, it is a sign the
instructions need improving, and telling us is itself useful.

## Language codes

Use the code in the first column as the folder name.

| Code | Language |
| --- | --- |
| `hi` | Hindi : हिन्दी |
| `bn` | Bengali / Bangla : বাংলা |
| `ta` | Tamil : தமிழ் |
| `te` | Telugu : తెలుగు |
| `mr` | Marathi : मराठी |
| `gu` | Gujarati : ગુજરાતી |
| `ml` | Malayalam : മലയാളം |
| `kn` | Kannada : ಕನ್ನಡ |
| `pa` | Punjabi : ਪੰਜਾਬੀ |
| `or` | Odia : ଓଡ଼ିଆ |
| `as` | Assamese : অসমীয়া |
| `ur` | Urdu : اردو |
| `ne` | Nepali : नेपाली |
| `sa` | Sanskrit : संस्कृतम् |
| `mai` | Maithili : मैथिली |
| `bho` | Bhojpuri : भोजपुरी |
| `raj` | Rajasthani : राजस्थानी |
| `kok` | Konkani : कोंकणी |
| `mni` | Manipuri / Meiteilon : ꯃꯤꯇꯩ ꯂꯣꯟ |
| `sat` | Santali : ᱥᱟᱱᱛᱟᱲᱤ |

**If your language is not on this list, add it.** Make the folder with a
sensible short code and put your file in it, exactly as in the steps above.
That is the most valuable contribution anyone can make here, because it is the
one nobody else can make for you. If you are unsure what code to use, pick
something reasonable and say so in your pull request : we will sort it out
together, and getting it "wrong" costs nothing.

## Writing your language in Latin letters counts

You do not need an Indic keyboard to take part.

If you write Tamil as *kilai* rather than கிளை, or Hindi as *shakha* rather
than शाखा, that is a **full contribution** : not a rough draft, not a
placeholder, not a lesser version of the "real" one. Transliteration is how a
huge number of people write their own languages every day, in messages and
searches and notes. It is often the form other learners will recognise fastest.

[`translations/ta/example-transliterated.md`](translations/ta/example-transliterated.md)
is there precisely so you can see one sitting alongside the others, treated the
same way.

If you would like to type in your own script and are not set up for it, Android
and iOS both have Indic keyboards built in, and Google Input Tools works in a
browser. Ask a helper : it takes about a minute. But please do not let it stop
you today.

## What happens to your file

Your file stays exactly as you wrote it, with your name on it, permanently.

Later, the `glossary/` folder will hold a single curated file per language,
brought together from everybody's submissions : so someone looking up a word
gets one clear page rather than twenty. Where people chose differently, the
curated file will show the alternatives rather than pick a winner, because
often there is no winner.

**Every contributor whose work feeds a curated file is credited in it, by name
and by link.** Nothing gets absorbed anonymously.

## The rest

- [`CONTRIBUTING.md`](CONTRIBUTING.md) : the same steps in more detail, plus
  what makes a good entry.
- [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md) : how we treat each other here.
- [`LICENSE`](LICENSE) : CC BY 4.0. Anyone may reuse this work, including
  commercially, as long as they credit the people who made it.

Built by [Accelerate](https://github.com/), the student open-source club at
Manipal University Jaipur.
