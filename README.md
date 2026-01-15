# LarcCAD 2026 — SolidWorks Project

This repository contains the **SolidWorks CAD files** for the **LarcCAD 2026 robot project**, including parts, assemblies, drawings, and manufacturing exports (STL / DXF).

**IMPORTANT:** This project uses **Git Large File Storage (Git LFS)**.  
**Do NOT use “Download ZIP” from GitHub.**

---

## How to Open This Project

### 1. Install Required Software
- **SolidWorks** (same or newer version than used to create the files)  
- **Git**  
- **Git LFS**

After installing Git LFS, run this **once** in your terminal (Git Bash or command prompt):

```bash
git lfs install
```

Once you see Git LFS initialized., you’re done and ready to continue.

### 2. Clone the Repository (DO NOT download ZIP)
```bash
git clone https://github.com/HANS27barron/LarcCAD2026.git
```
This ensures you get the real CAD files, not placeholders.

### 3. Open in SolidWorks
Open SolidWorks
Go to File → Open
Navigate to the cloned folder
Open:
Assemblies → .sldasm
Parts → .sldprt
Drawings → .slddrw

Do not move files after cloning — SolidWorks assemblies rely on relative paths.

# View-Only / No Editing
If you only want to view the project:

You still must clone, not download ZIP

Open files normally in SolidWorks

Do not save changes or rename files

Optional: Use eDrawings for lightweight viewing (assemblies + parts)

## Folder Structure
```bash
LarcCAD_2026/
├── Assemblies/   → Robot assemblies (.sldasm)
├── Parts/        → Individual components (.sldprt)
├── Prints/       → Manufacturing files (STL / DXF)
```

## Notes
- This repository uses Git LFS for SolidWorks files
- Folder additions will not break the project
- Clone to your PC and open assemblies from the cloned folder
