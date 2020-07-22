uploadKey is a property that is a string.
It's a property that you can use to limit the people that can upload to your server if needed

## Uses
The uploadKey property is used when a user attempts to upload a file, it will compare the provided key with the key on the server.
If the uploadKey property is left as an empty string this will disable the check

For example the uploadKey on EUS is empty as it is a public server that has no limitations on who can upload to it.