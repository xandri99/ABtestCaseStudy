# A/B Test Case Study

In this case study, we examined the effect that different version of the app BestPhotoEditor, each with
notable UI changes, had on user activity. For this, we used a A/B test experiment, where a total of
150.000 new users where segmented in the 3 versions of the app.
We analyzed the differences in behavior that these users presented across the different segments of the
test, to try to determine which of the observed effects could be attributed to the differences in UI, and
not just to random causes. For this, we used a mix of conventional and niche techniques, trying to
explore multiple possible effects, and test for statistical significance the most promising ones
The findings, more detailed in the section ‘Analysis Report’, seem to clearly point out the benefits of
segment 2, introducing tutorial elements to guide and increase their understanding of the app and its
features
While basic engagement metrics such as Retention Rate, Conversion Rate and ARPU were similar
across all segments, Segment 2 stood out significantly in terms of Life Time Value of user (LTV), and
its derived metric averaged Life Time Value of user (aLTV). This segment showed an enhanced LTV,
pointing to a greater potential for revenue growth.
We conducted a statistical significance verification of these results using ANOVA, which showed that
the observed different in LTV across segments was not significant. To further asses this results, I opted
for a less conventional approach using Random Forest models to test LTV as a key differentiator in
spending behaviors among segments.
Thus, this analysis seems to indicate that users in Segment 2, exposed to tutorial-based features, show
a tendency to higher spending. This seems to implicate a potential pronounced increase in revenue
potential from the new UI.


## Project structure:
```yml
├── Makefile
├── notebooks/
│   └── ABtesting_Analysis.ipynb
├── README.md
├── requirements.txt
├── results
    ├── histogram.png
├── setup.cfg
├── setup.py
└── src
    ├── tests
    │   └── test_utils.py
    └── utils.py
```
