# blah blah blah #

## Setup ##

In the root of the project, create a venv folder with:
```console
python -m venv venv
```
then activate the environment:<br>
(Windows)
```console
venv/Scripts/activate
```
(macOS)
```console
. source venv/bin/activate
```
then install Flask:
```console
pip install Flask
```
To initialize the database:
```console
flask --app rhs_events init-db
```
To test:
```console
flask --app rhs_events --debug run
```
