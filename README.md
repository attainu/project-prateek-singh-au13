# JUNK FILES ORGANIZER
 To make that task of organizing the files easy the below Python script is develop to so that all the files are organized in a well-manner within seconds.

# Create Dictionaries:
The code below will create the defined Directories:

DIRECTORIES = {
    "HTML": [".html5", ".html", ".htm", ".xhtml"],
    "IMAGES": [".jpeg", ".jpg", ".tiff", ".gif", ".bmp", ".png", ".bpg", "svg",
               ".heif", ".psd"],
    "VIDEOS": [".avi", ".flv", ".wmv", ".mov", ".mp4", ".webm", ".vob", ".mng",
               ".qt", ".mpg", ".mpeg", ".3gp"],
    "DOCUMENTS": [".oxps", ".epub", ".pages", ".docx", ".doc", ".fdf", ".ods",
                  ".odt", ".pwi", ".xsn", ".xps", ".dotx", ".docm", ".dox",
                  ".rvg", ".rtf", ".rtfd", ".wpd", ".xls", ".xlsx", ".ppt",
                  "pptx"],
    "AUDIO": [".aac", ".aa", ".aac", ".dvf", ".m4a", ".m4b", ".m4p", ".mp3",
              ".msv", "ogg", "oga", ".raw", ".vox", ".wav", ".wma"],
    "PLAINTEXT": [".txt", ".in", ".out"],
    "PDF": [".pdf"],
    "ZIPPEDS": [".rar",".zip",".7z", ".bzip2",".gzip",".tar",".wim", ".xz",]
        
}
# LIBRARIES USED :
import os         -  to get all the files from the directories,to create directories  
import shutil     -  to move the files from one directory to another

# APPROACH USED : 

EXT based organization - For the Extension based organization we have created a dictionary and saved all the possible extensions I can think of to access the extensions and afterwords moving the files to their specified directories. Checking the extension of the file in the computer directory and then compairing it with the dictionary values of extensions if matched then creating the new directory named organizer and inside it moving the different files according to the specified new directories. 


# HOW TO RUN :
Step 1 - Enter the path of folder which need to be organized 
Step 2 - It will show all the file present that can be organized and asked permission to proceed 
Step 3 - if y is enter program will proceed and organized the folder also give the count of file organized 
