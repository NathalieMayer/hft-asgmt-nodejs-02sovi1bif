![GitHub Classroom Workflow](https://github.com/hft-stuttgart-ipr/hft-asgmt-nodejs-NathalieMayer/workflows/GitHub%20Classroom%20Workflow/badge.svg)

# hft-asgmt-nodejs

## TODO

- [X] Install and use the `sqlite3` package
- [x] Use names for your form fields: `username` for the username and `message` for the textarea
- [x] parse json via express.json() GOOGLE IT!
- [X] Iterate over all items in your database and show them in your table
- [X] Refactor the `GET /` route to deliver your index page with data from the database
- [x] Create a route, for `POST /add-entry` to receive form data

## Hints

- It is not necessary to store the ID in the Database! `username` and `message` is enough! This is because of the sqlite autoincrement feature, which automatically increases the ID + 1
- [https://www.npmjs.com/package/body-parser](https://www.npmjs.com/package/body-parser) -> Check examples for how to use bodyParser for json
