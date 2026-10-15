## Tailwind Notes


## Setup
- Add the script tag(<script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>) in the '<head>'. No css file needed
- Tailwind resets the browser defaults.


## Utility classes
- Every tailwind class = one CSS declaration.
- 'bg-teal-700' = background-color. ' text-white' = color.
- The styles go in the 'class', not in a CSS file.


## shortcut ctrl + alt
-used to edit multiple lines of code






## Scales
- Spacing number x 4 = pixels. 'p-6' = 24px.
- 'p' = all sides, 'px' = left&right, 'py' = top&bottom, 'pt' = top only.


## Hover
- 'hover:' = only while the mouse is over it.
- 'transition' = fade the change smoothly.
- A prefix says when a class applies.


## Text on top of an image
- Outer box: 'relative' + a height ('h-64').
- Image: 'absolute inset-0 w-full h-full object-cover' = out of the flow, stretched to the edges of Outer box.
- Dark layer: 'absolute inset-0 bg-black/50' (black at 50% opacity).
- Text: 'relative' , and it comes last in the HTML so its drawn on top.


# Responsive Notes


## Breakpoints
- 'md:grid-cols-3' = at 768px and up. A floor, not a range.
- No prefix = always, even on the smallest screen.
- sm: 640, md: 768, lg: 1024, xl: 1280.



## More than columns
- 'p-4 md:p-6' = less padding on phones, more on bigger screens.
- 





## Media queries
- '@media (min-width: 768px) { ... }' = only 


##