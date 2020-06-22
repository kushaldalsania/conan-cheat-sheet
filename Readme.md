### Clear local cache
```
conan remove "*" -f
```

### List all package in local cache
```
conan search
```

### Search package recipes
```
conan search poco/* -r=conan-center
```
Remove `-r` option to search locally

### Search package binaries
```

```

### List all profiles
```
conan profile list
```

### Show profile
```
conan profile show default
```

### Update profile
```
conan profile update settings.compiler=gcc default
```
Here compiler value (under settings section) of default profile is updated to `gcc`. If value has space (like `Visual Studio`), quote value with `inverted commas ""`. 
