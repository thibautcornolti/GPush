# GPush

GPush allows to easily push a file to Google Drive and share its link.

## Usage

`gpush [-h] example.png`

GPush will upload `example.png` in a folder named `GPush` and will share to **anyone** with the link. The link is printed and copied in your clipboard.

## Example

```
$> gpush README.md 
https://drive.google.com/a/x/uc?id=xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx&export=download
Link copied!
```

## Requirements

Install the python3 dependencies:

`pip3 install -r requirements.txt`


### Google API access

Follow the instructions at https://developers.google.com/sheets/api/quickstart/python to setup credentials and API access.

You need to put the `client_secret.json` file in the `~/.gpush` folder.
