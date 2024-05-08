From the godot-cpp directory of the project, run the following command to build the project:
```bash
python -m SCons platform=windows custom_api_file=../extension_api.json
```
The `custom_api_file` argument is optional and can be used to specify a custom API file. If not specified, the default API file will be used.

Then move to the root directory of the project and run the following command to build the project:
```bash
python -m SCons platform=windows
```

We are here in the tutorial:
"We're going to assign the Godot logo to this node as our texture, disable the centered property:"