---
layout: default
---

# EX09: Data Analysis for Continuous Improvement

**Author:** Vedant Mehta | COMP110 Spring 2026

---

## Analysis Summary

I analyzed two columns from the anonymized COMP110 course survey: `prior_exp` (prior programming experience level) and `pre_lecture_videos` (1–7 Likert rating of how helpful optional pre-lecture videos would be).

After combining both survey datasets and filtering out incomplete responses, I compared how students across different experience levels rated the idea. I also examined whether perceived course difficulty correlated with demand for pre-lecture videos.

**Key finding:** Students with no prior programming experience rated the idea of optional pre-lecture videos higher on average than students with 2+ years of experience. Students who found the course more difficult also tended to want pre-lecture videos more, suggesting the same population is driving demand.

---

## Visualizations

### 1. Overall Distribution of Pre-Lecture Video Ratings
![Chart 1](/ex09/static/imgs/chart1.png)

### 2. Pre-Lecture Video Rating by Prior Experience Level
![Chart 2](/ex09/static/imgs/chart2.png)

### 3. Difficulty vs. Pre-Lecture Video Desire by Experience Level
![Chart 3](/ex09/static/imgs/chart3.png)

---

## Conclusion

**Summary of Findings:**

The analysis examined whether students with less prior programming experience rate the idea of optional pre-lecture preparation videos more favorably than students with more experience. The data provides moderate support for this idea. The box plot (Visualization 2) shows that students with no prior experience tend to give higher median ratings to the pre-lecture video proposal than students with 2+ years of experience. The  average ratings confirm this as well. Novices rated the idea higher, on average, than experienced students. Visualization 3 further reveals that students who find the course more difficult (which strongly overlaps with students who have less prior experience) also tend to want pre-lecture videos more, suggesting the same people are driving demand.

**Potential Costs, Trade-Offs, and Downsides:**

- *Teaching staff workload:* Creating high-quality pre-lecture videos requires a lot of time from instructors or TAs. If this burden isn't offset by reduced traffic duringg office hours, it adds more work to the instructional team.
- *Student over-reliance:* Optional videos risk becoming essentially required content in students' minds. Students who don't watch might feel disadvantaged during lectures, which could increase anxiety rather than reduce it.
- *Mixed engagement:* Students with prior experience (whcih is a significant portion of the class) found the idea less valuable. Investing heavily in something that a large group isn't necessarily benefited by may not be the highest-ROI improvement.
- *Uneven production quality:* If videos vary in quality across topics, student expectations might become inconsistent.

**Extensions and Future Work:**

1. *Targeted delivery:* Rather than offering videos to all students, the course could survey students at enrollment about their experience level and provide students an option to sign up for videos, which could reduce irrelevance for experienced students.
2. *Measuring impact:* A future version of the analysis could track whether students who watch pre-lecture videos (if they exist) show higher `understanding` ratings or lower `difficulty` ratings mid-semester, creating a feedback loop for continuous improvement.
3. *Exploring alternative formats:* Short readings, interactive code examples, or concept maps might provide the same preparation we're looking for with lower production cost. Future surveys could ask about format preferences explicitly.