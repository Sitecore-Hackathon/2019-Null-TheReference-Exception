# Documentation

## Summary

**Category:** Best use of SPE to help Content authors and Marketers

Bulk Operations Module is build for both content editors and developers to easily manipulate items in bulk by using Sitecore Powershell Extension. Module creates a new Ribbon that includes available operations. Available Bulk operations include:

* Add Current Item

* Add With Wizard

* View Items

* Report Items

* Clear Items

* Edit Fields

* Delete Items

* Expand Tokens 

* Rename Items

* Add Version

* Remove Version

* Publish

* Run Powershell Command

## Pre-requisites

- Sitecore Powershell Extensions 5.0

## Installation

1. Use the Sitecore Installation Wizard to install the [package](#sc.package/Bulk Operations Manager-1.0.zip)
2. Use the Sitecore Installation Wizard to install the [package](#Test Content Package.zip)

## Configuration

Even though you can start working directly with package installation, if you want to make more advanced configuration you can use the item with the following path below.

/sitecore/system/Modules/Bulk Operation Module/General Configuration

This item includes a couple of property that you can change. 

User Configuration Root: This is the folder which stores temporary user files.

Multiedit Temporary Template Root: When you make edits with multi item edit feature, temporary template files are stored under this folder.

Multiedit Temporary Item Root: This folder includes temporary items for multi edit feature.

Multiedit Multiple Values Token: This value used as a token in multi item edit process.


## Usage

* Add Current Item

Add selected item from Content Editor to the list of Bulk items to use in Bulk Operations.

![Add Current](images/Add-Remove%20Items/Add%20Current/Step%201.png?raw=true "Add Current")

* Add with Wizard

Add selected item's only Children, Item itself and also Children or only Item itself.

![Step 1](images/Add-Remove%20Items/Add%20with%20Wizard/Step%201.png?raw=true "Step 1")

![Step 2](images/Add-Remove%20Items/Add%20with%20Wizard/Step%202.png?raw=true "Step 2")

Then filter items by adding rules, Filter by updated, Filter by created, Updated since or Updated until, Created since, Created until to use in Bulk operations.

![Step 3](images/Add-Remove%20Items/Add%20with%20Wizard/Step%203.png?raw=true "Step 3")

![Step 4](images/Add-Remove%20Items/Add%20with%20Wizard/Step%204%20(Rule).png?raw=true "Step 4")

![Step 5](images/Add-Remove%20Items/Add%20with%20Wizard/Step%205.png?raw=true "Step 5")

Then select from result items.

![Final](images/Add-Remove%20Items/Add%20with%20Wizard/Final.png?raw=true "Final")

* Clear Items

Clear all selected items that is added for Bulk Operations.

![Step 1](images/Edit%20Items/Delete%20Items/Step%201.png?raw=true "Step 1")

![Step 2](images/Edit%20Items/Delete%20Items/Step%202.png?raw=true "Step 2")

* Edit Fields
  
After adding items for Bulk Operations, you can edit common fields on those items.

![Step 1](images/Edit%20Items%5CEdit%20Fields%5CStep%201.png?raw=true "Step 1")

![Step 2](images/Edit%20Items%5CEdit%20Fields%5CStep%202.png?raw=true "Step 2")

![Step 3](images/Edit%20Items%5CEdit%20Fields%5CStep%203.png?raw=true "Step 3")

![Step 4.1](images/Edit%20Items%5CEdit%20Fields%5CStep%204.1.png?raw=true "Step 4.1")

![Step 4.2](images/Edit%20Items%5CEdit%20Fields%5CStep%204.2.png?raw=true "Step 4.2")

* Expand Tokens

By using this operation you can expand tokens to item values.

![Step 1](images/Edit%20Items%5CExpand%20Tokens%5CStep%201.png?raw=true "Step 1")

![Step 2](images/Edit%20Items%5CExpand%20Tokens%5CStep%202.png?raw=true "Step 2")

![Step 3](images/Edit%20Items%5CExpand%20Tokens%5CStep%203.png?raw=true "Step 3")

![Step 4](images/Edit%20Items%5CExpand%20Tokens%5CStep%204.png?raw=true "Step 4")

* Rename Items

You can bulk edit all item names added to Bulk Operation list.

![Step 1](images/Edit%20Items%5CRename%20Items%5CStep%201.png?raw=true "Step 1")

![Step 2](images/Edit%20Items%5CRename%20Items%5CStep%202.png?raw=true "Step 2")

![Step 3](images/Edit%20Items%5CRename%20Items%5CStep%203.png?raw=true "Step 3")


* Add  Language Version

You can bulk add language versions to all items added to Bulk Operation list.

![Step 1](images/Language%20Versions%5CAdd%20%20Language%20Version%5CStep%201.png?raw=true "Step 1")

![Step 2](images/Language%20Versions%5CAdd%20%20Language%20Version%5CStep%202.png?raw=true "Step 2")

* Remove Language Version

You can bulk remove language versions to all items added to Bulk Operation list.

![Step 1](images/Language%20Versions%5CRemove%20Language%20Version%5CStep%201.png?raw=true "Step 1")

![Step 2](images/Language%20Versions%5CRemove%20Language%20Version%5CStep%202.png?raw=true "Step 2")

![Step 3](images/Language%20Versions%5CRemove%20Language%20Version%5CStep%203.png?raw=true "Step 3")

* Publish

You can bulk publish items added to Bulk Operation list.

![Step 1](images/Publish%5CStep%201.png?raw=true "Step 1")

![Step 2](images/Publish%5CStep%202.png?raw=true "Step 2")

* View Items

You can view items added to Bulk Operation list.

![Step 1](images/View%5CView%20Items%5CStep%201.png?raw=true "Step 1")

![Step 2](images/View%5CView%20Items%5CStep%202.png?raw=true "Step 2")

* Report Items

You can report items added to Bulk Operation list.

![Step 1](images/View%5CReport%20Items%5CStep%201.png?raw=true "Step 1")

![Step 2](images/View%5CReport%20Items%5CStep%202.png?raw=true "Step 2")

* Run Powershell Command

You can try any Powershell Command on items added to Bulk Operation list. You can reach all selected Items by -Items paramater.

![Powershell Command](images/Advanced/PowershellCommand.png?raw=true "Powershell Command")

## Video

Please provide a video highlighing your Hackathon module submission and provide a link to the video. Either a [direct link](https://www.youtube.com/watch?v=EpNhxW4pNKk) to the video, upload it to this documentation folder or maybe upload it to Youtube...


[![Sitecore Hackathon Video Embedding Alt Text](https://youtu.be/IM_6QWcrzBQ)](https://youtu.be/IM_6QWcrzBQ)
[![Sitecore Hackathon Video Embedding Alt Text](https://youtu.be/Gze25qf40tw)](https://youtu.be/Gze25qf40tw)