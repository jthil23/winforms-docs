---
title: Add Remove Theme Files
page_title: Add Remove Theme Files | RadThemeManager
description: This article shows how you can edit the list of XML files loaded into a Theme Manager.
slug: winforms/tools/visual-style-builder/adding-custom-themes-to-your-application/editing-themes
tags: editing,themes
published: True
position: 4
previous_url: tools-visual-style-builder-adding-custom-themes-to-your-application-editing-themes
---

# Add Remove Theme Files

>important RadThemeManager cannot load the theme if it is saved as package (tssp file). This is shown in the following article: [using custom themes]({%slug winforms/themes/using-custom-themes%})

To edit the list of themes loaded into a Theme Manager, follow these steps:

1. Select the RadThemeManager control, and then open its __Smart Tag__ menu. 

    ![tools-visual-style-builder-adding-custom-themes-to-your-application-editing-themes 001](images/tools-visual-style-builder-adding-custom-themes-to-your-application-editing-themes001.png)

1. Select __Edit Themes__to open the __ThemeSource Collection Editor__.

    ![tools-visual-style-builder-adding-custom-themes-to-your-application-editing-themes 002](images/tools-visual-style-builder-adding-custom-themes-to-your-application-editing-themes002.png)

1. Click __OK__ when you are finished working in the editor.

## To Add a New Theme to the Theme Manager

1. Click __Add__.
            

1. Choose the __StorageType__ for the theme. Select __Resource__ or __File__.

1. Set the __ThemeLocation__ (resource name or file location).

## To Remove a Theme from the Resource Manager

1. Select the theme that you wish to remove.
         

1. Click __Remove__.
         

## To Change the Properties for an Existing Theme

1. Select the theme that you wish to edit.
          

1. Set the __StorageType__ and __ThemeLocation__ properties to your desired values. 
        

>caution When setting the __ThemeLocation__ for a __Resource__ storage type be sure to include the project namespace. The naming convention for ThemeManager to find the resource is \<my project namespace\>.\<theme name\>.xml. In project "MyProject" with theme resource file "MyTheme.xml", the fully qualified resource name should be entered as "MyProject.MyTheme.XML".
>
