# work-linux-skills

## How to set up this repo

### Step 1 — Create on GitHub
1. Go to https://github.com
2. Click **+** top right then **New repository**
3. Name it `work-linux-skills`
4. Set to **Public**
5. Check **Add a README file**
6. Click **Create repository**

### Step 2 — Get the SSH clone link
1. Click the green **Code** button on your repo page
2. Select **SSH** tab
3. Copy the link — starts with `git@github.com:`

### Step 3 — Clone and scaffold locally
Run these in your Mac terminal one at a time:

```bash
git clone git@github.com:Manzmike/work-linux-skills.git
cd work-linux-skills
mkdir -p week_1/mon_Filesystem_Hierarchy
touch week_1/mon_Filesystem_Hierarchy/.gitkeep
git add .
git commit -m "init: scaffold work-linux-skills repo"
git push origin main
```

---

A self-directed daily Linux, Perl, and tools curriculum built around 1 hour per day, 4 days per week.

## What this is

This repo tracks my daily progress learning Linux filesystem internals, Perl scripting, and core command-line tools (vim, tmux, sed, awk, regex, and more). Each session produces a reading, a hands-on tutorial, a Perl exercise, and a tool drill — all committed here with solutions.

## Why

To build practical Linux and scripting depth that directly supports my work as an embedded systems engineer at Boeing — and compounds into the firmware architecture skills I'm developing in parallel.

## Structure

```
work-linux-skills/
  week_1/
    mon_Topic/
      READING.md
      TUTORIAL.md
      PERL.md
      TOOL.md
      solution.md
    tue_Topic/
    thu_Topic/
    fri_Topic/
  week_2/
    ...
```

## Topics covered

- Linux filesystem internals — FHS, inodes, permissions, links, /proc, file descriptors, disk usage, archiving
- Perl — scalars, arrays, hashes, regex, file I/O, subroutines, one-liners
- Tools in order — vim, vi, nano, tmux, regex, sed, awk, and additional utilities

## Rules

- Mastery before advancing — no topic moves forward until the solution is confirmed correct
- Every solution committed with a descriptive commit message
- Wednesday excluded every week

## Stack

- macOS (MacBook Pro M4) — primary machine
- Ubuntu ARM via Parallels — Linux environment
- Shared folder between environments at `~/Dev/shared` (Mac) and `~/shared` (Ubuntu)
