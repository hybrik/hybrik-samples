# Hybrik Cloud-based media handling
## Sample JSON files

Each of these JSON files, when run in the Hybrik environment, will create one or more output files. Output files have been validated by importing them and playing them back in a variety of tools, players, video editors, etc.

To use these files, make sure you edit the "source_filename", "source_path", and "destination_basepath" parameters in the beginning of the file to point to your own source files and destination output folders:


```
"definitions": {
		...
		"source_filename": "tears_of_steel_720p.mov",
		...

		"source_path": "s3://hybrik-examples/public/sources",
		"destination_basepath": "s3://hybrik-examples/public/output",
		...
},
```