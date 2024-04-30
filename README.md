# llm-archives

### Instructions

Click the "Use this template" button for this repository and choose "Create a new repository". You can give it the same name (llm-archives).

Once it's ready, go to [Groq](https://console.groq.com/keys) and follow the directions to get an API key. You'll need to login (or create an account if you don't have one).

Copy the API key value and then click on the Settings of your GitHub repository and click on "Secrets and variables" on the left side, then choose "Codespaces"

Click the green "New Repository Secret" button and paste your API Key into the "Secret" box, then put GROQ_API_KEY in the Name box above it. Click "Add Secret" and click on the name of the repository to return to the main page.

From there, click the green "Code" button and create a new Codespace in the Codespaces tab.

In the Terminal type the following: pip install requests groq and hit enter.

Then type: python get_stories.py

You should see a file called cns_maryland_posts.json appear. Let's look at it. It contains some details of the past 10 CNS stories.

Back in the Terminal, type: python entity_extraction.py and watch the output.

### Evaluation for JOUR389W

PUT YOUR EVALUATION HERE
Overall, this was really good tool and the output it produced was really strong. It correctly identified all the information that was relevant to the article, and then correctly identified the people and organizations mentioned in the article with correct attributions. This is probably the best output (on a small scale) that we have seen from a generative AI model in this class.
If my publication (FT) had access to this, it is plausible that we could use the outputs provided by a script like story.py as a way to generate tags and file away stories for faster access across some sort of database. For example, the publication could count and quickly show a table of all the stories they've published mentioned Carnegie Mellon University.