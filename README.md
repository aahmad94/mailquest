# MailQuest

A quick and easy platform that allows a user to send batch questionnaires and aggregate responses, built with Node/Express, MongoDB, React, and Redux.

## Features

1. OAuth
2. Stripe Payments API
3. User Questionnare Form w/ Email Addresses
4. Dispatch Emails w/ Questionnare Link
5. Tabulate Feedback for User

### OAuth Flow

Passport.js is utilized alongside the Google Passport Strategy to allow a client to login through a server request to Google to grant permission via an application ID -- the Google redirect URL to obtain user details and set record in database to set user ID in cookie for this user (logged in, cookie sent with all future domain requests).