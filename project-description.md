# Test Project Outline – Module E – Speed Tasks

## Competition time

2 hours

## Introduction

This module tests your ability to apply HTML, CSS, and JavaScript effectively and creatively. You must complete several short tasks within the competition time. Tasks range from simple, routine exercises to more complex challenges. You can usually spend 10 to 20 minutes on each task.

## General Description of Project and Tasks

Starter files and reference media for each task are provided under `assets/` in numbered folders (`01`–`10`), matching the task numbers below.

Your working directory must contain **10 subfolders** named `Task-01` through `Task-10`. Each folder must contain the solution for the corresponding task. **Each task must be committed separately in Git.**

## Requirements

The following tasks must be implemented.

### Task 1: HTML/CSS (Easy)

Starter files: `assets/01/` (`index.html`, `style.css`, `wheel.png`).

Create a web page that displays the provided image (`wheel.png`) and use CSS to make it rotate continuously so that the wheel appears to spin on the page. Using JavaScript is not allowed — CSS only.

### Task 2: JS (Easy)

Starter files: `assets/02/` (`index.html`, `script.js`).

In the `script.js` file, you will find an array of transport line numbers:

```text
["ligne n°1", "bus n°24", "tramway n°3", "ligne n°2", "bus n°20", "tramway n°312", "ligne n°130", "bus n°28", "tramway n°20", "ligne n°101"]
```

Sort the lines in ascending order by their number and output the result to the browser console.

Example result:

```text
["ligne n°1", "ligne n°2", "tramway n°3", "bus n°20" ...]
```

### Task 3: HTML/CSS (Medium)

Reference video: `assets/03/drip-sample.mp4`.

No code is provided. Implement a looping drip effect using only HTML and CSS, based on the provided video. Review the reference video and create the same effect.

### Task 4: JS (Medium)

Starter files: `assets/04/` (`index.html`, `css/style.css`, `js/todo.js`). Reference video: `assets/04/sample/sample.mp4`.

Using JavaScript, create interactive functionality for a to-do list application. Users must be able to add, filter, and manage tasks efficiently, and tasks must be saved automatically for future sessions.

Requirements:

- **Add task:** ability to add a task with a title, description, and category.
- **Filter by category:** buttons _(All, Work, Personal, Urgent)_.
- **Mark as complete:** toggle task state using a checkbox.
- **Save tasks:** use `localStorage`.

HTML and CSS are already provided. Focus only on JavaScript. Code goes in the `js/todo.js` file.

### Task 5: JS (Easy)

Starter files: `assets/05/` (`index.html`).

Create JavaScript code that displays the user's current time. The clock updates every second. Format: **HH:MM:SS**. A basic template is provided.

### Task 6: HTML/CSS (Easy)

Reference video: `assets/06/example.mp4`.

Style a button with animation as shown in the video.  
**Button color:** `#725ac1`

### Task 7: HTML/CSS (Medium)

Reference video: `assets/07/video.mp4`.

Create the animated navigation menu shown in the video.  
**Color:** `#e8e8e8`

### Task 8: JS (Hard)

Reference video: `assets/08/example.mp4`.

Create a `box-shadow` generator tool with the following parameters:

- **x offset:** from `-50px` to `50px`
- **y offset:** from `-50px` to `50px`
- **spread:** from `-50px` to `50px`
- **blur:** from `0px` to `100px`
- **color:** selected via `color input`

Requirements:

- Sliders (`input type="range"`) for all parameters except color
- Slider color changes together with the selected shadow color
- **Copy** button copies the `box-shadow` value to the clipboard
- The generated style is applied to the container in real time

Follow the video example.

### Task 9: JS (Medium)

Starter files: `assets/09/` (`index.html`). Reference video: `assets/09/example.mp4`.

HTML and CSS are provided. There is a box on the screen. When clicked and held, the box must be draggable across the screen, and when released, it must stop.

Dragging must be smooth, without jerks or flickering. See the video example.

### Task 10: HTML/CSS (Easy)

Reference video: `assets/10/Example.mp4`.

Style a text field and animate focus acquisition as shown in the video.  
**Color:** `#c200fd`

## Assessment

Module E will be assessed using the latest stable version of Google Chrome and Firefox. Each speed task is evaluated against its requirements and reference media (videos, starter files). HTML, CSS, and JavaScript solutions are checked for correctness, visual fidelity to the examples, and adherence to task constraints (for example, CSS-only where JavaScript is not allowed). Git commit history is reviewed to confirm that each task was committed separately.

## Mark distribution

The table below outlines how marks are broken down and how they align with the WorldSkills Occupation Standards (WSOS). Please read the Technical Description for a full explanation of the WorldSkills Occupation Standards.

| WSOS SECTION | Description                            | Points |
| ------------ | -------------------------------------- | ------ |
| 1            | Work organization and management       | 0.5    |
| 2            | Communication and interpersonal skills | 1.5    |
| 3            | Design Implementation                  | 3.5    |
| 4            | Front-End Development                  | 4.5    |
| 5            | Back-End Development                   | 0      |
| **Total**    |                                        | **10** |
