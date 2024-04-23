# Google Cloud Function

## Starting a project
To start a new project in Google Cloud, we can go to the
[Firebase Console](https://console.firebase.google.com) or
create it from [Google Cloud Platform Console](https://console.cloud.google.com).

## Creating a virtual environment
First we have to install `python3-venv` with:
```
brew install virtualenv
```
Then, we create the virtual environment:

```
virtualenv venv -p python3
```

To activate the virtual environment:
```
source venv/bin/activate
```

Then, we can add dependencies (packages) by putting them
in a `requirements.txt` file and we then install them with:
```
pip install -r requirements.txt
```

## Running locally

Run the command:
```
functions-framework --target hello_world
```

Request example:
```
http://localhost:8080/?name=Filipe&lastname=Medeiros
```