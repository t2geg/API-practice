This Repo contains some APIs for practice purpose.  
  
Following are the APIs:  
  
1. Authentication & Authorization (JWT + Roles)  
Build an API with user authentication using JWT.  
Implement role-based access control (RBAC), where different roles (e.g., Admin, User, Moderator) have different permissions to access certain routes.  
Example: Admins can create, read, update, and delete users, while normal users can only update their profiles.  
  
  
2. Rate Limiting  
Create an API that allows rate limiting for specific routes.  
Example: Implement a rate limit of 100 requests per minute for user endpoints, but allow admins to have a higher limit.  
  
  
3. File Upload with Validation  
Create an API endpoint that allows users to upload images or files.  
Add file validation (e.g., only allow certain file types, limit file size, and image resolution).  
Store the files on a cloud storage service like AWS S3 or locally with proper security.  
  
  
4. Search & Filtering with Pagination  
Create an API that provides advanced search functionality for a database of items.  
Include filtering (e.g., by category, date range, price), sorting, and pagination.  
Example: Search through a collection of products where users can filter by price, category, and rating, and sort by popularity.  
  
  
5. WebSocket Integration  
Implement WebSocket with the MERN stack to create a real-time feature like a chat app.  
Have the chat API send and receive messages in real time between users.  
Add message persistence in the database (e.g., MongoDB).  
  
  
6. Complex Data Relationships (One-to-Many, Many-to-Many)  
Create an API that handles complex data relationships, such as a social media app.  
Example: Design an API where users can follow/unfollow other users and like/dislike posts.  
Also, implement a feed where users see posts only from those they follow.  
  
  
7. Event-Based System with RabbitMQ or Kafka  
Implement a microservice architecture with MERN and integrate an event-based system like RabbitMQ or Kafka.  
Example: When a user makes a purchase, trigger events that update inventory, send confirmation emails, and update the user’s order history.  
  
  
8. GraphQL API  
Create a GraphQL API alongside a REST API.  
Implement schema stitching for a larger application with multiple data sources, where the user can make more flexible queries compared to REST.  
  
  
9. API Rate Monitoring and Analytics  
Build an API that logs and monitors its usage.  
Example: Implement functionality to track API call statistics (number of requests, response times, error rates) and store them in a separate MongoDB collection.  
Build an endpoint that retrieves and displays the statistics, useful for debugging and analytics.  
  
  
10. Building a Payment Gateway Integration  
Create an API that integrates with a third-party payment gateway like Stripe or PayPal.  
Implement secure payment processing, store transaction details, and allow users to view their transaction history.  
