## Setup:
You will need to provide a API key in order for this workflow to function. This can be found/generated in Settings >
API & Integrations > Manage API Keys. Once you have this, paste it in the box on the left side of your screen. 

## Prerequisites:
- Alfred 5 with Powerpack
- JQ (If you don't have it, install with  `brew install jq`)

## Commands:
- `sncreate` Create a new card with the argument provided. The title is always "New card from Alfred", but this can be changed in the initial setup process, or at anytime by hitting the "Configure Workflow button" Useful for taking notes directly from Alfred
    - Example: `sncreate This is the body of a note` 
- `sndaily` Creates/appends your text as a to-do on a card with the date. Helpful for daily todo lists. 
    - Example: `sndaily go to the store` 
- `snsearch` Searches your cards for the text provided and shows the first card in a Alfred text view. Useful for finding cards without having to open Supernotes.
    - Example: `snsearch Supernotes Alfred workflow` (Did I mention I wrote this in Supernotes)
- `snclip` Sends your current clipboard contents to Supernotes as a new card. Similar to `sncreate` the title will always be "New Clip", but this can be changed in the initial setup, or by modifying the cURL.
- `snlink` Searches your notes, then creates a deeplink with the card. Helpful if you want to have a reference to a card in a different app. (For example, I use to reference cards in Things)

If anything breaks or you want to get in touch, open a issue and I'll take a look. Happy note taking!! 


