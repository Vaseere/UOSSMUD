# Unofficial Squaresoft MUD Mudlet Pack
This pack is designed to work with Mudlet only.

The `UOSSMUD - Core` package is designed as a hub package for managing other Mudlet packages designed for UOSSMUD.

If you're looking for the standalone versions of the Map or GUI packages, check [here](https://github.com/Vaseere/UOSSMUD/tree/main/Standalone%20Packages).

<br>

## Installing the UOSSMUD Core Package
Run the following command:

`lua installPackage([[https://github.com/Vaseere/UOSSMUD/raw/refs/heads/main/Core/UOSSMUD%20-%20Core.mpackage]])`

<br>

## Installing the UOSSMUD Map Package
The UOSSMUD Map package is completely optional, but highly recommended.

After installing the `UOSSMUD - Core` package, run the following command inside Mudlet to install the map for UOSSMUD:

`uoss install map package`

Once the package is installed, run the following command to install the map file for UOSSMUD:

`uoss update map`

<br>

## Installing the UOSSMUD GUI Package
The UOSSMUD GUI package is completely optional.<br>
Check the [GUI Readme](https://github.com/Vaseere/UOSSMUD/tree/main/GUI) for more information about the GUI package for UOSSMUD.<br>

After installing the `UOSSMUD - Core` package, run the following command inside Mudlet:

`uoss install gui package`

After the GUI package has been installed, run the following commands to reload the GUI and adjust the main display borders:

`uoss gui reload`
`uoss config borders`

After the borders have been adjusted, run the following command to install the monster database:

`uoss update monsters`
