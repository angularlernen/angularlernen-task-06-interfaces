Interfaces
==========

### Introduction

Let us focus on the _api_ module.

A typical _Single Page Application (SPA)_ represents the _client_ in a _distributed architecture_. To make an App complete we also have to provide some kind of an _API_. State of the art is to access a _RESTful API_ with _application/json_ as mime type.

First of all... let's give the exchanged data a _shape_ using _interfaces_.

### Preperation

1. Check, if you're able to access the mock database: 
https://angularlernen-task-06-interfaces-result.stackblitz.io/assets/microevents.json

2. Run `json-server https://angularlernen-task-06-interfaces-result.stackblitz.io/assets/microevents.json` in order to work with this remote db.

3. Alternatively - download the file to your local file system and run: `json-server --watch microevents.json`.

### Task

#### event.response.ts / EventResponse

1. Analyze the dataset for _events_: http://localhost:3000/events
2. Create a folder _event_ in the _api_ module.
3. Create an interface for a particular _event response object_: `ng g interface api/event/event-response`
4. If you like, rename the created _event-response.ts_ file into _event.response.ts_ in order to follow the Angular CLIs teams recommendation to introduce own sterotypes as part of the file name.

#### profile.response.ts / ProfileResponse

5. Analyze the dataset for _profiles_: http://localhost:3000/profiles
6. Create a folder _profile_ in the _api_ module.
7. Create an interface for a particular _profile response object_: `ng g interface api/profile/profile-response`
8. If you like, rename the created _profile-response.ts_ file into _profile.response.ts_ in order to follow the Angular CLIs teams recommendation to introduce own sterotypes as part of the file name.

### HOWTOs

Don't do this: http://json2ts.com/ ;-)
