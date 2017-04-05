# TeleForm Connect Agent for ApplicationXtender 8.1

## Install
Place the ApplicationXtender 8.1.vbe file in the scripts folder on your TeleForm system. 
* For a desktop install the path would be C:\programdata\Cardiff\TeleForm\scripts
* For a Workgroup/Enterprise system it would be \\\yourshare\TeleForm\scripts

### Usage
This connect agent requires that the AppXtenderReST service be installed. Please see the [AppXtender documentation](https://support.emc.com/docu70698_ApplicationXtender-8.1-Installation-Guide.pdf?language=en_US "EMC Site") for instructions. Open your form in TeleForm Designer and select Form -> Auto Export Setup. From the drop-down, select ApplcationXtender 8.1. If this entry does not exist, make sure the vbe is in the scripts folder and restart the Designer application. Once the export is selected, click the fields tab and click automap. Click the "Main" tab again and click the "Save as" button. Enter the AppXtenderReST URL and your user/password. If correct, the datasource dropdown will populate. Select your datasource and the applications you have create permissions to will populate. Select your application and then map the fields to TeleForm fields. Once done, click OK. Click the "File Export" tab and enable "Export files". Select a folder to output the images and the image format you need.

### Multi-Index support
If you have an application that is configuired for multiple index for a single document, you can configure the connect agent to do this as long as you have a Table on your form. The option will only appear when there is a table on the form **AND** the AX application is configured for multi-index. You must include these two predefined fields in your table: BatchNo and BatchPgNo. Click save as in the auto export as above and fill out everything. Once you click "Multi-Index", you will be instructed to click save. Click on the Table tab, select ApplicationXtender 8.1 from the drop-down and "Save as" again and you will be able to map the TeleForm fields from the table to AX. 

## Support
This software is provided as is. If you would like to purchase a support contract, please email sales@binaryoffice.com or call us at 480 970 6900
