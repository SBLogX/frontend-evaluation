### Context

You are working for a company which aims to provide better communication between doctors, and the first product of this company involves sending medical reports between practitioners.

This company already has a base API for many apps, built with the FHIR standard (https://www.hl7.org/fhir).

The final goal of this challenge is to build a small webapp connected to this backend, that will upload a document and give some reporting to the user.

There are 3 levels:
* Lvl 1: build a dropzone
* Lvl 2: send the file to a fake API
* Lvl 3: add some reporting information for the user

### General guidelines 

* You need to use React and Redux (Saga or Rematch), if you can, use Next Framework for SSR.
* The app should look ok. It should be usable (have a decent UX and UI).
* This app should be purely front-end - no backend !
* We should be able to launch the app easily ("npm run dev" is ok)

### Level 1

The goal is to create a small interface to drop a document.

* A drop zone should be present on the page
* When the user drop a document, the webpage should display the filename somewhere on the page

When you are done -> [Next Level](https://github.com/SBLogX/frontend-evaluation/tree/master/lvl2)
