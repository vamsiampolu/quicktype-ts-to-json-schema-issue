### Repo for [ISSUE 2695](https://github.com/glideapps/quicktype/issues/2695)

When I generate json schema from typescript types, I see an error where `"type": "{string}"` appears
instead of `"type": "string"`. I guess `quicktype` may be reading `JSDoc` and writing the `@type` 
annotation directly.
