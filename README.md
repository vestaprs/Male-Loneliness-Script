Basically, I re-ran the code with a new script (Male_Loneliness_Project_v2.ipynb)
    1. It re-pulled r/AskMen (posts and comments, since comments are the answers to the questions posed in the threads and would be more useful data
    2. It pulled the r/exredpill data
    3. It took the data we already pulled from r/lonely and r/forever alone from the old script's data (removed r/MGTOW since its banned from reddit and they don't want us to look at banned data, and removed r/AskMen because it was incomplete in the old file) and combined it with the new r/AskMen and r/exredpill
This file is called "combined_raw" (too large to upload to GitHub)
    4. Data was then cleaned to remove both removed and deleted posts, or posts that were too short in wordcount to analyze
This file is called "cleaned_all" (too large to upload to GitHub) and the file that describes what was cleaned is called "cleaning_log"
    5. The code looked in the cleaned_all data to find f-tags (denoting female reddit users posts) and tagged them so that we are aware.
This was called "f_tag_report"
    6. A random sample of 3000 posts from each reddit thread (r/lonely, r/AskMen, r/ForeverAlone, r/exredpill) were pulled for analysis - this method was similar to the Reddit discourse on Mpox paper
This was called "analysis_sample" and a version that removed all the f-tags from this analysis sample was called "analysis_sample_no_F_tags"# Male-Loneliness-Script
