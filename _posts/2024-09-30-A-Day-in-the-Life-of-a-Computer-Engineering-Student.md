---
title: A Day in the Life of a Computer Engineering Student
date: 2024-09-30 14:23:18 +0200
categories: [Agile Methodologies, Software Development]
tags: [BDD, Cucumber, Agile, User Stories, Software Engineering, Lo-Fi UI Sketches]
---

# A Day in the Life of a Computer Engineering Student

As a computer engineering student, my daily routine involves applying agile methodologies, specifically **Behavior-Driven Design (BDD)**, and utilizing tools like **Cucumber** to keep software development aligned with user needs.

One of the core principles I work with is writing **SMART user stories**—which are specific, measurable, achievable, relevant, and time-bound. Instead of vague requirements like “make the UI more user-friendly,” we refine them into clear, actionable goals, such as:

- **User Story Example**:
    - **As a** user
    - **I want to** search for a movie by title
    - **So that** I can find and read reviews.

This clarity helps developers focus on concrete, measurable goals and forms the foundation for automated tests.

In practice, we often use **Cucumber**, a tool that translates these user stories into automated, executable tests. Here’s how a user story can be transformed into a Cucumber scenario:

- **User Story: Search for a Movie**
    - **Feature**: Search for a movie by title
    - **Scenario**: User searches for a movie
        - **Given** I am on the Rotten Potatoes home page
        - **When** I search for "Inception"
        - **Then** I should see "Inception" in the search results.

The corresponding Cucumber code for this scenario would look like:

```gherkin
Feature: Search for a movie
  Scenario: User searches for a movie by title
    Given I am on the Rotten Potatoes home page
    When I search for "Inception"
    Then I should see "Inception" in the search results
```

This scenario isn’t just a static description—it serves as a live, automated test that runs to check if the system meets the specified criteria. For instance, when a user searches for "Inception," the system must return that movie in the results. This approach ensures continuous validation of features, helping to avoid misunderstandings and ensuring the project stays on track.

We also emphasize **Lo-Fi UI Sketches** during the early stages of development. Before diving into code, we sketch the user interface by hand, creating simple visuals that are easy for all stakeholders to understand. In a recent project, we sketched how users would search for movies and view reviews, which allowed us to get feedback and refine the design before any code was written.

Collaboration plays a crucial role in our development process. Our team uses concepts like **points and velocity** to estimate the workload for each sprint. Each user story is assigned a point value based on its complexity, and our team’s velocity—the average number of points completed per sprint—helps guide planning for future iterations. For example, if the "search for a movie by title" task is estimated at 2 points, we consider our team’s velocity to decide whether we can finish it within a sprint.

These practices, from BDD to Cucumber tests, Lo-Fi UI sketching, and sprint planning, make my experience as a computer engineering student a blend of theory and hands-on application. The focus is always on building functional, user-centered software that addresses real-world needs efficiently and effectively.
