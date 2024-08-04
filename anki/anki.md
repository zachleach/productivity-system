# Anki for Math, Programming, and Computer Science

![Daily Limits](./daily_limits.png)
![New Cards](./new_cards.png)
![Display Order](./display_order.png)
![Advanced](./advanced.png)

## 7-Day Good Interval

The most efficient use of time is to not spend it on things that don't actually matter.

The reason I do '7-day good' is because I'll likely end up reviewing the concepts in the notes again during assignments, projects, lecture, etc. In other words, any smaller interval is often a redundant waste of time.

Moreover, if I've completely forgotten a note 7-days later, then the concept in the note probably never came up again naturally on its own. If that's the case, the note might not be as important or as worth remembering as I initially thought when creating it.

__That last point is really important.__ Anyone who has done Anki before in earnest has experienced the situation where you're spending more time doing *reviewing* than *actually learning*. It fucking sucks.

Consider this schedule as a 2-week trial period for notes. You review the note the next day, then a week later, then another week later. After 2 weeks pass, hopefully you will have learned a lot more and are in a better position to decide whether a given note is worth having, and can more confidently delete notes that aren't.

If the natural state is to forget things, why fight against that when you could use it to your advantage instead? 

## How I use this schedule

While I'm reading, doing assignments, listening to lecture, etc, I keep note of the important concepts or practical applications that come up. 

Here's small snippet of an 'important list' I made while working on a web-development course. 

```
>    html table syntax at a high level
>    statement to import state hooks in react
>    how to get root element from index.html react
>    how to get index of the max value in an integer array in js
...
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

...
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
