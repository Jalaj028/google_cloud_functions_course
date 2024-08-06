# Google cloud functions course
## Starting a project
TO start a new project in the Google cloud, we can go to the
[Firebase Console](https://console.firebase.google.com) or create it from [Google Cloud Platform Console](https://console.cloud.google.com)

## Creating a Virtual Environment (so that we have an independent version of python for every project)
First we have to install 'python3-venv' with the following command
```
sudo apt install python3-venv 
```
then we execute the following command
```
python3 -m venv venv

```
then activate the virtual environment
```
source venv/bin/activate
```

now to add new packages to our new virtual environment we create a file called `requirements.txt` and execute the following command:
```
pip install -r requirements.txt
```