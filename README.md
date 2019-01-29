# Indian-Names-for-Dialoglow
Indian Names for Dialogflow

# Indian Names not recognized by dialogflow
This is one of the common problem that we face when we want to personalize the Google Home app for our customers. It recognizes John but not Akash. Most indian names are recognized. 

# Solution
Create a new entity called username
<Img src="https://user-images.githubusercontent.com/1933684/51902279-9bcb9380-23df-11e9-8707-d1a74e208fd9.png" idth="400" height="400"/>

Switch to Raw Edit mode in the selected entity.
<Img src="https://user-images.githubusercontent.com/1933684/51902831-e568ae00-23e0-11e9-8302-cf62dc7226f9.png" idth="400" height="400"/>

Copy csv data from <b>10000 Indian Male Names for Dialogflow .csv </b> and paste it under the CSV tab and save it. 

I have added system provided names also in the list. This will cover whatever names that is there in the dialogflow database. 
"@sys.given-name:given-name ","@sys.given-name:given-name "
"@sys.given-name:last-name","@sys.given-name:last-name"
"@sys.given-name:first-name","@sys.given-name:first-name"
"@sys.last-name:last-name","@sys.last-name:last-name"
"@sys.first-name:first-name","@sys.first-name:first-name"
"@sys.last-name:first-name","@sys.last-name:first-name"

And do check the <b>Allow automated expansion</b>

