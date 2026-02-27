User Interaction Document

Problem Statement: We need to find the words from the images having word puzzle & highlight in the image as a agentic AI langflow output.

User Flow

We will collect all the random letters from the image. AI - Tool Call: To extract the Letters from the Image & Prepare the table.
We should know all the words present inside the image. For Ex: THANOS, BATMAN, SPIDERMAN, CAPTAIN AMERICA AI - Search the words inside the Table & Highlight. AI - Search the words in horizontal, vertical & diagonal manner for matching.
How to plot the puzzle words inside the LLM/Image Suggestion: we can prepare the plotting for word puzzle inside the table format in html. Ask LLM to find the word from the table & highlight it. AI - Prepare table with highlighted output in HTML.
Prompt for extract: Extract the 2D Letter Grid from the image in JSON. Highlight the word from the 2D Grid.

Chat input (Image) --> Extract the Letters & keep in HTML Table format --> Search the Words inside the HTML Rows & Columns to make a word --> Highlight the words in different color inside the HTML & Give the output. Chat input -->

Tools Required: Custom Component Python Intepretor (REPL)

This component should display the HTML with Higlighted keywords in Word GRID puzzle.
Langflow Diagram:
<img width="1280" height="532" alt="image" src="https://github.com/user-attachments/assets/69c198b5-af3d-43b2-bf7d-9399528ff280" />

Output:
<img width="1280" height="571" alt="image" src="https://github.com/user-attachments/assets/15094645-b7ec-4c5a-b53b-00b8e56d03a0" />
<img width="1280" height="572" alt="image" src="https://github.com/user-attachments/assets/ef2bd35a-cb5e-4f59-8314-e21eab7c73e6" />


