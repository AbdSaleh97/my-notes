# Reading Notes

This website serves as a platform for sharing and storing reading notes for various courses related to software development.

### Code 401 - Advanced Software Development
- 
# [Readings](Reading.md)
<!-- # [Mindset Prework](#mindset-prework) -->
# [sql practice](SQL.md)

- Relational databases are like organized collections of data stored in tables, where each table has rows and columns. These databases use relationships between tables to link related information together.

    SQL, or Structured Query Language, is a language used to communicate with these databases. It's like a universal tool that lets you ask questions about your data, add new information, update existing records, and remove data you no longer need. SQL makes it easier for humans to work with databases by providing a common language that works across different systems.

    So, in simple terms, relational databases help keep our data organized, and SQL is the language we use to talk to them and get the answers we need. 

## The Command Line

The command line is a text-based interface for interacting with a computer's operating system. It allows users to issue commands to the computer by typing text commands rather than using a graphical interface. The command line provides direct access to the system, enabling users to perform various tasks such as file manipulation, software installation, and system configuration.

### How it Works:

When a command is entered in the command line interface, it is interpreted by the shell, which is a program that acts as an intermediary between the user and the operating system. The shell parses the command, identifies the executable program associated with it, and then executes the program with any specified options and arguments. After execution, the output of the command is displayed in the terminal window.

### Getting started:

To access the command line on Windows, open Command Prompt or PowerShell from the Start menu or by using keyboard shortcuts like Win + R and typing "cmd" or "powershell".

# Linux File System Navigation

## File System Hierarchy

Linux organizes files in a hierarchical structure starting from the root directory (/). Key directories include:

- /bin: Binary files
- /etc: System configuration files
- /home: User directories
- /var: Variable data

### Current Directory

You can check your current directory using the pwd command.

### List Contents

Use ls to list the contents of a directory. Options like -l provide detailed information such as permissions, owner, size, and modification time.

### Change Directory

Move to a different directory using cd. Typing cd without arguments takes you to your home directory.

### Relative and Absolute Paths

Paths can be relative (specified from your current directory) or absolute (specified from the root directory). Use . to represent the current directory and .. to represent the parent directory.

### Path Completion

Pressing the Tab key can help complete directory and file names, saving time and reducing typing errors.


## Manual Pages:
  Manual pages, commonly referred to as man pages, are a comprehensive set of documentation in Unix-like operating systems that provide detailed information about various commands, utilities, functions, and file formats. They serve as a vital resource for users to understand the usage and functionality of commands available in the command-line interface.

- **Main Commands Used in the Demo:**
  1. `man <command>`: Displays the manual page for the specified command, providing detailed information on its usage and options.
  2. `man -k <search term>`: Performs a keyword search across all manual pages to find commands related to the specified search term.
  3. `/<term>`: Within a manual page, performs a search for the specified term, allowing users to quickly locate relevant information within the page.

- **Summary:**
  Manual pages, or man pages, are comprehensive documentation in Unix-like systems providing detailed information about commands, utilities, and functions. Users can access manual pages using the `man` command to view documentation for specific commands or perform keyword searches using `man -k`. The ability to search within manual pages using `/` followed by a term enhances usability, enabling users to quickly find relevant information.


  # Linux Features

## Linux is an Extensionless System
- Linux ignores file extensions to determine file types.
- Unlike Windows, where extensions are crucial for file identification.
- Use the `file` command to identify file types regardless of their extensions.

## Linux is Case Sensitive
- Linux distinguishes between uppercase and lowercase letters in filenames.
- This is different from systems like Windows, which are case-insensitive.
- Pay attention to letter casing when using commands and referring to files.

