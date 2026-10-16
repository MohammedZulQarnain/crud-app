# Posts Manager

A simple Ruby on Rails application for managing blog posts.

## What this project does

Posts Manager is a small CRUD app that lets users:

- create a new post
- view all posts
- open a single post's details
- edit an existing post
- delete a post

The app uses a `Post` model with a title and description, and the homepage displays the list of posts so users can quickly manage content.

## Project purpose

This project is designed to demonstrate a basic Rails workflow for content management, including:

- MVC structure in Rails
- database-backed records
- form handling and validation-friendly controller actions
- route setup for standard CRUD operations
- simple front-end views for listing and editing data

## Tech stack

- Ruby 3.0
- Rails 6.0
- Node 14
- SQLite (default Rails database setup for this project)

## App structure

- `app/controllers/posts_controller.rb` handles create, read, update, and delete actions
- `app/models/post.rb` defines the Post record
- `app/views/posts/` contains the UI for listing, showing, and editing posts
- `config/routes.rb` sets up the routes for the posts resource

## Getting started

1. Install the required Ruby and Node versions.
2. Install dependencies:

   ```bash
   bundle install
   yarn install
   ```

3. Set up the database:

   ```bash
   rails db:create
   rails db:migrate
   ```

4. Start the app:

   ```bash
   rails server
   ```

5. Open the app in your browser at:

   ```text
   http://localhost:3000
   ```

## Default behavior

- The root page shows all posts.
- Clicking "Create Post" takes you to the form for adding a new record.
- Each post can be viewed, edited, or removed from the list.

## Notes

This is a lightweight project intended for learning and practicing Rails CRUD features in a simple, easy-to-follow application.