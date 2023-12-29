## Topics

1. Terminal Emulator
2. What is Shell
3. List commands
4. ls
5. mkdir
6. cd
7. Environment Variables
8. Path Environment Variable
9. Bash files
10. zprofile
11. Where are Environment Variables stored?
12. pwd
13. ls
14. cd
15. ls -R
16. man
17. tr
18. mkdir
19. touch
20. cp
21. mv
22. rm
23. cp -R
24. Renaming a file
25. Deleting a directory
26. sudo
27. df
28. head
29. tail
30. diff
31. locate
32. find
33. File Permissions
34. Changing file permissions
35. chown
36. Performing an action on multiple files
37. grep
38. history
39. regex
40. regex commands
41. alias command
42. Terminal shortcuts
43. wget
44. top
45. uname
46. zip
47. unzip
48. hostname
49. useradd
50. userdel
51. Operating system commands
52. uname
53. Operating system information
54. lscpu
55. free
56. vmstat
57. id
58. getent
59. id User
60. lsof
61. Networking commands
62. nslookup
63. netstat
64. sed
65. cut
66. htop
67. ps aux
68. Working with operators

```

🖥️ The video focuses on practical aspects, covering how to use the terminal and work with modifications of terminals, emphasizing their importance in a DevOps boot camp.
📜 Shell scripting (bash scripting) is mentioned as a more advanced topic to be covered later in the DevOps boot camp, along with concepts related to Linux infrastructure and file structure.
🚀 Future videos will cover YAML, Docker, and Kubernetes, with comprehensive courses planned for Docker and Kubernetes.
🌐 Explanation of terminal emulators, shells, and the command prompt, highlighting their role in controlling the operating system and executing commands.
🔍 Environment variables, particularly the PATH variable, are discussed as a mechanism for the system to locate executable files, influencing how commands are executed.
🖥️ Using special characters in PS1 allows customization of the terminal prompt in Linux.
📁 Configuration files like .zprofile and .bashrc are used for setting environment variables in Linux.
🌐 Environment variables set in files like .zprofile are not permanent; they are valid only for the current session.
📂 Basic commands like pwd (print working directory) and ls (list files) are fundamental for navigating and understanding the file system.
🔄 Using pipes (|) in Linux allows redirecting the output of one command as input to another, enabling powerful command chaining.
📂 cp command copies files and directories. Use -r to copy entire subtrees. Use mv to move files or directories, and rm to delete them. Add -f to force deletion.
🛡️ sudo allows executing commands as a superuser/administrator, requiring administrative permissions. It's useful for tasks that regular users can't perform.
💽 df command displays disk space usage on volumes. Use df -m for megabytes and df -h for human-readable format. It helps monitor available disk space.
🗃️ du command shows disk usage statistics for files and directories. Use du -h for human-readable format. It's useful for identifying space usage.
👀 head and tail commands display the first and last lines of a file, respectively. Use them to previewcontent quickly.
🧐 Use grep to search for a specific word in a file. Add -w for a complete word match and -i for case-insensitivity.
📝 Find line numbers of matches using grep. Combine tags like -n, -w, and -i for more specific searches.
🔄 Use grep recursively with -r to search for a pattern in all files in a directory. Use -l to list files containing the pattern.
🧮 Count occurrences of a pattern using grep with -c. Pipe (|) output to other commands for more complex searches.
🎭 Use regular expressions (grep -P) for advanced pattern matching, such as finding emails or phone numbers. Set up aliases for commonly used commands.
🖥️ Learn how to check free and used memory in Linux using the free command.
🆔 Use the id command to check user and group IDs in Linux.
📂 List all open files in the system with the lsof command.
🌐 Perform DNS lookup using the nslookup command in Linux.
⚙️ Understand the use of operators, such as &&, ||, ;, |, and !, to combine and control the execution of commands.

```