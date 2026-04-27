---
layout: default
title: COMP110 Data Project
---

# Should COMP110 Livestream Its Lectures?

**An analysis of the Spring 2026 course survey**

*Ethan Kramer & Blake Sanders — COMP 110, Spring 2026, EX09*

## Summary

This project tests a proposed change to COMP110: that in-person lectures should be livestreamed. Using survey responses from 764 students across all three sections of the course, we look at whether livestreaming would actually create value — and which students would benefit most from it.

The survey directly asks students to rate their support for livestreaming on a 1-to-7 Likert scale (`add_livestream`). It also captures variables — transfer status, prior programming experience, perceived difficulty, and self-reported understanding — that let us figure out who is driving the support.

## Finding 1 — Overall support for livestreaming is strong

The distribution of `add_livestream` responses is sharply skewed to the right. Strongly Agree (7) was the single most common answer, and roughly three-quarters of the class rated their support at 5 or higher.

![Overall Support for Livestreaming COMP110 Lectures](assets/chart1.png)

This is a strong signal that students want this option — but a student who *wants* livestreaming isn't necessarily a student who *needs* it. The next two findings dig into who's actually driving the support.

## Finding 2 — The support is broad, not subgroup-specific

Our first hypothesis was that demand would be concentrated in specific subgroups — transfer students, or students with little prior programming experience. Neither hypothesis held up.

Transfer students (n=81) and non-transfer students reported nearly identical mean support. Across the five prior-experience categories, mean support sat in a narrow band of roughly 5.51 to 5.79 — basically flat from "None to less than one month" all the way to "Over 2 years."

![Mean Support for Livestreaming by Prior Programming Experience](assets/chart2.png)

So this isn't a niche request. Whatever's driving the support is something more universal than one type of student.

## Finding 3 — Demand rises sharply with perceived course difficulty

If experience and transfer status don't drive demand, what does? The clearest pattern in the analysis comes from `difficulty`.

Mean support climbs from 4.88 at difficulty=1 up to 6.37 at difficulty=7. The box plot shows the entire distribution shifting upward as perceived difficulty rises — at difficulty=1 the median sits around 5 with a wide spread, but at difficulty=7 the median is 7 with most responses clustered near the top.

![Livestream Support by Perceived Course Difficulty](assets/chart3.png)

We then ran an independent check against the `understanding` variable and found the same pattern: students who feel lost want livestreaming more than students who feel they understand the material. Two different variables pointing to the same conclusion strengthens the result.

## Conclusion

The data supports livestreaming COMP110 lectures. Support is broad across the student body, but it's strongest among students who are finding the course most difficult. That combination — wide popularity plus concentrated benefit for the students who need help most — is what makes this change valuable.

### Trade-offs to consider

1. **In-person attendance may decline.** A livestream option could erode the engagement that comes from actually being in the room together.
2. **Technical and staffing overhead.** A reliable livestream needs working AV equipment, a platform, and ideally a TA monitoring chat.
3. **Signals about course norms.** Adopting livestreaming may implicitly communicate that in-person attendance is optional, which could shift attendance expectations in a large intro course.

### What's next

- **Livestream-on-request** — available by short advance request rather than as a default — could preserve in-person norms while still supporting the students the data identifies.
- **Live TA-moderated chat** alongside the stream would let remote viewers participate actively rather than just receive a glorified recording.
- **Track outcomes**, not just preferences. A follow-up could measure whether livestream users perform differently on assessments than in-person attendees, which would tell us if there's an actual learning cost.