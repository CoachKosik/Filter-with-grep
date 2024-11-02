# Linux commands - Filter with grep

## Objective

This lab focuses on enhancing information retrieval skills within the Linux environment. By leveraging the `grep` command and piping techniques, users can efficiently search for specific patterns within files and directories. This skill is crucial for security analysts to quickly identify relevant information, analyze logs, and investigate potential security incidents.

## Project description

This project focuses on utilizing the `grep` command and piping to efficiently search for and filter information within Linux file systems. By mastering these techniques, individuals can effectively analyze log files, configuration files, and other text-based data to identify security threats, troubleshoot issues, and gather valuable insights.

## Skills Learned

1. **Command-Line Navigation:** Proficiency in navigating the Linux file system using commands like `cd` and `ls`.
2. **File Content Search:** The ability to search for specific patterns within files using the `grep` command.
3. **Piping:** The skill of combining multiple commands to create more complex operations, such as filtering and redirecting output.
4. **Regular Expressions:** A foundational understanding of regular expressions to refine search patterns and match specific text patterns.
5. **File System Understanding:** Knowledge of Linux file system structure and how to locate files within directories.

By mastering these skills, information within large datasets, analyze logs, and identify potential security threats can efficiently searched.

## Tools Used

1. **Linux Terminal:** The primary tool used to interact with the Linux system and execute commands.
2. **grep:** A powerful command-line utility used to search for patterns within text files.
3. **Pipe (|):** A mechanism used to chain commands together, sending the output of one command as input to the next.
4. **Basic Linux Commands:** Commands like `cd` and `ls` are used to navigate the file system.

## Steps
1. Search for error messages in a log file

   1. Navigate to the /home/analyst/logs directory.
   2. Use grep to filter the server_logs.txt file, and return all lines containing the text string error.
      
2. Find files containing specific strings

   1. Navigate to the /home/analyst/reports/users directory.
   2. Using the pipe character (|), pipe the output of the ls command to the grep command to list only the files containing the string Q1 in their names.
   3. List the files that contain the word access in their names.
  
3. Search more file contents

   1. Display the files in the /home/analyst/reports/users directory.
   2. List the files in the current directory.
   3. Display the contents of the Q1_added_users.txt file.

6. Navigate to a directory and locate a file

   1. Navigate to the /home/analyst/logs directory.
   2. Search the Q2_deleted_users.txt file for the username jhill.
   3. Search the Q4_added_users.txt file to list the users who were added to the Human Resources department.<br>

<![grep](https://github.com/user-attachments/assets/6c3110b5-69d3-4f83-960d-8e5474ac7080)
br>

### Summary

This lab provided hands-on experience in using the `grep` command to efficiently search for specific information within files. By leveraging `grep` and piping techniques, users can effectively filter and extract relevant data from large datasets, making it a valuable tool for security analysts and system administrators.
