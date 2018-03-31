# Fast Data Eraser
Fast secure wiper/remover for files & directories written in Python 2.x. Running on Unix-like OS only.
It use shredding (see shred(1)) with 35 passes (the last pass adding a final overwrite with zeros to hide shredding) for files and wiping empty directories with wipe (See wipe(1)).
Install wipe first.

```
$ chmod +x fast-data-eraser
```
Move fast-data-eraser to the directory 

## Usage 
```

$ fast-data-eraser [PATH TO THE FILE OR DIR]
```

## Requirements
* wipe

## More info
More info about shredding and wiping: shred(1), wipe(1)
