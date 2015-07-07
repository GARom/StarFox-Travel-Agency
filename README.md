## Starfox Galaxies Travel

### What is Involved

- **Foundation**
 	- As the client-side framework for this layout project. 
	- Not all components of Foundation are used, only the necessary.**
- **Sass**
	- For your css preprocessor.
	- nested style
	- variable	
- **Layout**
	- The mobile layout requires a **dropdown nav**.
	- **Media Query Ranges**: The layouts included show small, medium, and large sizes. 
- **Server**
	- **LiveReload**.
	- Utilized **gulp** for your task runner (runs the server, gulp, gulp-sass, and livereload).
	- Instructions for **gulp+sass+livereload** setup are [here](https://gist.github.com/theRemix/b9f10de0bead6a7eaf5a)

### Process

1. Whiteboard the layout at all sizes, from the most complex layout to the least complex layout and label the structure with appropriate **Foundation** classes, and add in your own classes and divs where appropriate.
	- mark divs with appropriate **.rows** and **.columns**
	- mark divs with **hide-for-** and **show-for-** classes
	- if there are any sibling **.row** items, it is a good idea to wrap them in a div with an your own identifying class.
2. Write the HTML markup for the layout using the most complex layout as a reference.
3. Ask an instructor to check your markup.
4. Style the layout mobile-first, in this (suggested) order:
	- set base styles (base font size, general font, etc)
	- fine-tune your structural components/layout (widths, columns, padding, and margin)
	- typography
	- any other elements and details
	

==========
