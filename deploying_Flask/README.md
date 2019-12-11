# Deploying Pytorch with Flask API

### How to use
* Run the Flask server:
```sh
FLASK_ENV=development FLASK_APP=app.py flask run
```
* From the another tab of terminal, send the image file via HTTP POST request:
```sh
curl -X POST -F file=@<path_to_image> http://localhost:5000/predict
```