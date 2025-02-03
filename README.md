# Expo DocumentPicker - Incompatibility with certain file types

This repository contains a bug report and solution for an incompatibility issue encountered when using the Expo DocumentPicker library with specific file types.  The issue manifests as an unexpected error during file selection.

## Bug Description
The Expo DocumentPicker library fails to correctly handle files of certain types, resulting in an uninformative error message.  This prevents users from selecting these file types through the library.

## Solution
The solution involves either using an alternative file picker library that offers broader file type compatibility or pre-processing the files to convert them to a supported format before they're selected via DocumentPicker.