## Spaces in Names
- Spaces in file and directory names can cause issues on the command line.
- Use quotes or escape characters (`\`) to handle names with spaces.
  - Example using quotes: `cd 'Holiday Photos'`
  - Example using escape character: `cd Holiday\ Photos`

## Hidden Files and Directories
- Files or directories starting with a dot (`.`) are considered hidden in Linux.
- Commonly used for configuration files or to prevent cluttering in directory listings.
- Use `ls -a` to list all files, including hidden ones.

# Basic File and Directory Operations in Linux

## Making a Directory
- Use `mkdir` to create directories and organize files hierarchically.
- Understand relative and absolute paths for directory creation.

## Removing a Directory
- Use `rmdir` to remove empty directories.

## Creating a Blank File
- The `touch` command creates empty files.
- It's also used to modify file access and modification times.

## Copying a File or Directory
- Duplicate files or directories with the `cp` command.
- Use `-r` for recursive copying of directories.

## Moving a File or Directory
- The `mv` command moves files or directories.
- Renaming is accomplished by moving to the same directory with a different name.

## Removing a File (and non-empty Directories)
- The `rm` command deletes files and directories.
- Use `-r` for recursive removal of non-empty directories.


## Mindset Prework
<div id="mindset-prework"></div>

**Why This Topic Matters:**

- In this technology course, mindset matters as much as technical skills. Our ability to handle challenges and workload hinges on our mindset. Prework like reading about deliberate practice and watching videos on growth mindset, grit, and success redefines our approach. Assessing emotional intelligence and biases enhances self-awareness, crucial for navigating the tech landscape. By focusing on mindset, we're equipping ourselves to tackle the course material with resilience and adaptability, ensuring success in this module and beyond.

**1. Upgrade Your Technical Skills with Deliberate Practice:**
- Deliberate practice is a methodical approach to skill enhancement that involves breaking down complex tasks, focusing on improvement areas, and pushing beyond one's comfort zone. Its application in technology can lead to more effective learning and mastery of technical concepts and tools.

**2. Carol Dweck on the Growth Mindset :**
- Carol Dweck's concept of the growth mindset, emphasizing the belief that abilities can be developed through dedication and effort, is particularly relevant in the tech industry. Cultivating a growth mindset fosters resilience, adaptability, and a willingness to embrace challenges and learn from failures.

**3. Angela Lee Duckworth on Grit :**
- Angela Lee Duckworth's notion of grit, defined as passion and perseverance towards long-term goals, resonates deeply in the tech world where innovation often requires sustained effort and resilience in the face of setbacks. Grit enables individuals to persist through challenges and setbacks, ultimately leading to greater success.

**4. Alain de Botton on Redefining Success :**
- Alain de Botton's perspective on redefining success away from conventional metrics towards personal fulfillment and well-being is crucial in an industry often driven by external markers of achievement. By prioritizing intrinsic motivation, meaningful work, and work-life balance, individuals can find greater satisfaction and purpose in their tech careers.

**Emotional Intelligence Assessment:**
- Assessing emotional intelligence is essential in the tech industry, where collaboration, communication, and interpersonal dynamics play crucial roles in project success. Strengthening emotional intelligence skills such as self-awareness, empathy, and conflict resolution can enhance teamwork and leadership effectiveness.

**Bias Assessment:**
- Addressing biases is critical in the tech field to promote diversity, inclusion, and fairness. Recognizing and mitigating unconscious biases can lead to more equitable hiring practices, unbiased decision-making, and a more inclusive work environment, fostering creativity and innovation.

**Things I Want to Know More About:**
- How can deliberate practice be tailored to specific technical roles within the tech industry, such as software development or data science?
- What strategies can tech leaders employ to foster a growth mindset and grit among their teams, particularly in high-pressure environments?
- How does emotional intelligence impact remote work and virtual collaboration in the tech sector?
- What initiatives have been successful in addressing unconscious biases and promoting diversity in tech companies, and how can they be implemented more widely?

---

*Note: The above notes were adapted to fit the context of the technology industry and its unique challenges and opportunities.*


### In what ways can organizations cultivate a culture of empathy and inclusion to address biases and promote diversity effectively?

### What strategies can leaders implement to create a workplace environment where individuals feel empowered to challenge biases, engage in open dialogue, and contribute to a culture of diversity and inclusion?
