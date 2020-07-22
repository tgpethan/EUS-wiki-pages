acceptedTypes is a property that is an array.
It is an array that contains all of the file types your server accepts.

## Uses
The acceptedTypes array is used to limit the file types your server accepts on uploads.
It is also used to generate the list of files in the space API.

A sample array would be:
```json
[
    ".png",
    ".jpg",
    ".bmp"
]
```

If the array is left empty users attempting to upload files will always be met with an error as there are no accepted types of files.