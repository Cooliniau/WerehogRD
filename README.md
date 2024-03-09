# Werehog R&D
Research and development of ideas and facts relating to the Werehog, from 'Sonic Unleashed' (2008).

Community and archive by ini (🟣) of Cooliniau.
![alt text](https://pbs.twimg.com/media/FnXYLWXXEAYsXGL?format=jpg&name=orig)

## **Essential Links (more info below)**

- Werehog R&D: https://twitter.com/i/communities/1547719903578243072 / https://discord.gg/PfhJGVKNCT

- SingleFile: https://github.com/gildas-lormeau/SingleFile

- OldTwitter: https://github.com/dimdenGD/OldTwitter

- uBlock Origin: https://github.com/gorhill/uBlock

- GitHub Desktop (if you want something easy-ish to use for repo management): https://desktop.github.com/

## **ini's Notice**

This repository's goal is to archive at least MOST of the Community's ideas and findings featured on Twitter. 
The main format for archiving such content would be through saving the page as an HTML via the *"SingleFile"* addon, while also using another addon called *"OldTwitter"*.

The latter addon in particular allows for videos in Tweets to be loaded as something that can actually be saved as a video, and so the SingleFile addon can easily provide a link at the top left corner of the video preview that lets the user open the video in a new tab. The lack of a large empty space of nothing around the bottom portion of the page also makes OldTwitter much more favorable, as opposed to just using SingleFile on the regular Twitter website.

Both of these extensions in terms of their functions are crucial to archiving our Twitter posts inside the Werehog R&D Community page, so it's important for all members and anyone else to keep that in mind when contributing archived content of the Community.

All that aside, I'll proceed updating this repo as time goes on. For now, I simply wanted to get a head start !! - ini

##  **Getting Started**

- Anyone that actually wishes to contribute to archiving needs to be at least familiar with commits, forks, pushes, and pulls. Familiarize yourself with how the process works in a nutshell, and I'd also recommend using *GitHub Desktop* just for ease of use (imo anyway; if you're already using something akin to it, stick with that).

- Before anything else, make sure you have OldTwitter installed and ready to go. Then go to Twitter > click on your icon at the top right > Settings, and enable these settings (you can use Ctrl+F to Find these quickly)...
  - "Save preferred video quality" = Enable
  - "Disable large font for short/popular tweets" = Enable
  - "Hide trends" = Enable
  - "Hide 'Who to follow'" = Enable
- After that, head over to a random Tweet that has a video on it and select the highest resolution out of the 3 options right below it (preferably 1280p).
  - This will make OldTwitter remember your quality option and will play a somewhat big role in video resolution when you're saving Twitter pages as HTML.

- Be sure to have GitHub Desktop set up on your machine already, and clone the repo by going to this page > Code > Open with Github Desktop > Allow links to be opened by x-github. When on GitHub Desktop, just follow the prompts it gives you and you *should* have the repo on your machine.

- Head to the directory of the repo, and extract the contents of uBlock_and_SingleFile_Settings.zip to a different folder outside the repo folder. If you have uBlock and SingleFile set up already, then:
  - uBlock:
    - Left-click the extension
    - Click the gears icon
    - Go to "My filters"
    - Click "Import and append"
    - Go to the .txt file with uBlock in its name (extracted from the .zip file), and import it.
  - SingleFile
    - Right-click the extension
    - Go to "Manage Extensions" (I'm using Firefox)
    - Head over to the extension's dedicated Options page
    - Scroll down and click "Import"
    - Go to the .json file with SingleFile in its name (extracted from the .zip file), and import it.

- With all of this taken care of, you can *now* start archiving pages!
  - Head over to the Werehog R&D Twitter Community page
  - Find any new Tweet that has yet to be archived (you can check existing archives by clicking on the HTML files inside the repo)
    - Make sure you are on the page of the 1st Tweet in a whole thread and your scrollbar is at the very top.
    - Only try to capture reply threads if the main thread is *also* visible—otherwise, only proceed with the main thread.
  - Left-click the SingleFile extension in your browser's toolbar to save the page
  - Use this naming scheme when the file save prompt comes: "WRD-(insert-username-here)(Concept/Adjust/Showcase)-(insert-number-here).html"
    - If you aren't sure how to go about this, use the exisiting HTML files in the repo as a frame of reference !!
    - "Concept" is for #WerehogConcept Tweets or Tweets that talk about ideas but aren't properly labeled.
    - "Adjustment" is for #WerehogAdjustment Tweets or Tweets that talk about specific adjustments but aren't properly labeled.
    - "Showcase" is for Tweets that aim to simply showcase features and/or facts already present in the original game; usually in video format.
  - Save the HTML file(s) in the corresponding folder inside the **repo directory**.
  - Go to GitHub Desktop, and you should see file(s) with a green "+" icon to its left; that simply means a new file was added into the repo directory.
  - Go to the bottom left area where it says "Summary" and "Description", and place whatever title and comments you wish to give to your commit.
  - After that's done, click the blue "Commit to **main**" button below the "Description" box. Then go to the top of the window where it says "Push origin", and click it to push your additions to the **main** branch of the repo. That's that, you've successfully

## *Warnings and Tips*
- It is ***IMPERATIVE*** that you had a separate folder outside the repo in which you store *backups* of the HTML files you create.
- It is also ***HIGHLY IMPORTANT*** that you are extremely careful in both handling repo files and commiting changes.
  - If you accidently delete a file/folder in your repo directory: go to GitHub Desktop, click on the change itself (it should show itself as a red "-" icon), and delete the change. Do ***not*** commit mistakes like these to the main branch.
  - If you wish to be even MORE careful—although this is optional, you may create a fork or new branch of the main branch that makes your cloned repo be its own thing.
    - Go to "Current Branch" > Click on "New branch" > Give it a name of your choosing > Click on "Publish branch" to commit it to the repo > Now your cloned repo on your machine falls under that new branch, not **main**.
    - Any changes you make within this new branch that's fine for the main repo can be merged with the main branch.
      - Click on "Current Branch" > Switch to **main** first > Click on "Choose a branch to merge into **main**" > Select your branch > Click "Create merge commit" > Click on "Push origin" > Done!
      - If you wish to delete items you commited to both **main** and your branch, then delete the files in your local repo first while in **main** and then do it again while you are in YOUR own branch.
- Be sure to click the "Fetch origin" button periodically in case any new changes to the repo have made—from there, click "Pull origin" to have those changes be applied to your local cloned repo. It is VERY important to make sure you are keeping your repo up-to-date and not commiting any old files !!
