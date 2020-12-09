# Rails Notes coding challenge

**Rails Notes coding challenge** is a coding challenge for Rails developers applying for a job at Janan co. .

## Scenario
So here you are! You decided to apply for a job at Janan and now we are asking you to help us create a Notes App in Rails.

The app should have basic authentication with email and password.
You don't have to store any other information about the user.
Every user can sign up and create notes.
A note has a **title** and a **body**.

The user should be able to see a list of his notes, create new notes and should be able to edit them.

He should be able to collaborate with his friends and edit his notes with them through a link (like in Google Docs).
The user has to see the live updates, however not necessarily the cursors or any other thing. Only the text should change.

Bonus: Add two types of links (view only, view and edit)
Only editing is mandatory.

You don't have to spend a lot of time on styling.
An input field for the title and a text field for the body are enough for the note.
The body should be plain text without markup. (bold, italic etc. are not necessary)

The focus here is on your backend skills.

## Technical specifications
Ruby version: 2.7.0
Rails version: '>= 6.0.0'

## Mission
- [ ] Generate a rails app
- [ ] Copy this README.md to your app
- [ ] add user authentication to your app
- [ ] Create CRUD for the notes
- [ ] Add collaboration feature
- [ ] Add a guide in this readme under Project Setup on how to run your project. Also add which database you used.
- [ ] Push your code to Github
- [ ] Submit your git repository to hossameldin.khalifa@rwth-aachen.de

## Bonus
- [ ] Add view only option to collaboration link (the user can't edit however see view the note)
- [ ] Add the email of users collaborating on the note now with the current user
- [ ] Add text search to the app which searches in all notes


## Please note
- Pay attention to your code style and structure
- Don't pay special attention for design and styling (the functionality is enough)
- Please commit your changes often and write good and precise commit messages

## Feel free to
- Use whatever frontend you like (erb,haml or frontend frameworks) or even split backend and frontend


## Project setup
```
bundle install
rake notes:fresh
rails s
```

## Database used
postgres
...

