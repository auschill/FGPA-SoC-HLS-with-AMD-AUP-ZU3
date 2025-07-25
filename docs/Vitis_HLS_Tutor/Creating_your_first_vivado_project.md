---
layout: default
title: Creating your first vivado project
parent: Preparation
nav_order: 2.05
---

# Open Vivado

Vivado (2023.2) GUI should open as below
<div align=center><img src="new_images/vivado_open_page.PNG" alt="drawing" width="600"/></div>
Click "Create Project"

Name your project the appropriate name in the subfolder

Select "RTL Project"
<div align=center><img src="new_images/select_Rtl.PNG" alt="drawing" width="600"/></div>
Next, you can choose to select a file already created, or create a new source file for your project. Which, you can always start a project with no files, and go in and add sources after the project is created.
<div align=center><img src="new_images/create_new_file.PNG" alt="drawing" width="600"/></div>
Click Next until the "Default Part" page. There are two tabs, Parts, and Boards. Go under the boards tab, see if you see AMD AUP ZU3. Additionally, you can search the parts for `xczu3eg-sfvc784-2-e` under the parts tab if your board is not already listed. Go to Add your board file page on this site.
<div align=center><img src="new_images/snip_of_board_selection.PNG" alt="drawing" width="600"/></div>

Click finish.

Now your project is open. To add new sources, go to the "add sources" section under the project manager. Here you can add simulation files, sources files, and constraint file to your project as need. 
<div align=center><img src="new_images/add_sources.PNG" alt="drawing" width="600"/></div>

You just created your first Vivado project.
