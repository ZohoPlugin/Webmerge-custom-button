# Webmerge-custom-button


## To add custom button in Webmerge extension

* Click the Settings Icon(Setup) -> Customization -> Modules -> Select the Module to which the Custom Button have to be create -> Layout -> Links and Buttons -> Create New Button.
Give the Name of the Button (For Ex: Webmerge).

* Add Description if you want.

* Select the button to be placed.

* Select "Invoke a URL" to perform the action.

* Given the below URL in Construct Your URL :
  - https://extensions.zoho.com/plugin/webmerge/handler?action=mergeDocumentPage&module=ModuleName&rec_id=${Module.ModuleId}
  - For Ex : https://extensions.zoho.com/plugin/webmerge/handler?action=mergeDocumentPage&module=Lead&rec_id=${Lead.LeadId}

* Select the button on Where to show the content of the button action.

* Select Which Profiles to show this action.

* Click Save.
