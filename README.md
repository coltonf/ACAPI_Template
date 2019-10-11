# ACAPI_Template
 Template for creating Archicad 22 addons.

Support for Visual Studio and Visual Studio Code (with build tasks)

## Setup

- Download template
- Copy template to appropriate location 3 folders from Support folder (included in Archicad API download)
- Run Setup.ps1 (Shift + Rightclick at template location > Open Powershell Window here... > "./setup.ps1")
- Enter addon name, follow any further prompts

During setup, the script will ask you to enter your Archicad developer ID as well as create/enter a valid Addon ID, these get properly added to ```RFIX/project_nameFix.grc``` so that the addon will be verified and load properly within Archicad.

When these prompts are shown, the developer website page will attempt to open, sign in and you can copy/paste your developer ID.

The Addon ID prompt will open the tool to create a addon ID, if one is already created, simply find and enter it. 

The result will be that all instances of the default ```project_name``` will be replaced with your new addon name, and IDs will be properly set, so that the new Add-On project can be built without error out of the box.

Remember to set addon menu strings accordingly (32000, 32500 etc)

