ask-allie
=========

A simple webapp for Allie to manage studio requests.

Also a place for Ruthie to experiment with the following:

* backbone.js
* state.js
* jasmine
* sinon.js

## Design

See sketches. I like the idea of something skeumorphic,
literal 'inbox' and 'outbox', but first pass will be
boxes-on-a-page. Let's discuss.

## Roadmap

v0.1: Stand up the backbone app, a la a Todo app.
v0.2: Adds ability to see all Outstanding and Completed requests.
v0.3: Adds ability to create a new request.
v0.4: Adds ability to mark a request as Completed.
v0.5: Adds ability to edit arbitrary parts of existing requests.
v0.6: Adds ability to upload and attach files to requests.
v0.7: Multiple users - logins, authentication.
v0.8: Polish design and feel of app.
v0.9: Bundle as Chrome extension; alpha release.
v1.0: Beta release.
v1.1: Stable release.

## Architecture

#### Models 

* User
* Request

#### Views

* All Requests
* Single Request Details
* Request Form

tbd: partials in backbone?

#### Controllers

tbd: not sure how this concept works in backboneland.

#### State

* Data state
* UI state
