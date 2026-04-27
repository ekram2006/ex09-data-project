---
layout: default
title: COMP110 Data Project
---

# Should COMP110 Lectures Be Livestreamed?

**By Ethan Kramer**

## Project Summary

For our COMP110 data project, we explored whether in-person lectures should be livestreamed so that students who can't attend in person aren't required to. The motivation was simple: students have very different schedules, learning styles, and life circumstances, and a livestream option could create real value by giving flexibility without forcing anyone to give up the in-person experience.

To investigate whether students would actually support this change, we analyzed the anonymized COMP110 course survey, focusing on the `add_livestream` column — student agreement (on a 1–7 scale) with the idea that lectures should be live streamed.

We approached the question in three layers:
1. What does overall student support for livestreaming look like?
2. Are there specific subgroups (transfer students, low-experience students) driving the support?
3. Does support track with how difficult students find the course?

## Analysis & Visualizations

### Chart 1: Overall Support for Livestreaming

![Overall Support for Livestreaming COMP110 Lectures](assets/chart1.png)

The distribution of student responses is strongly skewed toward agreement. The single largest group selected 7 (Strongly Agree), and responses of 5, 6, or 7 together make up roughly three-quarters of the class. This is initial evidence that livestreaming is widely wanted — but a student who *prefers* livestreaming is different from a student who *needs* it, so the rest of the analysis dug into who actually wants it most.

### Chart 2: Support by Prior Programming Experience

![Mean Support for Livestreaming by Prior Programming Experience](assets/chart2.png)

We expected that students with no prior programming experience might want livestreaming the most, since they have the steepest learning curve. The data didn't support that. Mean support stayed remarkably consistent across all five experience levels — clustered narrowly between 5.51 and 5.79. Support is popular across experience levels rather than concentrated in any single subgroup. We also checked transfer students separately, and the pattern was the same: both transfers (n=81) and non-transfers rated support high, with no meaningful gap.

### Chart 3: Support by Perceived Course Difficulty

![Livestream Support by Perceived Course Difficulty](assets/chart3.png)

This is where the strongest signal showed up. Mean support for livestreaming rises substantially with how difficult students find the course — from 4.88 at difficulty=1 to 6.37 at difficulty=7. The box plot shows the entire distribution shifting upward as difficulty increases: at difficulty=1 the median is around 5 with a wide spread, but at difficulty=7 the median sits at 7 with most responses clustered near the top. We confirmed this pattern with a second variable, `understanding`, and found the same thing: students who feel lost want livestreaming more than students who feel they understand most of the material.

## Conclusion

The analysis supports the idea of livestreaming in-person lectures. The overall distribution of `add_livestream` responses is strongly skewed toward agreement, with "Strongly Agree" as the single most common response and roughly three-quarters of students rating their support at 5 or higher. When we sliced the data by transfer status and prior programming experience, demand looked similar across groups — meaning the support isn't being driven by one specific student type. The key finding was that mean support rises from 4.88 at difficulty=1 to 6.37 at difficulty=7, with the box plot distribution shifting clearly upward at higher difficulty levels. Checking against the `understanding` variable reproduced the same pattern: students who feel more lost want livestreaming more. Taken together, the data supports the conclusion that livestreaming would be widely welcomed and would primarily benefit students who are struggling.

**Potential trade-offs and downsides:**
- Livestreaming could reduce in-person attendance, which might lower lecture energy and informal peer interaction before/after class.
- It requires technical setup (cameras, mics, recording infrastructure) and instructor comfort with being recorded.
- Some students might lean on the stream as a substitute for engagement rather than a supplement, which could hurt their learning outcomes — particularly the struggling students who would benefit most from being there in person.

**Future work and refinements:**
- A follow-up survey could ask whether students want a *live* stream specifically, or whether *recorded* lectures uploaded after class would meet the same need at lower cost.
- Tracking whether students who use the livestream perform differently on assessments than in-person attendees would help measure the actual learning impact.
- The course could pilot livestreaming for a single section or a portion of the semester and measure attendance, performance, and student satisfaction before committing to it course-wide.

The data tells a clear story: students want this, and the students who want it most are the ones for whom flexibility matters most.