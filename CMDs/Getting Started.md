# Getting Started

If you're new to the Command Prompt (cmd) on Windows, this section will help you get started with the basics.

## **Opening the Command Prompt**

To open the Command Prompt:

1. Press **`Win + R`** to open the Run dialog.
2. Type **`cmd`** and press **`Enter`**.

Alternatively, you can search for "Command Prompt" in the Start menu.

## **Navigating the File System**

### **List Files and Directories (dir)**

To list the contents of the current directory:

```bash
dir
```

Here you can see the list of files and folders in my current directory

![Untitled](Getting%20Started%20215e098796eb428db352337c6cdb72fe/Untitled.png)

### **Change Directory (cd)**

Use the **`cd`** command to change the current working directory:

```bash
cd name-of-the-directory-you-want-to-go
```

Here you can see I am going to the folder name

![Untitled](Getting%20Started%20215e098796eb428db352337c6cdb72fe/Untitled%201.png)

### **Changing Drives**

If you have multiple drives, switch between them using the drive letter:

```bash
D:
```

Here you can see first I am going to D drive and then E drive

![Untitled](Getting%20Started%20215e098796eb428db352337c6cdb72fe/Untitled%202.png)

## **File Manipulation**

In the Windows Command Prompt, you can use the **`echo`** command to create a new file and the **`mkdir`** command to create a new folder. Here's how you can do it:

### **Creating a New File:**

You can use the **`echo`** command to create a new text file. For example, to create a file named **`example.txt`**, you can use the following command:

```bash
echo. > example.txt
```

![Untitled](Getting%20Started%20215e098796eb428db352337c6cdb72fe/Untitled%203.png)

This command uses the **`echo`** command with an empty string (**`echo.`**) and redirects the output to a file (**`>`**). The result is an empty text file named **`example.txt`**.

If you want to create a file with some content, you can do the following:

```bash
echo This is the content of the file > example.txt
```

This command will create a file named **`example.txt`** with the specified content.

![Untitled](Getting%20Started%20215e098796eb428db352337c6cdb72fe/Untitled%204.png)

### **Creating a New Folder:**

To create a new folder, you can use the **`mkdir`** command. For example, to create a folder named **`NewFolder`**, use the following command:

```bash
mkdir NewFolder
```

This command will create a new folder named **`NewFolder`** in the current working directory.

![Untitled](Getting%20Started%20215e098796eb428db352337c6cdb72fe/Untitled%205.png)

### **Creating Nested Folders:**

If you want to create a folder within another folder, you can specify the full path or use the **`cd`** (change directory) command to navigate to the desired location. For example:

```bash
mkdir ParentFolder
cd ParentFolder
mkdir ChildFolder
```

This sequence of commands creates a folder named **`ParentFolder`**, navigates into that folder, and then creates a folder named **`ChildFolder`** within it.

Remember to replace file and folder names with your desired names. Additionally, be cautious when using commands like **`mkdir`** to avoid unintentional overwriting or deletion of files and folders.

### **Copying Files (copy)**

To copy a file to another location:

```bash
copy sourcefile-name destination
```

Here is a text file in my desktop folder of C drive, I want to copy that to the world folder.

![Untitled](Getting%20Started%20215e098796eb428db352337c6cdb72fe/Untitled%206.png)

Here is how I did that

![copy file.png](Getting%20Started%20215e098796eb428db352337c6cdb72fe/copy_file.png)

### **Moving/Renaming Files (move)**

To move or rename a file:

```bash
move sourcefile destination
```

### **Deleting Files (del)**

To delete a file:

```bash
del filename
```

## **System Information**

### **System Information (systeminfo)**

To view detailed information about your system:

```bash
systeminfo
```

### **Running Processes (tasklist)**

To see a list of running processes:

```bash
tasklist
```

## **Networking**

### **IP Configuration (IP Config)**

To display the IP configuration for all network interfaces:

```bash
ipconfig
```

### **Ping (ping)**

To test network connectivity to a specific address:

```bash
ping destination
```

![Untitled](Getting%20Started%20215e098796eb428db352337c6cdb72fe/Untitled%207.png)

These are just a few basic commands to get you started. Explore the repository to find more advanced commands and techniques!