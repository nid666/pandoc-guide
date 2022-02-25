# Converting From Markdown to Word

To convert from Markdown to Word you will first need to open up the terminal or command prompt depending on your operating system. 

## Terminal/Command Prompt Instructions:

### Windows

1. Press and hold the windows key on your keyboard

	*This will be on the bottom left corner and will have the windows logo on it*

2. While the key is pressed, hit the "R" key

3. In the "Run" window that pops up, type "cmd"

4. Press Enter

### Mac

1. Press the command (⌘) key and the spacebar at the same time

2. Type "terminal" into the search bar

3. Select the following icon in the menu: 

	<figure>
	<img src="media/Mac4.png" alt="Image of Mac terminal search result">
	<figcaption>Figure 1: This is the icon you should select to access the terminal</figcaption>
	</figure>

## Conversion Instructions

1. Move the markdown file you want to convert onto your desktop

2. In the terminal or command prompt type

	> cd Desktop

3. Then copy and paste the following command into the window:
	> pandoc -s input.md -o output.docx

4. Modify the "input.md" to match the name of your markdown file on your desktop

5. Optionally, you may change the name of output.docx to change the name of the output file before it is made

6. Once you press enter, the outputted .docx file will be generated and saved to your desktop


{% include footer.md %}