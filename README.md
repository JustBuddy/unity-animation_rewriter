# unity-animation_rewriter
Little script that transfers unity animation properties via name matching.  
Originally made for a specific project as tooling, so very nieche.  
Enjoy  

## Define:
sourceFolderPath = The path which contains the .anim files in question. Like /Packages/com.package.stuff/Source  
targetRootPath = Path which contains folders with the same names as the .anim files.  

## Flow:
- Reads names of the animation from sourceFolderPath.  
- Name-Matches them with folder names inside targetRootPath.  
- Replaces the property (here RootQ) recursively from source to all animations in target.  