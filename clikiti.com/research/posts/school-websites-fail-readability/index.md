---
title: "4 in 5 private school websites fail a basic readability test"
status: published
date: 2026-10-14T07:00:00Z
author: clikiti-research
excerpt: "80% of the 114 school and tutoring websites we scanned have text below the 4.5:1 contrast minimum. On most sites it's a theme setting, not a redesign."
featured_image: /research/education/2026-q4/scenes/scene-teacher-1600.webp
featured_image_alt: "A teacher arranges books on a shelf in a school library"
featured_image_caption: "Low-contrast text is hardest to read on a phone in daylight."
og_image: /research/education/2026-q4/og.jpg
category: education
tags: [accessibility, speed]
type: finding
cites:
  - education/2026-q4#con
  - education/2026-q4#lcp
summary:
  - "80% of 114 private school and tutoring websites fail the WCAG 1.4.3 text contrast minimum of 4.5:1 (Clikiti Research, October 2026)."
  - "57% take longer than 2.5 seconds to show their main content on a phone."
  - "Contrast is usually fixed in the theme's colour settings, so it makes a quick first project."
pitch_line: "Parts of the site are hard to read, and it is a WCAG failure."
audio:
  src: /research/posts/school-websites-fail-readability/episode.mp3
  duration: 225
  transcript: /research/posts/school-websites-fail-readability/episode.txt
---

Pale grey text on white. White text over a photo of the school. A light gold that matches the crest but disappears on a phone in daylight. These are the most common ways a school website fails the oldest accessibility check there is.

In [The State of School Websites 2026](/research/education), Clikiti Research checked 114 private school and tutoring websites against WCAG 2.2. **80% have text that fails the 4.5:1 contrast minimum**, more than any other check in the study.

::stat{ref="education/2026-q4#con"}

## What does the contrast check measure?

WCAG 1.4.3 asks that normal body text has a contrast ratio of at least 4.5:1 against its background. We read it from Google Lighthouse in a phone and a desktop render. A site fails when any text on the home page falls below the line, which is why so many do: one grey caption or one button label is enough.

## Is speed any better?

Not much. 57% of the sites take longer than 2.5 seconds to show their main content on a phone, the Core Web Vitals threshold for a good load. Images have text descriptions on most sites; only 17% fail that check.

::chart{ref="education/2026-q4" set="technical" highlight="con"}

## Why does this matter to a school?

A parent comparing schools reads on a phone, often outside or in a car park at pickup. Text they can't read is text they don't read. Accessibility can also be a compliance question, and a named standard tends to get a bursar's attention faster than a design argument.

:::pitch{title="How do you pitch it?"}
1. **Run the check in front of them.** Paste their home page into a contrast checker or a free Clikiti scan and show the failing text in place.
2. **Separate the quick fix from the build.** Contrast is usually a theme setting and can be fixed in an afternoon. Speed means resizing images and deferring scripts, which is a bigger job and a natural second invoice.
3. **Lead with the standard, not taste.** "It fails WCAG 1.4.3" is a fact a committee can act on. "It looks washed out" is an opinion they can argue with.
:::

Contrast is the kind of problem that looks small and turns out to be everywhere, like the [phone number parents can't tap](/research/posts/school-websites-reach-a-person). That's what makes it a good opening: you're not criticising their design, you're pointing at a standard they didn't know they missed.
