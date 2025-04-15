# Frameit

This is a simple social media platform built using Next.js. Users can post image content, like and comment on posts, follow/unfollow other users, and receive notifications. It is similar to Instagram in functionality.

## Tech Stack

- Next.js
- Clerk (User Authentication)
- PostgreSQL (via Neon)
- Prisma ORM
- shadcn/ui (UI Components)
- UploadThing (Image Uploads)

## Features

### Posts
- Users can upload and share image-based posts.
- Users can like and comment on posts.
- Posts are visible on the home feed and user profiles.

### Notifications
- Users receive notifications when someone follows them, likes their post, or comments.
- Notification bar displays the number of unread notifications.

### Profile
- Users can view their own profile including:
  - Their posts
  - Liked posts
  - Number of followers and following
- Users can update their profile info (name, bio, profile picture).
- When visiting other profiles:
  - View their posts and likes
  - Follow or unfollow them

## Screenshots

### - Home Page Without Login  
![Home Page Without Login](Screenshot/image.png)

### - Home Page with User Authorized  
![Home Page with Login](Screenshot/image-2.png)

### - Create Post  
![Create Post - Step 1](Screenshot/image-3.png)  
![Create Post - Step 2](Screenshot/image-4.png)

### - Notifications Page (Light Mode)  
![Notifications Page](Screenshot/image-8.png)

### - Profile Page  
![Profile Page - Posts](Screenshot/image-5.png)  
![Profile Page - Followers & Following](Screenshot/image-7.png)

### - Update Profile  
![Update Profile](Screenshot/image-6.png)
