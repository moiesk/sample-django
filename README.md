# Getting Started

This will guide through the steps to install the sail cli and pushing this repo to a new app

## Installing App Sail

To install the sail cli run in your Mac terminal:

    bash <(curl -s https://appsail.nyc3.digitaloceanspaces.com/install)

## Downloading the source code

To download the demo app run in your Mac or Linux terminal:

	git clone https://github.com/digitalocean-appsail/sample-django
	cd django-todoapp

## Deploying App

    sail push

It will ask for an auth key if you haven't used sail before. Retrieve it from [the auth page](https://cloud.digitalocean.com/appsail/auth).

Then it will ask how to configure the app.
Answer the questions as follows:

    ✓ Choose your configuration preference: Automatic...
    ✓ Django app detected, is this correct: Yes
    ✓ Use Python 3: Yes
    ✓ Do you need any background workers: No
    ✓ Do you need a database: Yes
    ✓ Database type: Postgres
    ✓ Add another database: No

After that, it will go through a deploy process. Once it's done, you can open the live app by following these steps:

	1. Go back to the auth page in your browser
	2. Click the 'Apps' link in the top left corner
	3. Select the app you just deployed
	4. Click the 'Live App' button in the top right part of the screen

# Author
This project was original created by [Kabir Baidhya](https://github.com/kabirbaidhya/django-todoapp).