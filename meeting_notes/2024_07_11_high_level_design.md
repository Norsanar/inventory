# High level description
- helps the user keep track of the items they own
- keep track of where those items are (the location)
- know what box (another item) contains a particular item

# Features
## Required
- add item
## Future
- add temporary locations or boxes to an item
- know the usual storage location/box of the item
- notify user if an item has been in a temporary location/box for a TBD amount of time
- sync databases across multiple devices
- add items to database from csv or similar file (displays all items to be added in a list so the user can confirm that it was parsed correctly)

# Components
## Required
- web api
- web server
- database
## Future
- android phone application
- desktop application (Windows, Linux)
- SFTP (secure file transfer protocol) server

# API
## Required
- add an item (needs a name and location)
- put item inside another item (a box as an example)
- look at all items in a location (recursive on items)
- look at a list of all the locations
## Future
- search by name (of location) for location, returns a list of locations that match (sorting order?)
- search by name (of item) for item, returns a list of items that match (sorting order?)
- add sub locations (for rooms etc)
- look at all items in a particular item, a box (recursive)
- look at all items in a particular item, a box (non-recursive)
- look at all items in a location (non-recursive on items)
- add multiple locations and boxes and mark which ones is the actual location/box
- create tags for items
- search for items by tag
- add quantity for items
- add items to a set (if they go together, could be a tag I suppose)
- view all items in a particular item's set

# Application
- Technology: Spring Boot
- Kubernetes or Docker?
## Required
## Future

# Database
- Technology: PostgreSQL
## Required
- local server
## Future
- cloud server? (toggleable)

# Notes
- this application is intended for personal use
- what is the purpose of this application
- setup some JIRA issues, etc
- how is the user going to interact this software?
