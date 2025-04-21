# csvtoyoutubemusic
Automatically add YouTube Music Music through a CSV file

# Features
- Nothing much really, adds songs to Liked and that's it for now
- If a song is already liked, it will skip.

# How to use
- Login to your YouTube Music account on the default profile of your Chrome browser
    The app works by automating your existing Chrome profile, this is because Google restricts sign ins from browsers running test software like Selenium
    (Read notice below)
- Export your playlist from your platform of choice to a CSV file, with comma as the delimiter, the first line is always ignored as it is assumed to be the title of your CSV file.
- Open up the app, a new Chrome window should open, maximise the window and make sure the search box is visible, if not, zoom out on the page to make it visible to continue and do not reset or resize the Chrome window. Once you have set up the view, minimize the window and go back to the app.
- Press ENTER to continue and drag the CSV file into the terminal and press ENTER. Make sure the file path does not contain any spaces.
- Once parsed, you will be presented with a list of the songs, the songs are arranged from top to bottom of the CSV file.
- Press ENTER to contimue and press ENTER again after confirming your Chrome sizing and press ENTER, the operation will start.
- You will be provided with a log on your console.
