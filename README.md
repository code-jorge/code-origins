## 👋 Hey there!

It might look like I started coding back in **1991**, but not really.

Let's revisit the timeline real quick:

- I was **born** in **1991**. 
- **Linus Torvalds** released **git** in **2005**
- I started **coding** in **2010**

## How this is done

Well, **git** allows you to add a custom date to your commits.

You can do any date you want, it really doesn't care.

So here's how I did this:

----------------

#### 🚀 Step 1: Create the project

Starting a new repository locally is as easy as:

```
mkdir code-origins
cd code-origins
git init
touch README.md
echo "## 👋 Hey there!" >> README.md
```

#### ☁ Step 2: The cloud

Go to Github and create a new empty repository.

I named mine `code-origins`.

You also want to link your newly created repository to this one. **Github** outputs the instructions once you create the repository!

#### 👶 Step 3: Time travel

Let's take a trip back to when I was born, 1991 (yes, I'm **that** old)

```
git add README.md

GIT_COMMITTER_DATE="Wed Sep 11 11:11 1991 +0100" \
  git commit -m "Coding since the day I was born" \
  --date="Wed Sep 11 11:11 1991 +0100"

git push origin main
```

#### 💰 Step 4: Profit

Still working on that one!