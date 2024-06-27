# README

# Unix Command Practice

This activity is designed to help you refresh your unix command line skills, which is helpful for getting started with Node's fs module.

Follow the instructions to work with the sample content provided in this repository.

## Instructions

1. **Navigate:** Open your terminal and use the `cd` command to enter this directory.
2. **Create:**
   - Make a new directory inside `documents` called `project-plan`.
   - Create a new file within the `project-plan` directory called `goals.txt`. Use the `touch` command.
3. **Copy:**
   - Create a copy of `draft.txt` and call it `revised_draft.txt`. Use the `cp` command.
   - Copy the image into the `project-plan` directory
4. **Rename:**
   - Change the name of `notes.txt` to `meeting_notes.txt`. Use the `mv` command.
   - rename the image to something more appropriate to the image content. Use kebab or snake case
5. **Move:**
   - Move `revised_draft.txt` into the `project-plan` directory.
6. **Delete:**
   - Remove the `documents` directory and all of its contents. Use the `rm -r` command (be careful!).

## Bonus Challenge

- Try using the `cat`, `less`, or `more` commands to view the contents of any text file you created or modified.
- Experiment with `ls -l` to see detailed information about the files and directories.

## Node.js Connections

These Unix commands relate directly to Node.js file system (fs) module functions:

- `mkdir` is like `fs.mkdir` (create directory)
- `touch` (creating an empty file) is similar to `fs.writeFile` (with no content)
- `cp` is like `fs.copyFile`
- `mv` can be used for both renaming (like `fs.rename`) and moving
- `rm -r` is similar to `fs.rmdir` (remove directory) and `fs.unlink` (remove file)

## Image License

- [Close-Up Shot of a Stack of Pancakes on a Plate
  ](https://www.pexels.com/photo/close-up-shot-of-a-stack-of-pancakes-on-a-plate-14263515/) By [Esra Korkmaz](https://www.pexels.com/@esrakorkmaz/) Licensed for free usage
