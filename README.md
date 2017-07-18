# imageFolderDescriptor
Training project for python. Uses external image recognition API to generate image names for chosen folder.

### Requirements:
**Functional**
  
* Should be a console application written in Python 3,  
* should take 2 parameters as input - <folder_with_images> <destination_folder> and:
  * copy images to a new folder,
  * name them in a way that describes their content,
  * include 5 most popular tags describing images in a `.txt` file.
  
**Non-functional**
* All exceptions should be handled,
* tests need to be written for cases that might generate exceptions,
* should use external image description api.

**Process**
1. Use "projects" tab for tracking progress.
2. No stupid commit messages.

**Structure**
Aplication should consist of at least 4 files that contain **__classes__**.
1. Main class.
2. Class for connection and retrieving results from external API.
3. Class that handles reading and storing data.
4. Class which will generate names and establish 5 most popular tags.

Good luck!
