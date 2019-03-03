# Documentation

## Summary

## Pre-requisites

- Sitecore Powershell Extensions 5.0

## Installation

1. Use the Sitecore Installation Wizard to install the [package](#sc.package/Bulk Operations Manager-1.0.zip)
2. Use the Sitecore Installation Wizard to install the [package](#Test Content Package.zip)

After installation you can work directly without any further modifications.

Package installs the items below automatically for you.

/sitecore/system/Modules/Bulk Operation Module

/sitecore/system/Modules/PowerShell/Script Library/Bulk Operations Manager

/sitecore/templates/Modules/Bulk Operations Manager

/sitecore/content/Applications/Content Editor/Ribbons/Chunks/BulkOperations - Add

/sitecore/content/Applications/Content Editor/Ribbons/Chunks/BulkOperations - Advanced

/sitecore/content/Applications/Content Editor/Ribbons/Chunks/BulkOperations - Edit

/sitecore/content/Applications/Content Editor/Ribbons/Chunks/BulkOperations - Language Versions

/sitecore/content/Applications/Content Editor/Ribbons/Chunks/BulkOperations - Publish

/sitecore/content/Applications/Content Editor/Ribbons/Chunks/BulkOperations - View

/sitecore/content/Applications/Content Editor/Ribbons/Ribbons/Default/Bulk Operations

/sitecore/content/Applications/Content Editor/Ribbons/Strips/Bulk Operations

## Configuration

Even though you can start working directly with package installation, if you want to make more advanced configuration you can use the item with the following path below.

/sitecore/system/Modules/Bulk Operation Module/General Configuration 

This item includes a couple of property that you can change. 

User Configuration Root: This is the folder which stores temporary user files.

Multiedit Temporary Template Root: When you make edits with multi item edit feature, temporary template files are stored under this folder.

Multiedit Temporary Item Root: This folder includes temporary items for multi edit feature.

Multiedit Multiple Values Token: This value used as a token in multi item edit process.


## Video

Please provide a video highlighing your Hackathon module submission and provide a link to the video. Either a [direct link](https://www.youtube.com/watch?v=EpNhxW4pNKk) to the video, upload it to this documentation folder or maybe upload it to Youtube...


[![Sitecore Hackathon Video Embedding Alt Text](https://youtu.be/IM_6QWcrzBQ)](https://youtu.be/IM_6QWcrzBQ)
