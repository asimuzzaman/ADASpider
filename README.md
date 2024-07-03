# ADASpider
A research project on ADAS

### Data: Posts
- **`post_id`**: Unique ID for each post
- **`tags`**: All tags for each post are enlisted in one cell separated by comma and enclosed by double quotation (") marks to escape `comma` in CSV files. eg. `"driveworks,driveos"`
- **`score`**: A numeric value to indicate the reach/engagement of a post

### Data: Comments
- **`comment_id`**: Unique ID for each comment
- **`post_id`**: Indicates which *post* the *comment* belongs to. Acts as a foreign key to `posts/post_id`
- **`score`**: A numeric value to indicate the reach/engagement of a comment

