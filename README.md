# Dirclean
Clean directories with ease. Quick Shell script to batch process files.

Move files from a directory to its individual recycle bin, undo actions and permanently delete files - all from the command line.
Place bash script in the directory to clean up.

### Delete Files 
Supply the extension of the files to recycle. 
```bash
sh dirclean.sh zip
```

### Undo Delete
```bash
sh dirclean.sh undo
```

### Permanently Delete Files/Empty Recycle Bin
```bash
sh dirclean.sh delete
```
### View Files in Recycle Bin
```bash
sh dirclean.sh peek
```
