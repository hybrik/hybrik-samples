# Hybrik Cloud-based media handling
## Sample JSON files

Each of these JSON files, when run in the Hybrik environment, will create one or more output files or reports. Output files have been validated by importing them and playing them back in a variety of tools, players, video editors, etc.

To use these files, make sure you edit the "source" and "destination_path" parameters in the beginning of the file to point to your own source files and destination output folders:


```
"definitions": {
        "profile_name": "<some name here>",
        "source": "s3://hybrik-examples/public/sources/tears_of_steel_720p.mov",
        "destination_path": "s3://hybrik-examples/public/output/<output folder names>/{{profile_name}}"
		...<possibly more definitions here>...
},

```
