**DISCLAIMER**: I AM NOT RESPONSIBLE FOR WHAT YOU DO WITH THIS SCRIPT. THIS SCRIPT IS SIMPLY PROOF OF CONCEPT, AND SHOULD NOT BE USED TO CLAIM OR SELL COPYRIGHTED MATERIAL. BY USING THIS SCRIPT, YOU AGREE THAT YOU ARE RESPONSIBLE FOR HOW IT IS USED.

Description: This program captures screenshots of various website elements to create short 1 minute videos for use on social media.

Before we start: I have provided sample folders to use, although this is completely optional.

Instructions to set up the scripts:

1. Install Python: Download and install Python from https://www.python.org/

2. Install Dependencies:
   - For generate_video.py and split_video.py: 
     Run pip install moviepy in the terminal or command prompt.
   - For web_scrape_tts.py: 
     Run pip install selenium pyttsx3 in the terminal or command prompt.

3. Download WebDriver: For web_scrape_tts.py, download the WebDriver for your browser. For Chrome, download ChromeDriver from https://sites.google.com/chromium.org/driver/



Setting Up generate_video.py

- Line 6, 7, 8: Replace YOUR IMAGE FOLDER PATH GOES HERE, YOUR AUDIO FOLDER PATH GOES HERE, and YOUR BACKGROUND VIDEO FOLDER PATH GOES HERE with your actual folder paths.
- Line 50: Replace YOUR OUTPUT FOLDER GOES HERE with the path where you want the final video to be saved.



Setting Up web_scrape_tts.py

- Line 17, 18: Replace YOUR IMAGE FOLDER PATH GOES HERE and YOUR AUDIO FOLDER PATH GOES HERE with your actual folder paths.
- Line 21, 22: Replace YOUR CHROME DRIVER PATH GOES HERE with the path to your downloaded WebDriver file. Replace YOUR CHROME APPLICATION PATH GOES HERE if necessary.
- Line 25: Replace YOUR WEBSITE URL GOES HERE with the URL of the website you want to scrape.
- Lines 30 and various: Replace TITLE XPATH GOES HERE and other placeholder XPaths with the actual XPaths for the elements you want to scrape and convert to text and images. XPATH can be found by downloading a generic "XPATH finder" extension on chrome.



Setting Up split_video.py

- Line 8: Replace YOUR VIDEO FOLDER PATH GOES HERE with the path to your video file.
- Line 9: Replace YOUR OUTPUT FOLDER PATH GOES HERE with the path where the split video segments should be saved.
- Line 27: Replace YOUR CHANNEL NAME GOES HERE with your YouTube channel name or any text you want to add to the video.



Running the Scripts

After setting up, navigate to the folder containing your script in a terminal or command prompt and run the script with Python. For example, to run generate_video.py, type python generate_video.py and press Enter. Follow similar steps for web_scrape_tts.py and split_video.py as needed. Make sure all dependencies are installed and paths are correctly set to avoid errors.

--- 


If you have any problems setting up the script, I will be uploading a YouTube video soon on how to set it up --> https://www.youtube.com/channel/UCc4A-AJk5cE8EUBoccfFS3g
