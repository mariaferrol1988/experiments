# 

## Table of contents md

## Working with .tar files 

### Checking content
```bash
tar -tf filename.tar.gz
```

### Extracting the content 
```bash
tar -xf archive.tar
tar -xvf archive.tar # showing the name of the file extracted 
tar -xf archive.tar file1 file2 # extracting files
```

### Giving permissions 
```bash
chmod 777 /path/to/directory 
chmod 644 /path/to/directory # the owner of the file has read and write access, while the group members and other users on the system only have read access
```



## Sources
* working with tar files: <br/>
http://linuxize.com/post/how-to-create-and-extract-archives-using-the-tar-command-in-linux/#:~:text=To%20create%20a%20tar%20archive,the%20name%20of%20the%20archive.&text=You%20can%20create%20archives%20from,no-recursion%20option%20is%20specified. <br/>


