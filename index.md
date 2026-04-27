---
layout: default
title: COMP110 Data Project
---

# Should COMP110 Lectures Be Livestreamed?

## Project Summary

For our COMP110 data project, we explored the idea of livestreaming in-person lectures so that not all students would be required to attend in person. The motivation was straightforward: students have very different schedules, learning preferences, and life circumstances, and a livestream option could create real value by giving flexibility to students while still preserving in-person attendance for those who benefit from it.

To investigate whether students would actually support this change, we analyzed the anonymized course survey data submitted by COMP110 students earlier in the semester. Specifically, we looked at the `add_livestream` column, which captures student agreement (on a 1–7 scale) with the idea that lectures should be live streamed.

We approached the question from three angles:
1. What does overall student support for livestreaming look like?
2. Does support vary by prior programming experience? (i.e. is this just a "beginners want help" preference?)
3. Does support vary by perceived course difficulty? (i.e. is this driven by students who are struggling?)

## Analysis & Visualizations

### Chart 1: Overall Support for Livestreaming

![Overall Support for Livestreaming COMP110 Lectures](assets/chart1.png)

The distribution of student support is heavily skewed toward agreement. The most common response was a 7 (Strongly Agree), with over 300 students selecting it. Together, ratings of 5, 6, and 7 vastly outnumber ratings of 1, 2, or 3. This shows broad and strong support for livestreaming across the student body — not just a small group of students who would benefit.

### Chart 2: Support by Prior Programming Experience

![Mean Support for Livestreaming by Prior Programming Experience](assets/chart2.png)

When we broke support down by how much prior programming experience students had coming into COMP110, the mean support stayed remarkably consistent — hovering around 5.5 across every experience level, from "None to less than one month" all the way to "Over 2 years." This was somewhat surprising. We expected that less-experienced students might want livestreaming more (so they could rewatch confusing parts), but in reality, even highly experienced students want this option. That tells us this isn't an "I'm struggling" preference — it's a flexibility preference that cuts across all experience levels.

### Chart 3: Support by Perceived Course Difficulty

![Livestream Support by Perceived Course Difficulty](assets/chart3.png)

Similarly, when we grouped students by how difficult they were finding COMP110, support for livestreaming stayed strong across the board. Median support is at 5 or 6 for almost every difficulty rating, including students who said the course was very easy (rating 1). Even students who aren't struggling want this option to be available. This further reinforces the idea that students aren't asking for livestreaming because they're falling behind — they're asking for it because flexibility itself is valuable.

## Conclusion

Our analysis strongly supports the idea that livestreaming COMP110 lectures would create value for students. Support is high overall, and — importantly — it's high across every subgroup we tested. Students with no programming background want it. Students with years of experience want it. Students finding the class easy want it. Students finding it hard want it. The consistency of support is the most compelling part of the finding: it isn't a niche request from a specific group.

**Potential trade-offs worth considering:**
- Livestreaming could reduce in-person attendance, which might lower the energy of live lectures and reduce informal peer interaction before/after class.
- It requires technical setup (cameras, mics, recording infrastructure) and instructor comfort with being recorded.
- Some students might rely on the stream as a substitute for engagement rather than a supplement, which could hurt their learning outcomes even if they prefer the option.

**Future work and refinements:**
- A follow-up survey could ask whether students want a *live* stream specifically, or whether *recorded* lectures uploaded after class would meet the same need (potentially cheaper to produce).
- It would be valuable to track whether students who use the livestream perform differently on assessments than those who attend in person, to see if there's an actual learning cost.
- The course could pilot livestreaming for a single section or a portion of the semester and measure attendance, performance, and student satisfaction before committing fully.

Overall, the data tells a clear story: students want this, and they want it consistently. Adding a livestream option is a low-risk way to create real value for the largest stakeholder group in COMP110.