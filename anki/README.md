# Anki for Math, Programming, and Computer Science

![Daily Limits](./daily_limits.png)
![New Cards](./new_cards.png)
![Display Order](./display_order.png)
![Advanced](./advanced.png)

---

## Why '7-day' good interval

1.	In problem solving subjects, you often implicitly review the concepts several times during assignments, projects, lecture, etc., so adding an additional reviews in Anki on top of that via shorter intervals (e.g., "10m 1d 3d") is a waste of time.
2.	Increased interval lets you decide whether a note is worth keeping or deleting. Deleting bad notes will save you from review fatigue.
3.	Selecting `Hard` during the learning phase will schedule it 4-days later. (In case you're afraid you will forget before 7-days). 

## How I use this schedule

While I'm reading, doing assignments, listening to lecture, etc, I keep note of the important concepts or practical applications that come up. 

Here's small snippet of an 'important list' I made while working on a web-development course. 

```
>    html table syntax at a high level
>    statement to import state hooks in react
>    how to get root element from index.html react
>    how to get index of the max value in an integer array in js
```

After N amount of hours have passed and mental fatigue has accumulated to the point where it's starting to hard to continue working, end the session by going through your important list and answering all the questions.

```
>    html table syntax at a high level
<table>
    <tr>
        <td>
        </td>
    </tr>
</table>

>    statement to import state hooks in react
import { useState } from 'react'

>    how to get root element from index.html react
document.getElementById('root')

>    how to get index of the max value in an integer array in js
arr.indexOf(Math.max(...arr))
```

Finally, manually copy paste each into Anki.

## Keep track of higher level concepts separately

Good Anki notes are short and specific. Compound notes that require you to recall several things are a bad idea. If you're having a hard time coming up with a good review question for a concept, ask ChatGPT to generate some.

I keep note of higher-level, more abstract, concepts in a text file separate from Anki. Anki is great at helping you retain the important *details*, but you're likely going to forget the top-level concepts. 

Below is an example of a list of the important broader concepts I made while working on projects within a web development course.  

```md
courseinfo project
	spin up a basic react project
	functional components

unicafe project
	state hooks
	buttons that update state when clicked
	conditional rendering
	html tables

anecdotes project
	modifying state re-renders the component

courseinfo (pt. 2) project
	rendering collections
	array#map()
	array#reduce()
	refactoring components into separate modules
```

Functionally, this serves no other purpose than the personal satisfaction of being able to to look back at the end of the month and see what you've done. I could think of several use-cases for it, but that's outside the scope of this mini-tutorial.
