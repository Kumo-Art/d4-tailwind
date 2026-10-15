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
- Text: