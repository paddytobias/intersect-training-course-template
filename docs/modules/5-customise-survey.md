---
layout: page
title: "Customising the survey"
date: 2018-03-21 00:49:07
short-title: "Mod. 5"
show-in-nav-bar: true
teaching: 15
exercises: 5
questions: #add module questions
objectives: #add module objectives
keypoints: #add module key points
---

>Objectives
>- Objective 1
>- Objective 2
>- Objective 3
{: .objective}

Now we have our survey in Qualtrics, let's make it work the way we want.

## 1. Configuring questions and adding answers
With using the import functionality to build our survey, we are somewhat limited with the options to change question types.

> Because the four main question types are text entry, multiple choice, matrix and then the specialty types, we can only move around in these categories when changing a type. A key way to find out what types you can choose from for each category is to click on the question in Qualtrics and inspect your options in the righthand menu.
> { .note}

[ADD SCREENSHOT]

### Steps
1. Because the answer options for `QID4` are kind of on a logical scale, let's set it to `Position > Horizontal`. After this, let's do the same for `QID6`, `QID10` and `QID17`.

For `QID2`, note that we have an `Other` option. Say we want to know what this **other** is. Well let's add in another question to have the respondent specify which other language they speak at home.
2. To do this, go to the question after `QID2` (i.e., `QID3`) and click on the top <span style="color:green"> green + </span> icon.
3. In the new question, type _Please specify which other languages you speak at home_. The set this question to `Text Entry`question type.

[ADD SCREENSHOT]

4. Now let's go and renumber our questions. Note that they are currently all mixed up. This can be done by hovering your cursor over the `QID` number and double clicking. In total you should now have 17 questions.

## 3. Skip logic
With the relationship between Qn `1` and Qn `2`, we can use what Qualtrics calls [**skip logic**](https://www.qualtrics.com/support/survey-platform/survey-module/question-options/skip-logic/). Skip logic allows us to insert conditional pathways in our survey. For example, we don't want to ask Qn `2` to respondents who have answered `Other` to Qn `1`. So in this case, let's add a skip to Qn `1`.

### Steps
1. Go to the ![cog](images/cog.png) icon and `Add Skip Logic...`
2. Enter in the condition: `Other`, `Is selected` Skip to: `3 Do you speak only a non-English language, more of a non-English language than English, both equally, more English than a non-English language, or only English?`
3. The click **Done**



## 2. Adding Blocks

## 3. Add Descriptive text
Insert under each block

## 4. Response validation
Qn13
Qn16

## 5. Add Piped text
Change question 12

## 6. Use Skip logic

## 7. Change look and feel



In the next module we're going to look at how to distribute the survey



## Next
[Go to Module 6]({{ site.baseurl }}/modules/6-[**INSERT MODULE 6 FILENAME**]){: .next-link}
