
---

### File Management

---

[<<<](https://github.com/ttltrk/ELSE/blob/master/SHELL/BUM/BUM.MD)

---

* <a href="#01">File Types</a>
* <a href="#02">Listing Files</a>
* <a href="#03">Metacharacters</a>
* <a href="#04">Hidden Files</a>
* <a href="#05">Creating Files</a>
* <a href="#06">Editing Files</a>
* <a href="#07">Display Content of a File</a>
* <a href="#08">Counting Words in a File</a>
* <a href="#09">Copying Files</a>
* <a href="#10">Renaming Files</a>
* <a href="#11">Deleting Files</a>
* <a href="#12">Standard Unix Streams</a>

---

<h3 id="01">File Types</h3>

|File Type|Description|
|------|------|
|Ordinary Files|An ordinary file is a file on the system that contains data, text, or program instructions. In this tutorial, you look at working with ordinary files.|
|Directories| Directories store both special and ordinary files. For users familiar with Windows or Mac OS, Unix directories are equivalent to folders.|
|Special Files|Some special files provide access to hardware such as hard drives, CD-ROM drives, modems, and Ethernet adapters. Other special files are similar to aliases or shortcuts and enable you to access a single file using different names.|

---

<h3 id="02">Listing Files</h3>

To list the files and directories stored in the current directory

```
ls
```

---

<h3 id="03">Metacharacters</h3>

```
ls *.doc
```

---

<h3 id="04">Hidden Files</h3>

Some common examples of the hidden files include the files

```
.profile − The Bourne shell ( sh) initialization script

.kshrc − The Korn shell ( ksh) initialization script

.cshrc − The C shell ( csh) initialization script

.rhosts − The remote shell configuration file
```

---

<h3 id="05">Creating Files</h3>

```
vi <filename>

blabla
```

---

<h3 id="06">Editing Files</h3>

```
vi <filename>
```

---

<h3 id="07">Display Content of a File</h3>

```
cat <filename>
```

You can display the line numbers by using the ```-b``` option along with the ```cat``` command

```
cat -b <filename>
```

---

<h3 id="08">Counting Words in a File</h3>

```
wc <filename>
```

```
wc <filename1> <filename2> <filename3>
```

---

<h3 id="09">Copying Files</h3>

```
cp <source_file> <destination_file>
```

---

<h3 id="10">Renaming Files</h3>

```
mv old_file new_file
```

```
mv filename newfile
```

---

<h3 id="11">Deleting Files</h3>

```
rm <filename>
```

```
rm <filename1> <filename2> <filename3>
```

---

<h3 id="12">Standard Unix Streams</h3>

|Stream|Description|
|---|---|
|stdin|This is referred to as the standard input and the associated file descriptor is 0. This is also represented as STDIN. The Unix program will read the default input from STDIN.|
|stdout|This is referred to as the standard output and the associated file descriptor is 1. This is also represented as STDOUT. The Unix program will write the default output at STDOUT|
|stderr|This is referred to as the standard error and the associated file descriptor is 2. This is also represented as STDERR. The Unix program will write all the error messages at STDERR.|

---

[src](https://www.tutorialspoint.com/unix/unix-file-management.htm)

---
