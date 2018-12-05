# Accreditron-Releases
A public repo to publish our Accreditron releases notes to the marketing website

### How to use
Any releases you make or edit in the 'releases' feature of this repo will be automatically availible on the marketing website. You don't have to redeploy the website or anything - you just need to have write access to this repo. 


### How it works
Our releases page calls the github rest api, gets back some json, renders the markdown, and slaps it all in the dom just using Jquery. Don't rename this repo or the link will break.
