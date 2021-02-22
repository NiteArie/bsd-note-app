# bsd-note-app (Note App)

## Design

Adobe XD: [https://xd.adobe.com/view/51ec9939-5713-4c13-8580-98d88e91a014-04bf/](https://xd.adobe.com/view/51ec9939-5713-4c13-8580-98d88e91a014-04bf/)

## Requirement

* The application looks similar to the design and is available for users through a link.
* Users can both search and filter notes.
* Users can add new notes.
* When adding a new note, users can fill title, description, and category. The date should be created under the hood using the current time.
* Users can see created, colored notes sorted by date as well as an empty UI with illustration when there are no notes or couldn't be found.
* Users can see how many notes are completed including the visual progression indicator.
* Users can mark notes as complete, edit, and delete them.
* When completing notes, they should have strikethrough text and become grayed out. Also, they should be moved into the end.
* When editing notes, the date of note should also be updated altogether with other fields.
* When deleting notes confirmation should pop up.

## Additional Requirement

* Save and read notes, e.g localStorage
* Add unit tests to code, e.g Jest
* Add e2e tests to code, e.g cypress