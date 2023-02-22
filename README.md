# youtube-redesign-concept

Figma link:
https://www.figma.com/file/B4RVBhhVzAEPIvkVt6maOq/YouTube-Redesign-Concept-(Copy)?node-id=0%3A1&t=CWlXKqOGOYUAU95P-0

### Description of ur project.

The goal of project is to make new design for popular 
video provider YouTube.

Redesign project contains main youtube pages such as 
home page, video page, channels page, library page, liked vide page,
trending page etc. (Explained in figma markup).

YouTube API used for authorization and video access.
Backend models used for analytics.

### Main functions with the overview of ur future application
- Authorization (using google accounts API)
- Video access (Ability to like videos, save it, divide by categories)
- Share videos
- Subscribe to video channels
- Analyze user activity (Time spent, most watched categories, etc)

### Data models description.

- Video:
    - name
    - description
    - video link
    - video duration
    - likes
    - dislikes 
    - views

- Channel
    - name
    - description
    - owner
    - videos
    - subscribers

- Analytics
    - most viewed videos
    - liked videos
    - most viewed categories
