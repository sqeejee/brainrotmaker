# Reddit Video Generator
This program generates a .mp4 video automatically by querying the top post on the
r/askreddit subreddit, and grabbing several comments. The workflow of this program is:
- Install dependencies
- Make a copy of config.example.ini and rename to config.ini
- Register with Reddit to create an application [here](https://www.reddit.com/prefs/apps/) and copy the credentials
- Use the credentials from the previous step to update config.ini (lines 22 -> 24)

#To get started:
Go into the config file and set your id and secret to the keys given at the reddit api app creation screen
Then, (optionally) use the eleven labs api key (this will allow you to have a more dynamic voice, but does cost money; this step is not necessary)
Navigate to the main.py file and replace the USER in the chrome director to your computer's user name
Run the file and generate brain rot
