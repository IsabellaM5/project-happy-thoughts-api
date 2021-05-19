# Project Happy Thoughts API 💌

Replace this readme with your own information about your project.

Start by briefly describing the assignment in a sentence or two. Keep it short and to the point.

## The problem

Describe how you approached to problem, and what tools and techniques you used to solve it. How did you plan? What technologies did you use? If you had more time, what would be next?

I chose to use the npm package express-list-endpoints to list the endpoints in the home endpoint. I continuously tested my API using Postman and checked out my database using MongoDB Compass. 


## View it live

Link to my deployed API: https://project-happy-thoughts-isabm5.herokuapp.com/ 


## Documentation

### ENDPOINTS

Displays all endpoints for this API using npm package express-list-endpoints.
- ```GET /```


### THOUGHTS

Endpoint for several thoughts.
- ```GET /thoughts```
- ```POST /thoughts```


### SINGLE THOUGHT

Endpoint for a single thought.
- ```GET /thoughts/:thoughtId```
- ```DELETE /thoughts/:thoughtId```
- ```PATCH /thoughts/:thoughtId```
- ```PUT /thoughts/:thoughtId```

Endpoint for a single thought to POST a like on a specific thought.

- ```POST /thoughts/:thoughtId/like```