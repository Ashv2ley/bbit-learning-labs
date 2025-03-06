# Runkeeper Tweet Report

**INF 133 - User Interaction Software - Winter 2025**

**Assignment 2: Runkeeper Tweet Report in JavaScript and TypeScript**

## Overview

This project involves analyzing and summarizing a week's worth of tweets from the RunKeeper app using JavaScript and TypeScript. The goal is to present information in an organized manner through a webpage, helping researchers understand patterns in RunKeeper-related tweets.

## Features Implemented

1. **Summarizing Tweets (`about.js`)**
   - Extracted and displayed the earliest and latest tweet dates.
   - Categorized tweets into four types: Completed events, Live events, Achievements, and Miscellaneous.
   - Identified user-written tweets and calculated the percentage of tweets containing user-generated content.
   - Used DOM manipulation to dynamically update the report based on the dataset.

2. **Identifying the Most Popular Activities (`activities.js`)**
   - Determined activity types from completed tweets.
   - Converted distances from kilometers to miles where applicable.
   - Identified the three most frequently logged activity types and displayed them dynamically.
   - Used Vega-Lite to visualize distances logged for each activity type and analyze distance variations by the day of the week.

3. **Adding a Text Search Interface (`description.js`)**
   - Created a functional search interface for filtering tweets based on text input.
   - Implemented case-insensitive text
