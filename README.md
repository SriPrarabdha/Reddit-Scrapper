# Usage

Run the script in comment-scrapper.ipynb with you own Reddit-ID , Reddit-Secret

## JSON File

### Comments we want to scarpe

![Reddit](assets\Screenshot 2022-12-29 121808.png)

### Structure of JSON File

- Each Submission has two entries
    - Submission Body
    - List of Dictionary of top level Replies 
- Each reply has 3 enteries
    - id of reply
    - Body of Reply
    - List of Dictionary of second level Replies

And this goes on Recursively in a depth first search manner till a reply with no further reply is found

![JSON](assets\Screenshot 2022-12-29 122755.png)