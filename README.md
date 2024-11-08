Office Installer

Automate your Microsoft Office installation with a custom Configuration.xml file.
Prerequisites

    Download the Office Setup tool:

    https://officecdn.microsoft.com/pr/wsus/setup.exe

    Prepare your Configuration.xml file. This file controls the Office installation settings, including:
        Applications to install
        Update channels
        Language preferences
        Installation path

Usage Instructions

    Place setup.exe and Configuration.xml in the same directory.

    Run the setup command:

cd <path_to_files>
setup.exe /configure Configuration.xml
