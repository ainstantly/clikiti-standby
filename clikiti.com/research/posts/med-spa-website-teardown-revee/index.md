---
title: "Teardown: the med spa site that answers all nine client questions"
status: published
date: 2026-10-15T14:30:00Z
author: clikiti-research
excerpt: "Rêvée Aesthetics in Richmond, Virginia, is the best-in-class site in our scan of 194 independent med spa and aesthetic clinic websites. We read it page by page against the study's numbers: what it does that most sites don't, and what it still leaves out."
featured_image: /research/medspa/2026-q4/hero/hero-1-1600.webp
featured_image_alt: "An aesthetic nurse in espresso scrubs folds a linen towel onto a treatment chair in a travertine room lit by a window"
featured_image_caption: "Most of what a client wants to know before this appointment is missing from the average practice website."
og_image: /research/medspa/2026-q4/og.jpg
category: medspa
tags: [pricing, trust]
type: teardown
cites:
  - medspa/2026-q4#price
  - medspa/2026-q4#director
  - medspa/2026-q4#safety
  - medspa/2026-q4#con
summary:
  - "Only 34% of 194 independent med spa and aesthetic clinic websites show any treatment price: per unit, per syringe, per session or a starting price (Clikiti Research, October 2026)."
  - "The best-in-class site, Rêvée Aesthetics in Richmond, Virginia, prices Botox per unit on the treatment page, names its medical director on the home page and lists each injector with a credential."
  - "It still fails text contrast, as 87% of the sites do, has no medical business structured data, and stops pricing at neurotoxins."
pitch_line: "The first thing a client wants to know is what it costs, and your site makes her book a consultation to find out."
audio:
  src: /research/posts/med-spa-website-teardown-revee/episode.mp3
  duration: 225
  transcript: /research/posts/med-spa-website-teardown-revee/episode.txt
---

A client choosing where to have a neurotoxin or a filler appointment asks the same handful of questions of every practice she considers. What does it cost? Who will be holding the syringe? Is a doctor behind this? How long will I look treated? We turned those questions into nine pass rules and read the served pages of 194 independent practices against them.

That study is [The State of Independent Med Spa Websites 2026](/research/medspa). Its headline: **only 34% of the sites show any treatment price**, whether per unit, per syringe, per session or as a starting price. The median site answers five of the nine questions.

::stat{ref="medspa/2026-q4#price"}

The report names one site as best in class: [Rêvée Aesthetics](https://www.myrevee.com/), a physician-led med spa in Richmond, Virginia. It answers all nine questions, passes the speed and image-description checks, and scores 86 out of 100 on our overall website score, against a median of 75. This teardown reads it closely, section by section, with the study's numbers alongside. Everything described here can be checked on the live site.

## What is it being measured against?

The nine questions, with the share of all 194 sites that answer each:

| Client question | All sites | Rêvée |
| --- | ---: | ---: |
| What will it cost? | 34% | Yes |
| Is it safe, and how long will I look treated? | 42% | Yes |
| Is a doctor overseeing this? | 44% | Yes |
| What results can I expect? | 45% | Yes |
| Can I talk to someone first? | 52% | Yes |
| Can I spread the cost? | 65% | Yes |
| Do other clients vouch for you? | 68% | Yes |
| Who will be doing my treatment? | 71% | Yes |
| Can I book without calling? | 87% | Yes |

::chart{ref="medspa/2026-q4" highlight="price"}

Booking is close to solved across the trade: 87% of sites let a client book online. The questions that separate a considered site from a booking widget with a homepage are the four at the top of the table.

## How does it handle price?

The Botox page has a section headed with the client's own question, "How much does Botox cost?" Under it: a price per unit, a lower price per unit for members, and the range of units most patients need. Dysport follows in the same format.

That is the complete answer. A per-unit price alone leaves the client unable to estimate a visit; a unit range alone tells her nothing about money. Together, she can do the arithmetic herself before she books. The page also explains why the total varies (the areas treated and the client's own anatomy), which is the point most owners fear a published price will hide.

Across the study, 66% of sites show no treatment price at all. Cosmetic dermatology is lowest: 13% of those sites show one. Injector-led boutiques and independent med spas do best, at 44% and 41%.

## Who holds the syringe, and who oversees them?

The home page says who leads the practice: Dr. Lonny Green, named with his Allergan trainer role. The team page lists a medical director, a physician assistant (PA-C), a nurse injector (RN), a nurse practitioner (FNP-BC) and the aestheticians, each with a profile.

The detail worth copying is on the Botox page itself. It closes with "Our Injectors": four names, each with a credential. A client reading about a treatment sees who performs it on the same page, without going to look for a team page. The before-and-after captions do the same thing in a smaller way: "Lips by Jade", "Facial Balancing by Dr Green".

In the study, 71% of sites name a provider with a clinical credential. Only 44% name a physician as medical director or lead doctor, and the split by kind of practice is sharp: 80% of cosmetic dermatology sites, 23% of laser and skin clinics and 23% of injector-led boutiques.

## Consultation, cost and downtime

The consultation page answers "Can I talk to someone first?" more fully than the rule asks. It says the consultation is free, then walks through it in four numbered steps: a conversation about goals, a skin assessment with imaging, a written plan, and leaving without pressure ("Some patients book treatment the same day. Others take time to think about it."). There is a short FAQ on whether a client needs to know what she wants before she comes in. 52% of sites offer a consultation by name; cosmetic dermatology sites, at 22%, rarely do.

Financing has its own page, naming the provider and the terms: a soft credit check and the APR range. 65% of sites offer financing or a membership.

Downtime is answered in the Botox FAQ: what most clients feel, how soon they return to normal activities, the redness or small marks they may see and how quickly they fade, and when results show. 58% of sites never say how long a client will look treated, though it is the question that decides whether she books before a wedding or after it.

## What does it still miss?

Three things, two of them shared with most of the sample.

**Text contrast.** Rêvée fails WCAG 1.4.3, the 4.5:1 contrast rule for text, as 87% of the sites in the study do. It is the most common failure in the report. On a prospect's site, check taupe or sand type on cream and white type over photographs first.

**Structured data.** The site carries no MedicalBusiness, MedicalClinic, Physician or DaySpa markup, like 59% of sites. Search engines and assistants are left to work out from the copy what kind of practice it is and who the physician is.

**Price stops at neurotoxins.** The pass rule needs one treatment price, and the Botox page gives one. In the served text of the filler page we found no price per syringe, and the special offers page lists a VIP membership and six treatment packages with a "Call Now" button and no price in its text. A client who comes for lips or a laser series, not for neurotoxin, still has to ask.

None of these takes a rebuild. Contrast is a theme change, the markup is an afternoon, and the filler price is a line the front desk already says on the phone.

## What it is fast at

The study's speed check is a phone load under 2.5 seconds. 77% of the sites fail it. Rêvée's real visitors see the main content in 0.6 seconds, from Chrome's field data. That matters more in this trade than in most: a client comparing three practices on her phone gives each one a few seconds.

> The questions that separate a considered site from a booking widget with a homepage are price, downtime, the medical director and the gallery.

For an agency, the site is a reference to show a prospect what a finished answer looks like, question by question. The page most practices are missing first is the consultation page, and [our copy deck for it](/research/posts/med-spa-consultation-page-copy-deck) gives it block by block. For the same build applied to another clinical trade, see the [dental insurance page build sheet](/research/posts/dental-insurance-page-build-sheet). The method, the pass rules and every practice in the sample are in [the full report](/research/medspa/2026-q4).
