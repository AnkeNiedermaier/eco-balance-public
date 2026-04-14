# EcoBalance

The PythonPart offers different functions to evaluate the eco balance, mainly GWP_ and AP_value, of components and models in ALLPLAN:
- **assign** eco related attributes
- **create** corresponding **data sheets**
- **show** overview **diagrams** of the eco impact

As in almost all LCA calculation, basis is the object material, for which individual eco values have been published. They are collocated in the **OEKOBAUDAT** database which is also delivered with the PythonPart as an **Excel file** **Ecobaudat_Database.xlsx**.

> ⚠️IMPORTANT\
The status and content of the Excel file might have been changed slightly since the release of the PythonPart. Whereas the content can be updated or enlarged, the existing structure of the file has to be kept **unchanged**. Otherwise the PythonPart might no longer work accurate.

## Installation

The PythonPart **EcoBalance** can be installed directly from the PluginManager in ALLPLAN. 

Alternatively, the corresponding ***.allep** package can be downloaded from the [release page](https://github.com/AnkeNiedermaier/eco-balance-public/releases). ***.allep** files are ALLPLAN internal setups that can be installed via drag and drop into the program window.

At least the version 2026 is needed to install the PythonPart.

## Installed PythonPart Scripts

If the installation was successfull, the PythonPart **EcoBalance** as well as the **Ecobaudat_Database.xlsx** file can be found
in the ALLPLAN Library:
`Office` → `Library` → `ALLPLAN GmbH` → `EcoBalance`

Besides the library, the PythonPart can also be found in the ActionBar in a newly created task area **EcoBalance** inside the task **Plug-ins**.

Whereas the location of all otherfiles has to be kept, the **Excel table** can arbitrary be copied or moved and even be renamed afterwards.

## Preparation

To use the different functions of the PythonPart, all objects that should be considered need appropriate material information. Therfor the first step is to pick up the relevant material name from the **Excel file** and add it as value to the choosen **material key** attribute.

Available materials are listed in the **Name (de)** or **Name (en)** columns of the table. Which ALLPLAN attribute is used as **material key** is free of choice, but always using the same is highly recommended. Otherwise the objects can not be evaluated togehter.

## Workflow

In general, all installed PythonParts can be found in the Library palette, no matter if an additional ActionBar entry is created or not. They are started either with a **double-click** on the icon or per **Drag and Drop** into the viewport. This shows the corresponding Properties palette and executes the underlying skripts.

> ⚠️IMPORTANT\
> [!Tip]
The status and content of the Excel file might have been changed slightly since the release of the PythonPart. Whereas the content can be updated or enlarged, the existing structure of the file has to be kept **unchanged**. Otherwise the PythonPart might no longer work accurate.

The palette is divided into a general part on the top which is relevant for all 

