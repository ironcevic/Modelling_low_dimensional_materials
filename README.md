# Modelling low dimensional materials

This repository will host content related to the "Modelling low dimensional materials" unit.

## Repository Structure

This repository is organized into the following folders:

- **lectures/** - Lecture materials, slides, and presentations
- **notes/** - Course notes and study materials
- **exercises/** - Practice problems and exercise solutions
- **simulations/** - Simulation scripts and code
- **data/** - Datasets and data files
- **references/** - Reference materials, papers, and documentation

## How to Add Folders to This Repository

### Understanding Git and Folders

Git tracks files, not empty folders. To add a new folder to the repository, you need to:

1. **Create the folder locally**:
   ```bash
   mkdir folder_name
   ```

2. **Add at least one file to the folder**:
   Git will only track folders that contain files. You can either:
   - Add a meaningful file (like a README.md explaining the folder's purpose)
   - Add a `.gitkeep` file (a convention to preserve empty folders)
   
   ```bash
   # Option 1: Add a README
   echo "# Folder Name" > folder_name/README.md
   
   # Option 2: Add a .gitkeep file
   touch folder_name/.gitkeep
   ```

3. **Stage and commit the folder**:
   ```bash
   git add folder_name/
   git commit -m "Add folder_name directory"
   ```

4. **Push to GitHub**:
   ```bash
   git push origin main
   ```

### Example: Adding a New Folder

Let's say you want to add a `projects` folder:

```bash
# Create the folder
mkdir projects

# Add a .gitkeep file
touch projects/.gitkeep

# Stage the changes
git add projects/.gitkeep

# Commit the changes
git commit -m "Add projects folder"

# Push to GitHub
git push origin main
```

### Best Practices

- **Use descriptive folder names**: Choose names that clearly indicate the folder's content
- **Add README files**: Include a README.md in each folder to explain its purpose
- **Keep organized**: Group related files together in appropriate folders
- **Use .gitignore**: Exclude files you don't want to track (e.g., temporary files, large datasets)

## Contributing

Feel free to add your materials to the appropriate folders following the structure above. 
