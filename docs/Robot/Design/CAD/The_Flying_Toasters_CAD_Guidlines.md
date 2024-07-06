# The Flying Toasters CAD Guidelines


!!! warning
    This page is a work in progress.

The following are the CAD design guidelines for the Flying Toasters robots. These guidelines are used to ensure that the robot is designed in an organized, structured manner. If the guidelines are followed it will be much easier to design the robot and ensure that it is built correctly.

## Example Robot File Structure

```
├── Main Assembly
|   ├── Drivetrain Assembly
|   |   ├── Drivetrain Main Assembly
|   |   ├── Drivetrain Part Studios Folder
|   |   |   ├── Drivetrain Part Studio 1
|   |   |   ├── Drivetrain Part Studio 2
|   |   |   ├── ...
|   |   ├── Drivetrain Drawings Folder
|   |   |   ├── Drivetrain Drawing 1
|   |   |   ├── Drivetrain Drawing 2
|   |   |   ├── ...
|   |   ├── Drivetrain CAD Imports
|   |   |   ├── CAD Import 1
|   |   |   ├── CAD Import 2
|   |   |   ├── ...
|   ├── Intake Assembly
|   ├── Climber Assembly
|   ├── Launcher Assembly
|   ├── Bumper Assembly
|   ├── Sizing Box Folder
|   |   ├── Frame Perimeter Sizing Box
|   |   ├── Max Extension Sizing Box
|   |   ├── ...
|   ├── Electronics Folder
```

## Part Naming Convention

TFT_DT_001_Descriptive_Name

- TFT - The Flying Toasters
- DT - Drivetrain (Shortened Assembly Name)
- 001 - Unique Part Number
- Descriptive Name - A descriptive name for the part

| Type | Toaster Nomenclature |
| --- | --- |
| Main Assembly | TFT Assembly_Name Main |
| Sub Assemblies | TFT Sub Assemblies Name |
| Part Studio | TFT_DT_001_Descriptive_Name |
| Drawing | TFT_DT_001_Descriptive_Name Drawing # |



## Part Drawings
Part Drawings are used to show the manufacturing team what the dimensions of the part should be. If you want a part to be manufactured, you need to have a part drawing.

!!! note
    All non-3D Printed and non-COTS parts should have a part drawing. This includes all tubes, plates, shafts, billet components, and sheetmetal parts used in a robots construction.

The Flying Toasters use a common Drawing template for all part drawings.
An example of The Flying Toasters part drawings are shown below.

