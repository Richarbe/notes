# Notes

### Entry Template


__command__ - _Description_

__Examples:__

```
bash code in here
```
---

## File Management

__mv__ - _Move file or Rename file_

__Examples:__

```
mv sourceFile destinationFile
mv sourceFile destinationLocation
mv myFile.txt myFolder/
```
---

__cp__ - _Copy file or folder_

__Examples:__

```
cp filename.cpp myCopy.cpp
cp -r myFolder/ myNewFolder
```
---

__rm__ - _Remove file or folder_

__Examples:__
```
rm filename.cpp
rm -r myfolder/
```
---

__rmdir__ - _Remove directory_

__Examples:__
```
rmdir myfolder/
```
---

__ln -s__ - _Creates alias for a given file_

__Examples:__
```
ln -s file.txt file2.txt
```
---

__scp__ - _Secure copy (remote file copy on a network)_

__Examples:__
```
scp file.txt USERNAME@host:directory/newfile.txt
scp USERNAME@host:directory/file.txt ~/destination/newfile.txt
```
---

__pwd__ - _Print working (current) directory_

__Examples:__
```
pwd
```
---

__ls__ - _List directory contents_

__Examples:__
```
ls
ls startofword*
ls *end.txt
```
---

__tar__ - _Create Tape ARchives and add or extract files_

__Examples:__
```
tar -cvwf tarfile.tar myfile.tar   
tar -cvwf tarfile.tar mydirectory/ #puts directory into tar file
tar -xvwf tarfile.tar              #extracts into currect directory


## File Transfer

__curl__ - _Displays URL_

__Examples:__
```
curl http://www.wikipedia.org

* wget
* scp
* rsync

## Pipe tools

* cat
* sort
* uniq
* grep
