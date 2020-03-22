<h1 align="center">Zane &amp; Sophie ©</h1>
<p align="center">Zane &amp; Sophie © : A wedding RSVP prototype using ejs as a templating tool</p>
<br>
<p align="center"><img src="https://github.com/christopherlye/snakeSnack/blob/master/images/github.io%20banner%20pic.png" alt="Zane &amp; Sophie ©" width="70%"></p>

---

## Inspiration

<p align="justify">In view of my upcoming wedding, I decided to work on something that could possibly help reduce the workload of the preparation. Even though there are many wedding RSVP websites out in the market, I thought it would be a good idea to work on it still, to go through the though-process of planning out how a wedding RSVP app should be.</p>

<p align="justify">Having picked up ejs as a templating tool for creating dynamic websites, I decided to use it for this project as well.</p>

<p align="justify">As you would have guessed, Zane and Sophie are fictional characters to simulate how my desired wedding RSVP app would look and feel like. Enjoy! 💍</p>

---

## Approach

In summary:

1. Wireframe the website
   - Sketched out how the entire website should look like
   - Determined the users of the website (e.g. myself, wedding guests)
   - Decided on how the user experience should be
2. Adopt an MVC approach
   - Model
     - attendees: the wedding guests
     - groups: the groups that the guests belong to (e.g. family, friends, relatives)
     - reminders: the messages to send out to the groups of guests regarding the wedding
     - users: the other users whom I would want to delegate access to so as to get help with the wedding (e.g. groomsmen, bridesmaids, family members)
   - View
     - attendees: list of attendees
     - groups: list of attendees in various groups
     - reminders: list of reminders to be sent out
     - rsvp: the guests who have already RSVP-ed
     - sessions: website sessions to restrict views
     - users: lists users of the website
3. Style the website
   - Determined kind of fonts. Chose font size
   - Font colours, placement, etc
   - CSS effects to enhance mood
4. Refactor my code abstract it using partials

---

## Installation

### Pre-requisites

- A working browser
- A laptop / tablet / desktop / mobile phone

### Steps

These are the installation steps if you would like to view the project locally:

<details>
<summary>Running Locally:</summary>

Step 1: Install npm dependencies

```
npm i
```

Step 2: Run mongod server in terminal

```
mongod
```

Step 3: Start nodemon

```
nodemon server.js
```

Step 4: Open up a browser tab and go to http://localhost:3300/

</details>

#

Viewing Online:

[Click to view!](http://zane-sophie.herokuapp.com/)

---

## Roadmap

### Ideas

- Style internal pages
- Add email confirmation in new user registration process
- Add email reminders functionality
- Add other parts of the one-page website (e.g. our story, schedule, getting there, questions)
- Add accordian for FAQ
- Integrate Google maps widget
- Add-to-calendar functionality for google

---

## TechStack

- HTML
- CSS
- JavaScript
- EJS
- expressJS
- dateformat
- bcrypt
- mongoDB
- mongoose

---

## Support

### Known Issues / Feedback

- Only links that currently work are the "RSVP Here" button and the "Login" button
- Internal pages are unstyled

---

## Authors

- Christopher Lye

---

## Acknowledgements

I would like to thank my instructors from General Assembly who have painstakingly taught us the concepts and introduced us new tools like EJS which help us keep code DRY.

---

## License

| S/N | License                                         |
| --- | ----------------------------------------------- |
| 1   | [MIT](https://choosealicense.com/licenses/mit/) |
