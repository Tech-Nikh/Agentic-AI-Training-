Goal:

User want to search & highlight words from image having letter grid. [https://www.rd.com/wp-content/uploads/2020/04/house_wordsearch-scaled.jpg?fit=750%2C750&original_fit=700,700]
Agentic Flow

User will input the prompt for keywords he need to search in grid.
A transformer agent will fetch the image from URL and convert into Base64 Format.
A transformer agent will convert Base64 format into 2D JSON Grid.
A word search component will search the inputted keyword inside the 2D JSON grid. It will search the keywords in 2D JSON Grid & format in html as Output.
Agent Components & Responsibilities:

Input Function:

Input will be received from end user through chat input component.
Input should be passed to LLM to generate the specific keywords.
It should give specific keywords comma seperated as a output in capital letters. For ex: KITCHEN,FOUNDATIONS,DRAINPIPE
Base 64 Image Conversion Agent:

A word grid image specified from particular URL should be fetched by this agent.
It should convert this image content to Base64 using LLM Call.
It should give output a Base64 Format.
Convert Base64 to 2D JSON Agent

Output text obtained from base64 conversion agent should be received as a input.
This input should be pass to LLM to convert Base64 text into 2D letter JSON GRID.
Words Finder & Highlighter Component

2D JSON Grid obtained from above agent should be received as input.
Keywords obtained from input component also should be taken as input.
Keywords should be searched in JSON & will be highlighted in HTML format.
HTML Format with highlighted keywords should be given as Output.
User Output Component

This component should display the HTML with Higlighted keywords in Word GRID puzzle.
Langflow Diagram:
<img width="1280" height="532" alt="image" src="https://github.com/user-attachments/assets/69c198b5-af3d-43b2-bf7d-9399528ff280" />

Output:
<img width="1280" height="571" alt="image" src="https://github.com/user-attachments/assets/15094645-b7ec-4c5a-b53b-00b8e56d03a0" />
<img width="1280" height="572" alt="image" src="https://github.com/user-attachments/assets/ef2bd35a-cb5e-4f59-8314-e21eab7c73e6" />


