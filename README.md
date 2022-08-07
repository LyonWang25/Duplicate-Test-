# Hatchways Frontend Work Simulation

part1
By default, “15 per page” is selected and you will be on page 1

When user changes “X per page” (the only options will be 15, 25, 50 and 100), it should only display at maximum that amount of blogs per page and the first page is displayed

When user clicks on the Previous and Next arrow button, it will display it’s respective page results

If the first and last page is the same, then previous and next arrow buttons are disabled

If user at the beginning of the results, the previous button should be disabled

If user at the end of the results, the next button should be disabled

Current page always have 2 siblings (refer to screenshots below)

Ellipses should be inserted if the first page or the last page is not a sibling of the current page

First and last page must always be displayed

There will always be at least 1 blog post

Please note that for this evaluation, calculations will be done on the frontend and that we are not looking to imitate an API call.

Current page is 1, and it has 2 sibling options next to it. Ellipses before the last page. view image

In the middle of the pagination, with one sibling before and after. Ellipses after page 1 and before the last page. view image

Second last page, one sibling before and after (the last page is the same page as the next page). Ellipses after page 1. view image

No ellipses when there is only one page available. view image

## General Instructions

For this project, you are provided a starting codebase for a React front end and are to build on this starting code by adding new features. The starting code is for the application described in the section below, and you can find your assigned work on the Issues tab of this repository.

Please open a **single pull request** with all of the changes needed to implement the features described in the issue, then return to the Hatchways dashboard to mark your assessment as completed.

We will use [this rubric](https://drive.google.com/file/d/1Lfn6JnanBhuSjMDQaIdIBk1_QK7i9mNU/view) to evaluate your submission. Please note that if your submission does not attempt to complete all of the requirements, or does not pass our plagiarism screening, we will be unable to provide feedback on it. Please contact hello@hatchways.io if you have any questions or concerns.

---

# Introduction to this Application

You will be designing front-end components in React for a simple blogging website. The feature set you will be responsible for is creating a pagination component for the blog posts (`src/data/blogs.json`).

A blog post has the following structure:

```json
{
  "id": 1,
  "author": "Esmeralda Vanne",
  "title": "Duis bibendum. Morbi non quam nec dui luctus rutrum. Nulla tellus.",
  "excerpt": "Cras in purus eu magna vulputate luctus. Cum sociis natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus.",
  "date": "1634439025000",
  "image": "http://dummyimage.com/200x134.png/cc0000/ffffff",
  "readingTimeMinutes": 9,
  "tags": ["crypto", "health"]
}
```

---

### Setup

```
yarn install
```

### Format Code

```
yarn prettier --write .
```

### Development

```
yarn start
```

### Testing

```
yarn test
```
