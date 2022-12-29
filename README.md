# Usage

Run the script in comment-scrapper.ipynb with you own Reddit-ID , Reddit-Secret

## JSON File

### Comments we want to scarpe

![Reddit Comments](assets\reddit.png)
<p align="center">
    <br>
    <img src="assets\reddit.png" width="400"/>
    <br>
<p>

### Structure of JSON File

- Each Submission has two entries
    - Submission Body
    - List of Dictionary of top level Replies 
- Each reply has 3 enteries
    - id of reply
    - Body of Reply
    - List of Dictionary of second level Replies

And this goes on Recursively in a depth first search manner till a reply with no further reply is found

![JSON Structure](assets\json.png)