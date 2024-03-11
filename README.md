# Quick Media Share
A simple Rust program that allow sharing files via http without setup 

## Usage (WIP)
Host files in current directory
```
qms
```

### TODO:
Host files in any directory
```
qms --root path/to/root
```

Specify password for access
```
qms --password somepassword
```

## Plans
- support range request for media streaming
- command line args
- proper ui using svelte
- file upload support

### maybe
- support for different uis
- multiple users and profiles
- automatic preview files
- config file