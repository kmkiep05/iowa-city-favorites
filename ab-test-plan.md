# A/B Test Plan – Iowa City Favorites (HawkSpot)

## 1. Page and Element Being Tested

The experiment will take place on the homepage (`index.html`). The single element being changed is the main homepage headline.

- **Version A (Control):** "Find your next favorite Iowa City experience."
- **Version B (Variant):** "Discover affordable things to do in Iowa City this weekend."

All other homepage content, images, buttons, navigation, and formatting will remain identical. Version B will be published as a separate test page with a noindex tag and a canonical tag pointing to Version A. It will not be included in the sitemap.

## 2. Hypothesis and Reasoning

I hypothesize that Version B will generate a higher percentage of positive responses than Version A. The revised headline is more specific and directly communicates two important benefits for the target audience: affordability and weekend activities. Since the website is designed for Iowa City college students looking for affordable things to do, I believe a more direct headline will make visitors more interested in exploring the website.

## 3. Model, Persona, Prompt, and Assignment

**AI Model:** GPT-6. The same model version and settings will be used for every trial. The exact model/version displayed at the time of testing will be recorded.

**Visitor Persona:** A University of Iowa undergraduate student who lives in Iowa City, has a limited student budget, and is looking for affordable activities to do with friends over the weekend.

**Exact Prompt:**

"You are a University of Iowa undergraduate student who lives in Iowa City, has a limited student budget, and is deciding what to do with friends this weekend. You want affordable, interesting local activities and have not already chosen a plan. Read the webpage below. Based only on the information provided, would you click the 'Explore This Weekend' call-to-action to look for an activity? Answer YES or NO as your first word, followed by one sentence explaining your decision. Do not assume information that is not included on the page.

Each trial will take place in a new conversation with no memory of previous trials. The complete page text will be provided in the same format each time, with only the headline differing.

**Random Assignment:** Before testing begins, 100 trials will be randomly assigned to Version A or Version B using a random number generator. Each version will receive exactly 50 trials. The assignment will be recorded before each trial is conducted.

## 4. Primary Outcome and Measurement

The primary outcome will be the percentage of AI visitors who indicate that they would click the "Explore This Weekend" call-to-action.

Responses will be recorded as:
- YES = Positive response
- NO = Negative response

Responses that do not clearly indicate YES will be recorded as NO. All trial outputs will be retained, and no trials will be removed from the final dataset.

## 5. Sample Size and Timeline

The experiment will include 100 total trials:
- Version A: 50 trials
- Version B: 50 trials

The experiment will launch no later than Tuesday, November 17, 2026. Data collection will take place from November 17 through November 26, with approximately 10 trials completed per day. All 100 trials will be completed before analyzing the results.

## 6. Comparison and Success Criteria

The percentage of positive responses for Version A will be compared with the percentage of positive responses for Version B. The difference will be measured in percentage points, and a two-proportion statistical test will be used to determine whether the difference is statistically significant at the 0.05 significance level.

The results will support my hypothesis if Version B produces a higher positive response rate than Version A and the difference is statistically significant. If the difference is not statistically significant, I will report that the experiment did not provide sufficient evidence that the revised headline performed better.

Regardless of the outcome, all 100 trials will be included in the final analysis.
