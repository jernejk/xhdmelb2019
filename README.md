**<https://github.com/jernejk/xhdmelb2019>**

## **Bronze**: To Do App

PBI:

> As a teenager,
> 
> I want to maintain a list of tasks
> 
> So I know what to do

### Acceptance Criteria

#### MVP

- User is able to add, via a free text field, a new item to the list
- User is able to mark an item as completed

#### Gold Plating

- User is able to edit an item in the list
- User is able to remove an item from the list
- Completed items should show in the bottom of the list

Note: The data does not need to be saved into a database

## **Silver**: RSS Feed App

### PBI

> As a blog reader,
> I want to specify my favourite blog
> So that I can read them in order

### Acceptance Criteria

You can use this to get the RSS in JSON [https://rss2json.com](https://rss2json.com/)

#### Example

<https://api.rss2json.com/v1/api.json?rss_url=https%3A%2F%2Fpassos.com.au%2Frss%2F>

#### MVP

- Display RSS Feed from a fixed URL

#### Gold Plating

- User is able to add a new RSS feed to the list
- User is able to edit an RSS feed
- User is able to remove RSS feeds from the list
- User clicks on the fetch button to load all the RSS posts and render it.
- Post list should be sorted by most recent and fields to display are:
- Title with a link to the post
- Which feed is coming from, ideally including the color
- Summary
- User can disable an RSS feed which will automatically filter out all posts from the list
- Color code each feed automatically

Note: The data does not need to be saved into a database

#### Sample Blog sites:

- <https://azuregems.io/rss>
- <https://jkdev.me/rss/>
- <https://kymphillpotts.com/atom>
- <http://weeklyxamarin.com/issues.rss>
- <https://lachlanwgordon.com/rss/>

## **Gold **: Trivia App

### PBI

> As a trivia addict,
> 
> I want to respond to questions
> 
> So that I can see my score at the end.

### Acceptance Criteria

#### MVP

- There should be 20 questions in the question pool
- User can select an answer
- Only 1 item will be shown at a time (e.g.: Who wants to be a millionaire style show)

#### Gold Plating

- Only 10 questions will be used, randomly picked from the question pool
- The user can only go forward, not backward
- At the end of the trivia, give a score to the user in "X out of 10" format
- Let the user start a new game without refreshing the page

**Note**: The data does not need to be saved into a database
