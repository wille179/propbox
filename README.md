# PropBox
A web-based inventory management application for UAH using Google AppEngine and Cloud Platform.

*This is a fork from the development repository, which reflects the status of the delivered product.*

## Propbox 1.0
[Release Notes](Propbox_1.0_Release_Notes.pdf)

## Development Cycle Demo Videos
* [Demo 1](https://www.youtube.com/watch?v=WzrQXxxZmw4)
* [Demo 2](https://www.youtube.com/watch?v=05PVDm8bSlo)
* [Demo 3](https://www.youtube.com/watch?v=HzJdMjkLOuA)
* [Final Presentation](https://youtu.be/8uIj-iSuMgg?t=4s)

## Installation Instructions
These instructions are for anyone from the UAH theater department who wants to use uah-propbox.appspot.com.

1. Navigate to the [site](https://uah-propbox.appspot.com), no setup required.

## Developer Installation Instructions
These instructions are for someone who wants to help contribute to the propbox project.
[Developer Guide](https://docs.google.com/document/d/150tjfQCVWj44AUbpQ-3HOCYtCxwx4G8quTkFvtUQkTU/edit?usp=sharing)

## Files

| File Name           | Description                                   |
|---------------------|-----------------------------------------------|
| app.yaml            | yaml file for running the server.             |
| appengine_config.py | Python script for adding 3rd party imports.   |
| auth.py             | Script for user authentication.               |
| main.py             | Main handlers for web application.            |
| requirements.txt    | Server requirements.                          |
| utils.py 			  | Helpers for main.py 						  |
| warehouse_models.py | Framework for items stored in the database.   |

## Folders

| Folder Name    | Description                                             |
|----------------|---------------------------------------------------------|
| scripts/       | This folder contains scripts for use in various places. |
| stylesheets/   | This folder contains CSS files.                         |
| templates/     | This folder contains HTML templates.                    |
| static/        | This folder contains any static files that are not js,  |
|                | css, or jinja templates                                 
