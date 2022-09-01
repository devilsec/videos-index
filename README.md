# DevilSec Videos Index

This repository contains an index of all DevilSec videos, particularly those hosted on YouTube.  

This repository is maintained by DevilSec's social media team.  


## Index Files

### Videos

The `videos.json` is the index of all DevilSec videos.  

All videos are objects of a 'videos' array.  
Each video object contains the following attributes:  
- Title: A string value which represents the name of the event.  
- Speakers: An array of speaker indexes which match a speaker in the Speakers index (`speakers.json`) present in the `github.com/devilsec/events-index` repository.  
- Date: An ISO 8601 date timestamp. It must only contain the date and no time value.  
- Tags: An array of tag indexes which match a tag in the Tags index (`tags.json`). The array should be left empty if there are no tags.  
- Video URL: A URL towards where the video in question is hosted and published (e.g. `https://youtube.com/watch?v=test`).  
- Description: A string value representing the description of the video.  


### Tags

The `tags.json` is an index of tags that are used as descriptors of videos.  

All tags are objects of a tags array.  
Each tag object contains the following attributes:  
- ID: An integer value represeting a unique ID of a tag.  
- Name: A string value representing the name of the tag.  

