# TeleForm Connect Agent for FileBound

## Install
Place the FileBound Hosted.vbe file in the scripts folder on your TeleForm system. 
* For a desktop install the path would be C:\programdata\Cardiff\TeleForm\scripts
* For a Workgroup/Enterprise system it would be \\\yourshare\TeleForm\scripts

### Usage
Open your form in TeleForm Designer and select Form -> Auto Export Setup. From the drop-down, select FileBound Hosted. If this entry does not exist, make sure the vbe is in the scripts folder and restart the Designer application. Once the export is selected, click the fields tab and click automap. Click the "Main" tab again and click the "Save as" button. Enter your FileBound Hosted site URL and your user/password. If correct, the projects dropdown will populate. Select the project you want your form to go into. Map the fields to TeleForm fields. Once done, click OK. Click the "File Export" tab and enable "Export files". Select a folder to output the images and the image format you need.


## Support
This connect agent only works with hosted FileBound sites. If you need an On-Premise Connect Agent, [please let us know](https://github.com/BinaryOffice/TeleFormFileBound/issues)

This software is provided as is. If you would like to purchase a support contract, please email sales@binaryoffice.com or call us at 480 970 6900
