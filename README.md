# Whatsapp Greetings

Sending Personalised messages to all of your contacts leave an impact on the receiver. He/She thinks you considered them important to personally type in the message and not forward just like others.

Here is your chance to Automatically send Personalised messages :)

## Gather Contacts

1) Open [Google Contacts](https://contacts.google.com "G contacts") webpage and export your contacts.
2) Ensure to keep this csv as "google.csv" and keep it in the same folder.

## Install libraries

1) Selenium : `pip install selenium `
2) Pandas : `pip install pandas`

## Chrome Driver

1) Install the latest version of Chrome Driver:http://chromedriver.chromium.org/downloads
2) Set up the path of Chrome Driver in line 8 of send_greetings.py

## Running the code

`python send_greetings.py`

1) This will start execution of filter contacts.
2) To add a contact to your list
    1. Enter the Personalised name with which you want to send the message
    2. To ignore the contact, press enter
    3. To use the given name, the one after -, press f and enter
    4. to break through the list, Press f and enter.
