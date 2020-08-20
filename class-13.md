# Class 13 Reading Notes

## Local Storage
Local storage is how web pages store data locally. They do so using key value pairs stored in the browsers file system. These files won't go away when you close or leave the page. They do not follow you to a different machine or browser though. The key must be a string but the data is any javascript supported data type. Don't forget to parse your data when needed. Calling to set items with a key thats already named will overwrite the data. Calling get items with a key that doesnt exist will return null. Local storage is in array form and you can use square brackets when calling. To track changes to local storage trap the storage event. 

